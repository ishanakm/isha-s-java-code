package arraysproject;

import java.util.Arrays;
import java.util.Scanner;

//anagrams
public class Asnmnt5 {

	public static void main(String[] args)
	{
		Scanner s1=new Scanner(System.in);
		System.out.println("enter the first string");
    String a1=s1.next();
    System.out.println("enter the second string");
    String a2=s1.next();
     if(a1.length()!=a2.length())
     {
    	 System.out.println("its not anagram");
     }
     else
     {
    	 char b1[]=a1.toCharArray();
    	 char b2[]=a2.toCharArray();
    	 Arrays.sort(b1);//sorting the string
    	 Arrays.sort(b2);
    	 Arrays.toString(b1);//to convert into array like[c,h,i,n]
    	 Arrays.toString(b2);//
    	 boolean ansr=Arrays.equals(b1, b2);
    	 if (ansr==true)
    	 {
    		 System.out.println("its an anagram");
    	 }
     }
       }
	}


