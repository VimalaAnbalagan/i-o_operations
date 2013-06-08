i-o_operations
==============

Input and output operation

import java.io.*;
class README
{
  public static void main(String args[])throws IOException
	{
		int a,b,c;
		String x;
		BufferedReader buf = new BufferedReader(new InputStreamReader(System.in));

		System.out.println("\n Enter the values of a and b");	
		System.out.println("Enter a value");
		x = buf.readLine();
		a = Integer.parseInt(x);
		System.out.println("Enter b value");
		x = buf.readLine();
		b = Integer.parseInt(x);
		System.out.println("a and b : "+a+ "and" +b);
		c = a+b;
		System.out.println("Addition of two numbers:"+c);
	}
}
