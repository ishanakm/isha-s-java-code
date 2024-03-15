package different_keywords;
//area of circle use pi from math pi.and radius from math.randomin the for loop for 10 times
public class Area_ofcircle {

	public static void main(String[] args)
	{
     double pi=Math.PI;
    for(int i=0;i<+10;i++)
    {
        double radius=Math.random();
    double	area=pi*radius*radius;
    	System.out.println(area);
    }
	}

}
