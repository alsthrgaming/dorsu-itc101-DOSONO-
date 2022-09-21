import java.util.Scanner;
 
public class Assignment2 {
 
 public static void main(String[] args) {
  Scanner in = new Scanner(System.in);
   
  System.out.print("Input first number: ");
  int num1 =in.nextInt ();
   

  System.out.print("Input second number: ");
  int num2 =in.nextInt ();
    
    {
  System.out.print("The sum of the two numbers is: ");
     System.out.println(num2 + " = " + (num1 + num2));
    
  System.out.print("The difference of the two numbers is: ") ;      
    System.out.println((num1 - num2));
  
  System.out.print("The product of the two numbers is: ");
     System.out.println(" = " + (num1 * num2));
  
  System.out.print("The quotient of the two numbers is: ");
  System.out.println(" = " + (num1 / num2));

    }

 }
 
}
