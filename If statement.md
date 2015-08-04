package com.company;
import java.util.Scanner;
public class Main {

   public static void main(String[] args) {

        Scanner in = new Scanner(System.in);
        int age = 15;

        System.out.println("Type your age");

        int boy = in.nextInt();

        if (age > boy){
            System.out.println("you are too young to drive");

        }else {
           System.out.println("you can drive");
        }






    }
}
