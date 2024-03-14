package arraysproject;
//check if the string contains space
public class Asnmnt12 {

	public static void main(String[] args) 
	{
      String name="ishana fathima";
      int count=0;
      char name1[]=name.toCharArray();
      for(int i=0;i<name.length();i++)
      {
    	  boolean ansr=Character.isSpaceChar(name1[i]);
    	  if(ansr==true)
    	  {
    		  count++;
    		  System.out.println("space is present");
    	  }
      
      }
      System.out.println("the number of spcae is  "+count);
	}

}
