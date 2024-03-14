package arraysproject;
//string =mango
//calculate how many are alpha & how many are numeric
public class Asnmnt7 {

	public static void main(String[] args)
	{
      String a="mango";
       char a1[]=a.toCharArray();
       int alpha_count=0;
       int number_count=0;
    		  for(int i=0;i<a.length();i++)
    		  {
    			  boolean b=Character.isAlphabetic(a1[i]);
    			  if(b==true)
    			  {
    				 alpha_count++; 
    			  }
    			  
    		 boolean c= Character.isDigit(a1[i]);
    		 if(c==true)
    			  {
    			 number_count++;
    				 }
    		  }
    		  System.out.println("the count of  numeric is "+ number_count);
    		  System.out.println("the count of  alphabet is "+ alpha_count);
	}

}
