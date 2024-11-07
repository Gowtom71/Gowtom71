/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package javaapplication4;

/**
 *
 * @author G0wtom
 */
public class JavaApplication4 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        
        //Java Arithmatic operator
        
         int num = 5;
         num += 5;
         int num1 = 5;
         num1 -= 5;
         int num2 = 5;
         num2 *= 5;
         int num3 = 5;
         num3 /= 5; 
         int num4 = 5;
         num4 &= 5;
         int num5 = 5;
         num5 %= 5;
         int num6 = 5; 
         num6 ^= 5; 
         int num7 = 5;
         num7 >>= 5;
         int num8 = 5;
         num8 <<= 5;
         
         //Java Sring
         
         String text = "I am learning Java \"mobile app\" developement";
         String text1 = " Becouse I want to be a \"mobile app\" developer";
         String text2 = "Now it\'s my turn";
         
         //Math class
         
         double rand = Math.random();
        
         System.out.println(num);
         System.out.println(num1);
         System.out.println(num2);
         System.out.println(num3);
         System.out.println(num4);
         System.out.println(num5);
         System.out.println(num6);
         System.out.println(num7);
         System.out.println(num8);
         System.out.println(text);
         System.out.println(text1);
         System.out.println(text2);
         System.out.println(text.length());
         System.out.println(text.indexOf("java"));
         System.out.println(text.toUpperCase());
         System.out.println(text.toLowerCase());
         System.out.println(text + " "+ text1);
         System.out.println(text.concat(text1));
         System.out.println(Math.max (10,15));
         System.out.println(Math.min (10,15));
         System.out.println(Math.sqrt (64));
         System.out.println(Math.abs(-20));
         System.out.println(Math.min(-10, 10));
         System.out.println("10:" + rand);
         System.out.println(Math.random()*100);
         
         //Java Booleans java if, else
         int x = 10;
         int y = 5; 
         System.out.println(x>y);
         System.out.println(x<y);
         
         int number = 3;
                 if (number > 5){
                     System.out.println(number+" 5 is grater than 3 ");
                 }
                 int numb = 2;
                 if (numb>2){
                     System.out.println("numb is grater than 2");   
                 } else  {
                         System.out.println((numb>=2)?"numb is grater than or equal 2" : "numb is less than 2");
                         }
                 int number1 = 5;
                 if (10 > 5) {
                     System.out.println("10 is grater than 5");
                 }
                 
                 int time = 20;
                 if (time < 18) {
                     System.out.println("Good day");
                 } else {
                     System.out.println("Good evening");
                 }
                 int Mark = 33;
                 if (Mark < 35 ) {
                     System.out.println("Pass");
                 } else {
                     System.out.println("Fail");
                 }
                 int Result = 80;
                 if (Result < 79) {
                     System.out.println("A+");
                 } else {
                     System.out.println("A-");
                 }
                 int wish = 7 ;
                 if ( wish % 2 == 0){ 
                     System.out.println(wish + " is even");
                 }else {
                     System.out.println(wish + " odd");
                 }
                 int age = 18;
                 if (age < 20) {
                     System.out.println("Adult");
                 }else {
                     System.out.println("Child");
                 }
                 System.out.println("End");
                 
                 
         
    }
    
}

