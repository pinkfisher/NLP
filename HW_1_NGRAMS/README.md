author: Selma Wanna
utid: SLW3429
email: slwanna@utexas.edu
phone: 713-305-7864
github: https://github.com/SouLeo/NLP

# Running on command line
1. copy and paste my files into a directory
2. run javac *.java in that directory
3. in order to run the BigramModelBackwards.java, uncomment it's main function (at the bottom) and comment out the BidirectionalBigram.java. RECOMPILE. Use the same commandline inputs: file/corpus path then the training vs testing ratio as in Dr. Mooney's BigramModel.java
4. To run BidirectionalBigram.java, uncomment it's main function (at the bottom) then comment out the main in the BigramModelBackwards.java. RECOMPILE. then use the same commandline inputs: file/corpus path then the training vs testing ratio as in Dr.Mooney's BigramModel.java

This project was constructed through the use of the IntelliJ IDEA IDE. This
README will explain how to build the project using this IDE.

# Basic Set Up for IntelliJ
1. Download all relevant .java files from my hw1 package
2. Open IntelliJ then navigate to File-> New Project-> Next(do not select
   additional libraries)-> Next(do no create project from template)
3. Name your project. (My project name was CS388_HW1)
4. add the package line hw1 to all of my code files
4. Create a package named hw1 under the src directory
5. There should now be a hw1 package under the project name workspace created
   in your home directory: ~/
5. copy all of my files into ~/your_project_name/src/hw1
6. compile! If it doesn't build, call, text, or email me
7. to run with specific command line args, click on edit configurations in the
   top right hand corner of the IDE (right next ot the green play button)

# Running the Backward Model
1. after entering the edit configuration menu, make sure your main class is
   hw1.BigramModelBackwards
2. Program Arguments should be ~/path_to_corpus 0.8 (where 0.8 represents the
   training to testing ratio)
3. Make sure you're using the classpath model to your project workspace
   (CS388_HW1)
4. Apply settings then hit OK
5. Make sure the main function is uncommented in BigramModelBackwards.java and that
   the main function in the BidirectionalBigram.java is commented out
6. Build the project using the green arrow pointing downward
7. Then hit the green button to run the program

# Running the Bidirectional Model
1. after entering the edit configuration menu, make sure your main class is
   hw1.BidirectionalBigram
2. Program Arguments should be ~/path_to_corpus 0.8 (where 0.8 represents the
   training to testing ratio)
3. Make sure you're using the classpath model to your project workspace
   (CS388_HW1)
4. Apply settings then hit OK
5. Make sure the main function is uncommented in BidirectionalBigram.java and that
   the main function in the BigramModelBackwards.java is commented out
6. Build the project using the green arrow pointing downward
7. Then hit the green button to run the program


Again, if you have any problems. Do not hesitate to contact me.
