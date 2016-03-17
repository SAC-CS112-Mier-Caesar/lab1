# lab3a

import java.util.Scanner;

public class lab3a {

public static void main(String args[]){

Scanner input = new Scanner(System.in); int userNum; int computerNum;

computerNum = 1 + (int) ( Math.random() * 10 );

System.out.println("Enter a number: "); userNum = input.nextInt();

if (userNum > computerNum || userNum < computerNum){ 
  System.out.println("Your number is either bigger or smaller than the computer number"); 
  }
else { 
System.out.println("Your number is correct!"); 
}

} }
