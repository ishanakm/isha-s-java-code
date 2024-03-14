package arraysproject;

import java.util.Arrays;

//43.array with double and boolean data type 
public class asnmnt1
{
   public static void main(String[] args) 
	{
      double number[]=new double[3];
      number[0]=2.16;
      number[1]=2.32;
      number[2]=2.3;
      Arrays.sort(number);
      System.out.println(Arrays.toString(number));
      
	boolean a[]=new boolean[3];
	a[0]=true;
	a[1]=false;
	a[2]=true;
	System.out.println(Arrays.toString(a));
	
	}

}
