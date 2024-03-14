package arraysproject;
//"sky is 441 !@#" find out no of special character we have

public class Asnmnt8 {

	public static void main(String[] args)
	{
     String a="sky is 441 !@#";
     char a1[]=a.toCharArray();
     int count=0;
     int didgit_count=0;
     int space_count=0;
     for(int i=0;i<a.length();i++) 
     {
    	 boolean ansr=Character.isAlphabetic(a1[i]);
    	 if(ansr==true)
    	 {
    		 count++;
    	 }
    	 boolean ansr1=Character.isDigit(a1[i]);
    	 if(ansr1==true)
    	 {
    		 didgit_count++;
    	 }
    	 boolean ansr2=Character.isSpaceChar(a1[i]);
    	 if(ansr2==true)
    	 {
    		 space_count++;
    	 }
     }
     int sc_count=a.length()-(didgit_count+count+space_count);
	 System.out.println("the count of numbers is "+didgit_count);
     System.out.println("the count of alphabet is "+count);
     System.out.println("the count of space is "+space_count);
	  System.out.println("the count of specail charecter is "+sc_count);
	}

}
