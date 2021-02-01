And start CobiGen again


## CobiGen Java

Open the following java file in the IDE.
`devonfw/workspaces/main/cobigenexample/core/src/main/java/com/example/application/cobigenexample/customermanagement/dataaccess/api/CustomerEntity.java`{{open}}

You can use the plugin simply via the context menu. Make a right click on the java file (in the explorer on the left or in the editor itself). The context menu will open and you can start the CobiGen Plugin by clicking on 'CobiGen'.

A terminal will open on the bottom of the IDE and CobiGen CLI will start.

You can choose the templates CobiGen should use by entering the numbers in the terminal of the IDE.

`1,3,5,6,8`

Switch back to the IDE. You can see that cobigen added code in some of the generated files. Open the Customer.java file which is located in the api module of the project in the package &#39;customermanagement/common/api/&#39;. You can see cobigen added the new getter and setter methods for the new &#39;company&#39; property.