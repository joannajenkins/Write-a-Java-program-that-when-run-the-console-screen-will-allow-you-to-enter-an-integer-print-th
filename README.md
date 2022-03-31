# Write-a-Java-program-that-when-run-the-console-screen-will-allow-you-to-enter-an-integer-print-th
Write a Java program that, when run, the console screen will allow you to enter an integer, print the screen "This is a positive integer"
import java.util.Scanner;

public class BaiTapJavaCoBan1 {
    public static void main(String[] args)
    {
       int n;
       System.out.println("Input an integer:");
       Scanner sc = new Scanner(System.in);

       n = sc.nextInt();

       if (n >= 0){
          System.out.println("This is a positive integer");
       }
       else {
          System.out.println("This is a negative integer");
       }
    }
}
