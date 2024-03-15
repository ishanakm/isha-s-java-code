package arraysproject;
//print 1 to 1000 if divisible by 3 print sun if divisible by 5 print moon if divisible by both then print sun and moon
public class Asnmnt16 {

	public static void main(String[] args)
	{
      for(int i=1;i<=1000;i++)
      {
    	 // System.out.println(i);
    	  if(i%3==0)
    	  {
    		  System.out.println(" sun");
    		  
    	  }
    	  if(i%5==0)
    	  {
    		  System.out.println( " moon");
    	  }
    	  if(i%3==0&&i%5==0)
    	  {
    		  System.out.println(" sun and moon");
    	  }
      }
	}

}
