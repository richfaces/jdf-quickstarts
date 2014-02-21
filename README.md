Red Hat JBoss Enterprise Application Platform (EAP) RichFaces Quickstarts
====================
Target Product: WFK
Product Versions: EAP 6.1, EAP 6.2, WFK 2.5  

Summary: The quickstarts demonstrate Java EE 6, RichFaces 4.1, and a few additional technologies from the JBoss stack. They provide small, specific, working examples that can be used as a reference for your own project.

Introduction
------------

These quickstarts run on Red Hat JBoss Enterprise Application Platform 6.2 and WFK 2.5 or later. We recommend using the JBoss EAP ZIP file. This version uses the correct dependencies and ensures you test and compile against your runtime environment. 

Available Quickstarts
---------------------

The list of all currently available quickstarts can be found here: <http://site-jdf.rhcloud.com/quickstarts/get-started/>. The table lists each quickstart name, the technologies it demonstrates, gives a brief description of the quickstart, and the level of experience required to set it up. For more detailed information about a quickstart, click on the quickstart name.

System Requirements
-------------------

The applications these projects produce are designed to be run on Red Hat JBoss Enterprise Application Platform 6.1 or later. 

To run these quickstarts with the provided build scripts, you need the following:

1. Java 1.6, to run JBoss AS and Maven. You can choose from the following:
    * OpenJDK
    * Oracle Java SE
    * Oracle JRockit

2. Maven 3.0.0 or newer, to build and deploy the examples
    * If you have not yet installed Maven, see the [Maven Getting Started Guide](http://maven.apache.org/guides/getting-started/index.html) for details.
    * If you have installed Maven, you can check the version by typing the following in a command prompt:

            mvn --version 

3. The JBoss EAP distribution ZIP.
    * For information on how to install and run JBoss, refer to the product documentation.

4. You can also use [JBoss Developer Studio or Eclipse](#use-jboss-developer-studio-or-eclipse-to-run-the-quickstarts) to run the quickstarts. 



Configure Maven
---------------

The quickstarts in the RichFaces project are designed to use artifacts in Maven Central. There is no need to configure Maven before you build and deploy the quickstarts. 


Run the Quickstarts
-------------------

The root folder of each individual quickstart contains a README file with specific details on how to build and run the example. In most cases you do the following:

* [Start the JBoss server](#start-the-jboss-server)
* [Build and deploy the quickstarts](#build-and-deploy-the-quickstarts)


### Start the JBoss Server

Before you deploy a quickstart, in most cases you need a running JBoss EAP server. To start the JBoss EAP server with the default profile:

1. Open a command prompt and navigate to the root of the JBoss server directory.
2. The following shows the command line to start the JBoss server:

        For Linux:   JBOSS_HOME/bin/standalone.sh
        For Windows: JBOSS_HOME\bin\standalone.bat

           
### Build and Deploy the Quickstarts

See the README file in each individual quickstart folder for specific details and information on how to run and access the example.


