# CS-23.252
[program1 wap to reverse the array](#assignment1)
##assignment1
```
import java.util.Scanner;
public class Revarray {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        Arraytest t1=new Arraytest();
        t1.input();
       
        t1.outarrorg();
         t1.rev();
        t1.outarrrev();
    }
    
}
class Arraytest{
    int x[];
    int rev[];
    
void input(){
    x=new int [5];
    Scanner sc = new Scanner(System.in);
    for(int i=0;i<5;i++){
        System.out.println("Enter array elements");
         x[i]=sc.nextInt();
    }
}
void outarrorg(){
    for(int i=0;i<5;i++)
    {
        System.out.println("The array is"+x[i]);
    }
}
void rev(){
    rev=new int[5];
    for(int i=4;i>=0;i--){
        
        
    }
}
void outarrrev(){
    for(int i=4;i>=0;i--){
        System.out.println("the reverse array is"+x[i]);
        
      
    
    }
        
}

}
```
<img width="557" height="448" alt="image" src="https://github.com/user-attachments/assets/afcdb4f5-0d02-496c-a104-44c604e2ecfb" />

[program2 to input/ output methods](#assignment2)
##assignment2 
```
import java.util.Scanner;
public class Test {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
           
        Test1 t1=new Test1();
t1.input(5,9);
t1.output();
    }
    
}
class Test1
{
    int x;
    int y;
void input(int a,int b)
{
    x=a;
    y=b;
}
void output()
{
    System.out.println(x);
    System.out.println(y);
}
}
```
<img width="338" height="98" alt="image" src="https://github.com/user-attachments/assets/cda85ccc-bc5b-4f8c-bb0a-a7d42bf868e1" />


[program3 wap to take input from user and dispaly it](#assignment3)
##assignment3
```
import java.util.Scanner;

public class Test2 {

    /**
     * Main method - program execution starts from here
     */
    public static void main(String[] args) {
        
        // Creating object of Test3 class
        Test3 t1 = new Test3();
        
        // Calling input method to take values from user
        t1.input();
        
        // Calling output method to display values
        t1.output();
    }
}

/**
 * Test3 class handles input and output operations
 */
class Test3 {

    // Declaring variables
    int x;
    int y;

    /**
     * Method to take input from user
     */
    void input() {
        // Creating Scanner object for user input
        Scanner sc = new Scanner(System.in);

        // Asking user to enter value of x
        System.out.println("Enter value of x");
        x = sc.nextInt();

        // Asking user to enter value of y
        System.out.println("Enter value of y");
        y = sc.nextInt();
    }

    /**
     * Method to display the entered values
     */
    void output() {

        // Printing value of x
        System.out.println("Value of x: " + x);

        // Printing value of y
        System.out.println("Value of y: " + y);
    }
}

```
<img width="361" height="132" alt="image" src="https://github.com/user-attachments/assets/cb0a8271-bf0a-408b-bf9c-2e1370682f9a" />

[program4 wap to input numbers , multiply it , and display the results](#assignment4)
##assignment4
```
import java.util.Scanner;

public class Test4 {

    // Main method - starting point of the program
    public static void main(String[] args) {
        
        // Creating object of Test5 class
        Test5 t1 = new Test5();
        
        // Calling methods for input, processing, and output
        t1.input();
        t1.proc();
        t1.output();
    }
}

// Class to handle input, processing and output
class Test5 {

    int x, y;   // Variables to store numbers

    // Method to take input from user
    void input() {
        Scanner sc = new Scanner(System.in);
        
        System.out.println("Enter value of x");
        x = sc.nextInt();
        
        System.out.println("Enter value of y");
        y = sc.nextInt();
    }

    // Method to double the values
    void proc() {
        x = 2 * x;
        y = 2 * y;
    }

    // Method to display the result
    void output() {
        System.out.println("Value of x after doubling: " + x);
        System.out.println("Value of y after doubling: " + y);
    }
}
```
<img width="313" height="151" alt="image" src="https://github.com/user-attachments/assets/3089b2cd-c983-46c9-8ede-fb58bbd3cf45" />









