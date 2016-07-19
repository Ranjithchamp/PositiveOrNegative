# PositiveOrNegative
import java.util.Scanner;

public class PostiveOrNegative {
	public static void main(String []arg)
	{
		Scanner get=new Scanner(System.in);
		int input=get.nextInt();
		if(input<0)
		{
			System.out.println("the number "+input+" is Negative");
		}
		else if(input>0)
		{
			System.out.println("the number "+input+" is Positive");
		}
		else
		{
			System.out.println("the number "+input+" is Zero");
		}
	}

}
