# Palindrome

package programs;

import java.util.Scanner;

public class palindrome {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		System.out.println("Enter The Number :");
		Scanner sc = new Scanner(System.in);
		int num1 = sc.nextInt();
		int r,sum = 0;
		int num = num1;
		while(num>0)
			
		{
			r= num%10;
			sum = (sum*10)+r;
			num=num/10;
			
			
			
			
		}
		
		System.out.println("The Given Number Is " +num1);
		if(sum == num1)
			
			System.out.println("The Number Is Palindrome" );
		
		else
			
			System.out.println("The Number Is Not a Palindrome");
		
		
		
		
		
	}

}
