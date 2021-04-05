To resolve the errors caused by generation some extra files we will do troubleshooting in CLI.



When generating code from a Java file, CobiGen makes use of Java reflection for generating templates. In order to do that, the CLI needs to find the compiled source code of your project.

If you find an error like Compiled class foo\bar\EmployeeEntity.java has not been found, it means you need to run mvn clean install on the input project so that a new target folder gets created with the needed compiled sources.



Now in the next step we will see how to integrate CobiGen in eclipse.
