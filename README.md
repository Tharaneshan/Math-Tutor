# Math-Tutor
Java code where it generates a random equation with 2 different numbers from 1 to 10 depending on what equation you choose. 

    import java.lang.Math;
    import java.util.Scanner;
    public class MathTutor {
      public static void main(String[] args) {
        int operator;
        Scanner input = new Scanner(System.in);

        System.out.println("Enter a operator(1 = +, 2 = -, 3 = *, 4 = /): ");
        operator = input.nextInt();
        input.close();

        switch (operator) {
          case 1: System.out.println("What is: " + (int)(10 * Math.random() + 1) + "+" + (int)(10 * Math.random() + 1) + "?");break;
          case 2: System.out.println("What is: " + (int)(10 * Math.random() + 1) + "-" + (int)(10 * Math.random() + 1) + "?");break;
          case 3: System.out.println("What is: " + (int)(10 * Math.random() + 1) + "*" + (int)(10 * Math.random() + 1) + "?");break;
          case 4: System.out.println("What is: " + (int)(10 * Math.random() + 1) + "/" + (int)(10 * Math.random() + 1) + "?");break;

      }
    }
    }
