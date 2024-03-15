package exceptionalhandling;

import java.util.InputMismatchException;

public class Asnmnt1 
{

	public static void main(String[] args) 
	{
	try
	{
       int a=1/0;
		System.out.println(a);
	}
	catch(ArithmeticException a1)
	{
		System.out.println("exception ");
	}
	catch(InputMismatchException i1)
	{
		System.out.println("exception ");
	}
	catch(NullPointerException n1)
	{
		System.out.println("exception ");
	}
	catch(ClassCastException c1)
	{
		System.out.println("exception ");
	}
	catch(ArrayIndexOutOfBoundsException a2)
	{
		System.out.println("exception ");
	}
	catch(IllegalArgumentException c2)
	{
		System.out.println("exception ");
		
	}
	finally
	{
		System.out.println("exception handled");
	}

	}

}