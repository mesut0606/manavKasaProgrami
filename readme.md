Manav Kasa Programı
Java ile kullanıcıların manavdan almış oldukları ürünlerin kilogram değerlerine göre toplam tutarını ekrana yazdıran program

import java.util.Scanner;

public class Main {
public static void main(String[] args) {
double armutfiyat = 2.14 , elmafiyat = 3.67, domatesfiyat =1.11, muzfiyat = 0.95, patlıcanfiyat= 5;
double armut, elma, domates, muz, patlıcan;

        Scanner input = new Scanner(System.in);

        System.out.print("Armut Kaç Kilo ? :");
        armut = input.nextDouble();

        System.out.print("Elma Kaç Kilo ? :");
        elma = input.nextDouble();

        System.out.print("Domates Kaç Kilo ? :");
        domates = input.nextDouble();

        System.out.print("Muz Kaç Kilo ? :");
        muz = input.nextDouble();

        System.out.print("Patlıcan Kaç Kilo ? :");
        patlıcan = input.nextDouble();

        double toplam = (armut*armutfiyat) + (elma*elmafiyat) + (domates*domatesfiyat)+
                 (muz*muzfiyat)+(patlıcan*patlıcanfiyat);
        System.out.print("Toplam Tutar :" + toplam +"TL");



    }
}