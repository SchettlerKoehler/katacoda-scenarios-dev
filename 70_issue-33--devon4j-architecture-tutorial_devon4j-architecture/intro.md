There are many different views that are summarized by the term architecture. First, we will introduce the key principles and architecture principles of devonfw. Then, we will go into details of the the architecture of an application.

= Key Principles

For devonfw we follow these fundamental key principles for all decisions about architecture, design, or choosing standards, libraries, and frameworks:

* *KISS* 
Keep it small and simple
* *Open* 
Commitment to open standards and solutions (no required dependencies to commercial or vendor-specific standards or solutions)
* *Patterns* 
We concentrate on providing patterns, best-practices and examples rather than writing framework code.
* *Solid* 
We pick solutions that are established and have been proven to be solid and robust in real-live (business) projects.

= Architecture Principles
Additionally we define the following principles that our architecture is based on:

* *Component Oriented Design* 
We follow a strictly component oriented design to address the following sub-principles:
** http://en.wikipedia.org/wiki/Separation_of_concerns[Separation of Concerns]
** http://en.wikipedia.org/wiki/Reusability[Reusability] and avoiding http://en.wikipedia.org/wiki/Redundant_code[redundant code]
** http://en.wikipedia.org/wiki/Information_hiding[Information Hiding] via component API and its exchangeable implementation treated as secret.
** _Design by Contract_ for self-contained, descriptive, and stable component APIs.
** xref:technical-architecture[Layering] as well as separation of business logic from technical code for better maintenance.
** _Data Sovereignty_ (and _high cohesion with low coupling_) says that a component is responsible for its data and changes to this data shall only happen via the component. Otherwise, maintenance problems will arise to ensure that data remains consistent. Therefore, interfaces of a component that may be used by other components are designed _call-by-value_ and not _call-by-reference_.
* *Homogeneity* 
Solve similar problems in similar ways and establish a uniform link:coding-conventions.asciidoc[code-style].

As an architect you should be prepared for the future by reading the https://www.capgemini.com/de-de/wp-content/uploads/sites/5/2020/07/TechnoVision-2020-Report.pdf[TechnoVision].



The definition of each step of this tutorial can be found at https://github.com/devonfw-tutorials/tutorials/tree/main/devon4j-architecture

Feel free to fix any errors you find yourself. You just need to create a pull request to the tutorials repository with your changes.
You can find a description of what to look for when creating a pull request at the devonfw contribution guide: https://devonfw.com/website/pages/docs/CONTRIBUTING.asciidoc.html#contributing.asciidoc_pull-requests
