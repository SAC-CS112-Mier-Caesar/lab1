# lab2

import java.util.Scanner;

public class lab1 { 
  
  public static void main(String args[]){

    Scanner input = new Scanner(System.in);
    int userNum;
    int computerNum;
    
    computerNum = 1 + (int) ( Math.random() * 10 );
    
    System.out.println("Enter a number: ");
    userNum = input.nextInt();
    
  if (userNum > computerNum)
    System.out.println("Your number is too big");
    
  else if (userNum < computerNum)
    System.out.println("Your number is too small");
    
  else (userNum == computerNum)
    System.out.println("Your number is correct!");

    
}
}
