package project3;

public class palindrom {

	public static void main(String[] args) {
String a="dad";
String reverse="";
for(int i=a.length()-1;i>=0;i--)
{
	char ansr=a.charAt(i);
	reverse=reverse+ansr;
}
System.out.println(reverse);
   boolean e=a.equals(reverse);
   if(e==true)
   {
	   System.out.println("its palindrom");
   }
   else
   {
	   System.out.println("its not palindrom"); 
   }
	}

}
