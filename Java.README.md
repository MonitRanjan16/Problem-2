
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int a = sc.nextInt();

        for (int i = 1; i <= a * 2; i += 2) {
            System.out.print(i + " ");
        }

       
    }
}
