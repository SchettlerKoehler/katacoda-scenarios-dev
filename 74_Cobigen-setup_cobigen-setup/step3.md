Below are the commands which we can use on CobiGen CLI.
Using the following command and option you will be able to customize your generation as follows


* cobigen, cg: Main entry point of the CLI. If no arguments are passed, man page will be printed.

* [generate, g]: Command used for code generation.

   - InputGlob: Glob pattern of the input file or the whole path of the input file from which the code will be generated.

   - &lt; --increment, -i &gt; : Specifies an increment ID to be generated. You can also search increments by name and CobiGen will output the resultant list. If an exact match found, code generation will happen.

   - &lt; --template, -t &gt; : specifies a template ID to be generated. You can also search templates by name and CobiGen will output the resultant list.

   - &lt; --outputRootPath, -out &gt;: The project file path in which you want to generate your code. If no output path is given, CobiGen will use the project of your input file.

* [adapt-templates, a]: Generates a new templates folder next to the cobigen cli and stores its location    inside  a configuration file. After executing this command, the CLI will attempt to use the specified Templates folder.

    - &lt; --custom-location, -cl &gt; : Allows the user to choose an absolute file path to a custom location where the CobiGen Templates should be stored and read from.

    - &lt; --verbose, -v &gt; : Prints debug information, verbose log.

    - &lt; --help, -h &gt; : Prints man page.

    - &lt; update, u&gt; : This command compare the artificial pom plug-ins version with central latest version available and user can update any outdated plug-ins version .



