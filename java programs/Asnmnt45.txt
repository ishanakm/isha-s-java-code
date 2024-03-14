package arraysproject;

import java.util.Arrays;
import java.util.Scanner;

//45. write size of an array from scanner class
public class Asnmnt3 {

	public static void main(String[] args)
	{
		 System.out.println("enter the size of array");
      Scanner s1=new Scanner(System.in);
	int a[]=new int[s1.nextInt()];
     for(int i=0;i<a.length;i++)
     {
    	 System.out.println("enter the value of array");
    	 a[i]=s1.nextInt();
     }
     Arrays.sort(a);
     System.out.println(Arrays.toString(a));
	}

}
