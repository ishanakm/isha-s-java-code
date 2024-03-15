package project4;

public class narrowing1 {

	public static void main(String[] args) 
	{
        double a=5.3;
        int a1=(int) a; //narrowing-should be done explicitly
        System.out.println(a1);
        
        double pi=3.14;
        int newpi=(int) pi;
        System.out.println(newpi);
	}

}
