import java.util.Scanner;

public class Sum1
{
 public static void main(String args[])
 {
  Scanner sc= new Scanner(System.in);
  System.out.println("Simple Calculator Program");
        System.out.println("1. Addition");
        System.out.println("2. Subtraction");
        System.out.println("3. Multiplication");
        System.out.println("4. Division");

        System.out.print("Enter your choice (1-4): ");
        int choice = sc.nextInt();
		
		System.out.println("Enter the first number:");
		int a= sc.nextInt();
  
		System.out.println("Enter the second number:");
		int b= sc.nextInt();
  
		int sum= a+b;
		int diff= a-b;
		int mul= a*b;
		int div= a/b;
		
		switch (choice)
		{
			
		case 1:
		System.out.println("The sum of two numbers are:"+sum);
		break;
		
		case 2:
		System.out.println("The diff of two numbers are:"+diff);
		break;
		
		case 3:
		System.out.println("The mul of two numbers are:"+mul);
		break;
  
		case 4:
		System.out.println("The div of two numbers are:"+div);
		break;
		}
 }
} 
		
  
