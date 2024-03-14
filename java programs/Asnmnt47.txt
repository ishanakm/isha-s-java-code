package arraysproject;

import java.util.Scanner;

//sting=isha123
//check which character is alpha and which is numeric
public class Asnmnt6 {

	public static void main(String[] args) 
	{
     System.out.println("enter the string");
     Scanner s1=new Scanner(System.in);
    	String a=s1.next();
    	char b[]=a.toCharArray();
   for(int i=0;i<a.length();i++)
   {
	   boolean ansr=Character.isAlphabetic(b[i]);
	   boolean ansr1=Character.isDigit(b[i]);
	   if(ansr==true)
	   {
		   System.out.println(b[i]+" is alphabetic");
	   }
	  if(ansr1==true)
	   {
		   System.out.println(b[i]+" is numeric");
	   }
   }
    		  
	}

}
