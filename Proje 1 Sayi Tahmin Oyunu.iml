import java.util.Random;
import java.util.Scanner;

public class Proje1SayiTahminOyunu {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        Random random = new Random();


        int rastgeleSayi = random.nextInt(100) + 1;

        System.out.println("1 ile 100 arasında bir sayı tahmin edin.");

        int tahmin;
        int denemeSayisi = 0;

        do {
            System.out.print("Tahmininiz: ");
            tahmin = scanner.nextInt();
            denemeSayisi++;

            if (tahmin == rastgeleSayi) {
                System.out.println("Tebrikler, " + denemeSayisi + " denemede buldunuz!");
                break;
            } else {
                int fark = Math.abs(rastgeleSayi - tahmin);
                if (fark <= 10) {
                    System.out.println("Yaklaştınız, tekrar deneyin!");
                } else {
                    System.out.println("Uzak, tekrar deneyin!");
                }
            }

        } while (true);

        scanner.close();
    }
}
