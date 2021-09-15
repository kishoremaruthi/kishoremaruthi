Java Program to find Perimeter of a Rectangle
TEST CASE 1

INPUT
2
6
OUTPUT
16
TEST CASE 2

INPUT
10
15
OUTPUT
50

import java.io.*;
import java.util.Scanner;
public class TestClass {
	 public static void main(String[] args) { 
       int a,b,perimeter;
       Scanner sc=new Scanner(System.in);
       a=sc.nextInt();
       b=sc.nextInt();
       perimeter=2*(a+b);
       System.out.println(perimeter);
		
	}
}
