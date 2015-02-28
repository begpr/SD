This example demonstrates the use of sockets in the Java platform.

The server opens a socket and blocks waiting for connections.

To compile:
javac *.java

To run:
java example.Socketserver 8000
    (portNumber)


Using Maven:
-----------

To compile:
mvn compile

To run:
mvn exec:java -Dexec.args="8000"

To generate a launch script, for Windows and Unix:
mvn package appassembler:assemble

To run:
target\appassembler\bin\java-sockets-server 8000


To configure the project in Eclipse:
-----------------------------------

If Eclipse files (.project, .classpath) exist:
    'File', 'Import...', 'General'-'Existing Projects into Workspace'
    'Select root directory' and 'Browse' to the project base folder.
    Check if everything is OK and 'Finish'.

If Eclipse files do not exist:
    'File', 'Import...', 'Maven'-'Existing Maven Projects'.
    'Browse' to the project base folder.
    Check that the desired POM is selected and 'Finish'.

To run:
    Select the main class and click 'Run' (the green play button).
    Specify arguments using 'Run Configurations'

--
2015-02-19
Miguel.Pardal@tecnico.ulisboa.pt, naercio.magaia@tecnico.ulisboa.pt
