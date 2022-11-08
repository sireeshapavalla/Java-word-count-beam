######  1.Java-word-count-beam
[jdk installation Link](https://www.oracle.com/java/technologies/downloads/#jdk19-windows)
[Apache maven](https://maven.apache.org/download.cgi)
###### 2. Maven creates a new project in the word-count-beam directory.
##### 3. cd .\word-count-beam
##### 4. List the example pipelines:dir .\src\main\java\org\apache\beam\examples
##### 5. In the word-count-beam directory, create a file called sample.txt.
###### 6. For Windows PowerShell:mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount `-D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner
###### 7. View the output content in a Unix shell:more counts*
