# Exercise-18

/*
*Jonathan Saldivar
*ITSE 1302-011
*Exercise 18
*/

import java.util.*;

public class IntegerCounter {

public static void main (String[] args) {

Scanner scan = new Scanner(System.in);
int intInteger = new int(100) + 1;

   System.out.println("Enter a number: ");
   int intNumber = scan.nextInt();
        
    
     while (intNumber != -1 && intNumber >= 0 && intNumber <= 100) {
     intInteger[intNumber]++;
     intNumber = scan.nextInt();
     }
        
       
    for (int index = 0 ;
    index<= 100;
    index++) {
    if (intInteger[index] > 0) {
    System.out.println(index+ " : " + intInteger[index]);
    }
    
    }
    }
}
