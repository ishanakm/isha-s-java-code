package arraysproject;

import java.util.Scanner;

//53.factorial of number using for loop with decrement operator and scanner class
public class Asnmnt13 {

	public static void main(String[] args)
	{
		Scanner s1=new Scanner(System.in);
		
  int num=s1.nextInt();
  int fact=1;
    for(int i=num;i>0;i--)
    {
    	//System.out.println(i);
    	fact=fact*i;
    	
    }
    System.out.println(fact);
	}

}
