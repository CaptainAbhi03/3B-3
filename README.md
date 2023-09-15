import java.util.Scanner;

public class StudentGrade {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Get input for marks in different subjects
        System.out.print("Enter marks for Subject 1: ");
        double subject1Marks = scanner.nextDouble();

        System.out.print("Enter marks for Subject 2: ");
        double subject2Marks = scanner.nextDouble();

        System.out.print("Enter marks for Subject 3: ");
        double subject3Marks = scanner.nextDouble();

        // Calculate the total marks
        double totalMarks = subject1Marks + subject2Marks + subject3Marks;

        // Calculate the percentage
        double percentage = (totalMarks / (3 * 100)) * 100;

        // Determine the grade based on the percentage
        char grade;

        if (percentage >= 90) {
            grade = 'A';
        } else if (percentage >= 80) {
            grade = 'B';
        } else if (percentage >= 70) {
            grade = 'C';
        } else if (percentage >= 60) {
            grade = 'D';
        } else {
            grade = 'F';
        }

        // Display the results
        System.out.println("Total Marks: " + totalMarks);
        System.out.println("Percentage: " + percentage + "%");
        System.out.println("Grade: " + grade);
    }
}
import java.util.Scanner;

public class CalculatePercentageAndGrade {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Get input for marks in different subjects
        System.out.print("Enter marks for Subject 1: ");
        double subject1Marks = scanner.nextDouble();

        System.out.print("Enter marks for Subject 2: ");
        double subject2Marks = scanner.nextDouble();

        System.out.print("Enter marks for Subject 3: ");
        double subject3Marks = scanner.nextDouble();

        // Calculate the total marks
        double totalMarks = subject1Marks + subject2Marks + subject3Marks;

        // Calculate the percentage
        double percentage = (totalMarks / (3 * 100)) * 100;

        // Determine the grade based on the percentage
        char grade;

        if (percentage >= 90) {
            grade = 'A';
        } else if (percentage >= 80) {
            grade = 'B';
        } else if (percentage >= 70) {
            grade = 'C';
        } else if (percentage >= 60) {
            grade = 'D';
        } else {
            grade = 'F';
        }

        // Display the results
        System.out.println("Total Marks: " + totalMarks);
        System.out.println("Percentage: " + percentage + "%");
        System.out.println("Grade: " + grade);
    }
}
