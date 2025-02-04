# oopsjava
I have make a programe to make student data type function in java using oops.
package oops;

public class StudentClass {
    // create new data type
    String name;
    int rno;
    double percent;

    // Method that accepts a StudentClass object and prints its name
    public static void fun(StudentClass x) {
        System.out.println(x.name);
    }

    public static void main(String[] args) {
        // Create an instance of StudentClass
        StudentClass x = new StudentClass();
        x.name = "Tisha";
        x.rno = 78;
        x.percent = 97.8;
        
        // Call the fun method
        fun(x);
    }
}


