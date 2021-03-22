This is Part 3 of the project MP1.

Instructions to run code:

1. Compile the files Example.java and TestSootLogging.java to ensure there are no syntax or compile time errors. 
2. Run the code in TestSootLogging.java order to get the desired output. 
3. Compile the files Log.java, TestSootLoggingHeap.java and HelloThread.java to ensure there are no syntax or compile time errors. 
4. After this, for the logging part, run Log.java, TestSootLoggingHeap.java and HelloThread.java.

Here we have two files, Example.java containing all the examples methods (Ex. abstract class Animal) in order for the user to see all the results. 
We have updated this file with 2 lines of code System.out.println("calling selectAnimal"); and System.out.println("calling saySomething"); 
for simplicity and visibility. Whenever I ran the code in TestSootLogging.java the first time, it created a file Example.jimple and a folder to go with that
called sootOutput. After this task I had commented out the line Options.v().set_output_format(1); and once I ran it after this was done, all the output files had
turned into .class files. From there I ran the modified Example.java class and I came across the output: 
calling selectAnimal 
calling saySomething
purr
