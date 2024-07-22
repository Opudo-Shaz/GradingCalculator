
# GradingCalculator
Exam Statistics
The "Exam Statistics" project is a Java console application that allows users to input student marks for multiple subjects. The program then calculates and displays various statistics such as the average mark for each subject, the highest and lowest marks for a specific subject, and the total marks.

Features
Input student marks for multiple subjects
Calculate the average mark for each subject
Determine the highest and lowest marks for a specific subject
Display the total marks for all subjects

Prerequisites
Java Development Kit (JDK) 8 or higher
An Integrated Development Environment (IDE) such as IntelliJ IDEA, Eclipse, or NetBeans

How to Run the Application
Clone the repository or download the project files.
Open the project in your IDE.
Compile and run the ExamStatistics.java file.
Usage
When you run the application, it will prompt you to enter the marks for each student in a comma-separated format.
Enter the marks for the specified number of subjects. If you enter fewer or more marks than required, you will be prompted to re-enter the marks.
After entering the marks for all students, the application will display the calculated statistics.

Example
Input student 1 marks in comma separated format e.g 21,45,23
21,45,23
Marks for student 1 = 21,45,23

Input student 2 marks in comma separated format e.g 21,45,23
34,50,29
Marks for student 2 = 34,50,29

Input student 3 marks in comma separated format e.g 21,45,23
20,40,30
Marks for student 3 = 20,40,30

The average for the first subject is 25.0
The average for the second subject is 45.0
The highest mark for subject 1 is 34
The lowest mark for subject 1 is 20

The main class ExamStatistics contains the following methods:

main(String[] args): The entry point of the application. It prompts the user for input, stores the marks in an ArrayList, and calls the calculateStats method to compute and display the statistics.

calculateStats(ArrayList<int[]> studentMarksList): This method performs statistical operations on the ArrayList of student marks. It calculates the average mark for each subject, the highest and lowest marks for a specific subject, and the total marks.

Method Details
calculateStats(ArrayList<int[]> studentMarksList):
Initializes variables to store the sum, highest mark, lowest mark, and total marks.
Iterates over the ArrayList of student marks.
Calculates the sum, highest mark, and lowest mark for each subject.
Computes the average marks for each subject.
Prints the calculated statistics to the console.
Contribution
Feel free to fork this repository and make contributions. Pull requests are welcome.

License
This project is licensed under the MIT License.

This README provides a comprehensive guide to setting up and using your "Exam Statistics" project. Adjust the instructions and details based on your actual project setup and requirements.






