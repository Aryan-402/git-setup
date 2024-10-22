

import java.util.Scanner;

public class ModulusCalculator {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
// i  changed this line 
        System.out.print("Enter the first number: ");
        int num1 = scanner.nextInt();

        System.out.print("Enter the second number: ");
        int num2 = scanner.nextInt();

        int modulus = num1 % num2;

        System.out.println("The modulus of " + num1 + " and " + num2 + " is: " + modulus);
    }
}
