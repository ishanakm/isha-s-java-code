package project3;

import java.util.Date;

//find 10 days before and after time
public class Time {

	public static void main(String[] args) 
	{
   Date d1=new Date();
   Date d2=new Date(d1.getTime());//current time
   System.out.println(d2);
   Date d3=new Date(d1.getTime()+1000*60*60*24*10);//10 days after time
   System.out.println(d3);
   Date d4=new Date(d1.getTime()-1000*60*60*24*10);//10 days before time
   System.out.println(d4);
	}

}
