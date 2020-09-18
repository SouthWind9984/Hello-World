# hello-word
This is just one program.
package 第二周练习;

//import java.util.Scanner;

public class 找素数 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int i=0;
		
		for(i=2;i<100;i++) //100以内的素数
		{
			int a=1;
			for(int j=2;j<i;j++)
			{
				if(i%j==0)
				{	
					a=0;
					break;
				}
			}
			if(a==1)
				System.out.printf(i+" ");		
		}
			
	}
}