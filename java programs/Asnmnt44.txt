package arraysproject;
//44
import java.util.Arrays;
//add value at the runtime
import java.util.Scanner;

public class Asnmnt2 {

	public static void main(String[] args)
	{
       int num[]=new int[3];
       Scanner s1=new Scanner(System.in);
       for(int i=0;i<num.length;i++)
       {
    	   System.out.println("enter the value");
    	   num[i]=s1.nextInt();
       }
       Arrays.sort(num);
        System.out.println(Arrays.toString(num));
	}

}
