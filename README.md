# Nexo Backend - BOM

This project uses a Maven BOM to manage dependency versions centrally. 
The BOM ensures that all library versions are compatible with each other, preventing "dependency hell." 
To use it, import the BOM in the <dependencyManagement> section of your pom.xml. 
This allows you to omit version tags when declaring specific dependencies.