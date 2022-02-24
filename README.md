Chinese Zodiac Calculator

/* Çin Zodyağı nasıl hesaplanır?

Çin zodyağı hesaplanırken kişinin doğum yılının 12 ile bölümünde kalana göre bulunur.

Doğum Tarihi %12 = 0 ➜ Maymun

Doğum Tarihi %12 = 1 ➜ Horoz

Doğum Tarihi %12 = 2 ➜ Köpek
Doğum Tarihi %12 = 3 ➜ Domuz

Doğum Tarihi %12 = 4 ➜ Fare

Doğum Tarihi %12 = 5 ➜ Öküz

Doğum Tarihi %12 = 6 ➜ Kaplan

Doğum Tarihi %12 = 7 ➜ Tavşan

Doğum Tarihi %12 = 8 ➜ Ejderha

Doğum Tarihi %12 = 9 ➜ Yılan

Doğum Tarihi %12 = 10 ➜ At

Doğum Tarihi %12 = 11 ➜ Koyun
*/

import java.util.Scanner;

public class ODEV15 {
    public static void main(String[] args) {

        int year,chineseZodiac;

        Scanner input = new Scanner(System.in);
        System.out.println("Enter your year of birth: ");
        year = input.nextInt();

        chineseZodiac = year % 12;

        switch(chineseZodiac) {

            case 0:
                System.out.println("Monkey"); // Doğduğun yılın 12'ye böümünden kalan 0 ise Çin Zodyağı burcun Maymun.
                break;
            case 1:
                System.out.println("cockerel"); // Doğduğun yılın 12'ye böümünden kalan 1 ise Çin Zodyağı burcun Horoz.
                break;
            case 2:
                System.out.println("Dog"); // Doğduğun yılın 12'ye böümünden kalan 2 ise Çin Zodyağı burcun Köpek.
                break;
            case 3:
                System.out.println("Pig"); // Doğduğun yılın 12'ye böümünden kalan 3 ise Çin Zodyağı burcun Domuz.
                break;
            case 4:
                System.out.println("Mouse"); // Doğduğun yılın 12'ye böümünden kalan 4 ise Çin Zidyoğı burcun Fare.
                break;
            case 5:
                System.out.println("Steer"); // Doğduğun yılın 12'ye böümünden kalan 5 ise Çin Zidyoğı burcun Öküz.
                break;
            case 6:
                System.out.println("Tiger"); // Doğduğun yılın 12'ye böümünden kalan 6 ise Çin Zidyoğı burcun Kaplan.
                break;
            case 7:
                System.out.println("Rabbit"); // Doğduğun yılın 12'ye böümünden kalan 7 ise Çin Zidyoğı burcun Tavşan.
                break;
            case 8:
                System.out.println("Dragon"); // Doğduğun yılın 12'ye böümünden kalan 8 ise Çin Zidyoğı burcun Ejderha.
                break;
            case 9:
                System.out.println("Snake"); // Doğduğun yılın 12'ye böümünden kalan 9 ise Çin Zidyoğı burcun Yılan.
                break;
            case 10:
                System.out.println("Horse"); // Doğduğun yılın 12'ye böümünden kalan 10 ise Çin Zidyoğı burcun At.
                break;
            case 11:
                System.out.println("Sheep"); // Doğduğun yılın 12'ye böümünden kalan 11 ise Çin Zidyoğı burcun Koyun.
        }

    }
}
