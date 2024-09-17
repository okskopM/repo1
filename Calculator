package com.itproger;

import java.util.Scanner;

class Main {
    
    public  static void main(String [] args){
        Scanner scan = new Scanner(System.in);
        System.out.print("Enter number 1: ");
      int a = scan.nextInt();

        System.out.print("Enter number 2: ");
        int b = scan.nextInt();

        System.out.print("Enter math sym: ");
        scan.nextLine();
        char math = scan.nextLine().charAt(0);

        int res = 0;
        switch (math){
          case '+':
              res = a + b;
              System.out.println("Res: " + res);
              break;

            case '-':
                res = a - b;
                System.out.println("Res: " + res);
                break;

            case '*':
                res = a * b;
                System.out.println("Res: " + res);
                break;

            case '/':
                if( b == 0 ) System.out.print("Error");
                else {
                    res = a / b;
                    System.out.println("Res: " + res);
                }
                break;
            default:
                System.out.println("Error");




      }

    }
