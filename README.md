import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int n;
        System.out.println("Hesaplanacak faktoriyel sayısı : ");
        Scanner input = new Scanner(System.in);

        n = input.nextInt();
        int total = 1;

        for(int i = 1; i <= n; i++)
        {
            total = total * i;
        }
        System.out.println(n + " : Faktoriyel = "  + total);
    }


}
