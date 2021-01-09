# 210109
package basic;

import java.util.Scanner;

public class CodeUp1035 {

	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		String a=sc.next();
		System.out.printf("%s\n",a);
		int temp=Integer.parseInt(a,16);
		System.out.printf("%d\n",temp);
		String n=Integer.toOctalString(temp);
		System.out.printf("%s",n);
		
	}

}
