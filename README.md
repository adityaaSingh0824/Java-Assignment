# Java-Assignment1
# Q1. Create a class StudentInfo with a method displayInfo() that prints your name, age, and grade.
import java.util.Scanner;
public class StudentInfo {
    public void displayInfo() {
        String Name = "Aman Sharma";
        int Age = 16;
        String Grade = "10th";
        System.out.println(Name);
        System.out.println(Age);
        System.out.println(Grade);  
    }
    public static void main(String[] args) {
        StudentInfo displayInfo = new StudentInfo();
        displayInfo.displayInfo();
    }
}


# Q2. Create a class Calculator with a method addNumbers() that adds two numbers and prints the result
import java.util.Scanner;
public class StudentInfo {
    public void displayInfo() {
        String Name = "Aman Sharma";
        int Age = 16;
        String Grade = "10th";
        System.out.println("Name: " +Name);
        System.out.println("Age: " +Age);
        System.out.println("Grade: " +Grade);  
    }
    public static void main(String[] args) {
        StudentInfo g = new StudentInfo();
        g.displayInfo();
    }
}
# Q3. Create a class Greeting with a method sayHello() that takes your name as a parameter and prints:
import java.util.Scanner;
public class Greeting {
    public void sayHello() {
        String Name = "Hello,Aditya! Welcoeme to the Java Programming";
        System.out.println(Name); 
    }
    public static void main(String[] args) {
        Greeting g = new Greeting();
        g.sayHello();
    }
}
# Q4. Create a class Circle with a method calculateArea() that calculates and prints the area of a circle.
import java.util.Scanner;
public class Circle {
    public void calculateArea() {
        int radius = 7;
        double Pie = 3.14;
        double area = Pie * radius * radius;
        System.out.println("Area: " + area);
    
    }
    public static void main(String[] args) {
        Circle g = new Circle();
        g.calculateArea();
    }
}
# Q5. Create a class SimpleInterest with a method calculateInterest() that calculates simple interest.
import java.util.Scanner;
public class SimpleInterest {
    public void calculateInterest() {
        double P= 1000;
        double T=2;
        double R=5;
        double SI = (P*T*R)/ 100;
         System.out.println(SI);
    
    }
    public static void main(String[] args) {
        SimpleInterest g = new SimpleInterest();
        g.calculateInterest();
    }
}




