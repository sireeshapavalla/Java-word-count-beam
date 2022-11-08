### Java-word-count-beam
[jdk installation Link](https://www.oracle.com/java/technologies/downloads/#jdk19-windows)
[Apache maven](https://maven.apache.org/download.cgi)
###Maven creates a new project in the word-count-beam directory.
###cd .\word-count-beam
###List the example pipelines:dir .\src\main\java\org\apache\beam\examples
###In the word-count-beam directory, create a file called sample.txt.
###For Windows PowerShell:mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount `-D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner
###View the output content in a Unix shell:more counts*
