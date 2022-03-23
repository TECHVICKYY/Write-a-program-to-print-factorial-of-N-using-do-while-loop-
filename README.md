# Write-a-program-to-print-factorial-of-N-using-do-while-loop.
import java.util.*;
	import java.util.Scanner;
public class A1_Ex7 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int fact=1, i=1;
		 System.out.println("Enter the number :");
		 Scanner sc = new Scanner(System.in);
		 int num = sc.nextInt();
		 
		 do {
		 fact=fact*i;
		 i++;
		 }while(i<=num);
		 System.out.println("Factorial of "+num+" is "+ fact); 
		}
	}
