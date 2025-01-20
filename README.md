# Read-and-print-
Read and Print

import java.util.Scanner;

public class ReadAndPrint {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter a message: ");
        String message = sc.nextLine();
        System.out.println("You entered: " + message);
    }
}

Output

Enter a message: Hello, World!  
You entered: Hello, World!
