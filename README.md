# Batch-Processor
This project will have teams building a batch language processor. The scope of this effort is to build a tool that parses and executes a batch files containing a number of commands. A batch file, or batch, contains one or more commands that are executed sequentially. Each command executed by our batch processor will be executed as a process and communicate (pass information) using files or pipes. 

Files included:

folder  :executablejar_team7 has mybatchprocessor_team7.jar file along with work directory.
Zip file : TEAM7_TKPM_OSProject1.zip which contains the source code.

Steps to Run:

1. open command prompt
2. go to the directory where .jar file is located
3. java -jar mybatchprocessor.jar work/batch1.xml 
     This gives output of dirout.txt.
4. java -jar mybatchprocessor.jar work/batch2.xml 
     This gives output of sortedwords.txt and reversesort.txt
5. java -jar mybatchprocessor.jar work/batch3.xml 
