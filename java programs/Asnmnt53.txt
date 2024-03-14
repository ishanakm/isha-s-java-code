package arraysproject;

import java.util.Scanner;

//swap the numbers with extra variable
public class Asnmnt14 {

	public static void main(String[] args)
	{
       Scanner s1=new Scanner(System.in);
       int num1=s1.nextInt();
       int num2=s1.nextInt();
       int a=num1;
       num1=num2;
       num2=a;
       System.out.println(num1);
       System.out.println(num2);
       
	}

}
