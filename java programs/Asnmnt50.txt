package arraysproject;

import java.util.Arrays;

//copy the value of 1 array into another array using iteration
public class Asnmnt11 {

	public static void main(String[] args)
	{
       int a[]=new int[4];
       a[0]=5;
       a[1]=65;
       a[2]=53;
       a[3]=15;
       
       int b[]=new int[a.length];
       for(int i=0;i<a.length;i++)
       {
    	  b[i]= a[i];
       }
       Arrays.sort(a);
       Arrays.sort(b);
       System.out.println(Arrays.toString(a));
       System.out.println(Arrays.toString(b));
	}

}
