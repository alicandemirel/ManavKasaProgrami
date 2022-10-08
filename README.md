//ManavKasaProgrami

import java.util.Scanner;

public class ManavKasa {

    public static void main(String[] args) {

        float armut = 2.14f;
        float elma = 3.67f;
        float domates = 1.11f;
        float muz = 0.95f;
        float patlican = 5.00f;
        float kg, totalAmount=0;

        Scanner input = new Scanner(System.in);

        System.out.print("Armut Kaç Kilo ? :");
        kg = input.nextFloat();
        totalAmount += kg*armut;
        System.out.print("Elma Kaç Kilo ? :");
        kg = input.nextFloat();
        totalAmount += kg*elma;
        System.out.print("Domates Kaç Kilo ? :");
        kg = input.nextFloat();
        totalAmount += kg*domates;
        System.out.print("Muz Kaç Kilo ? :");
        kg = input.nextFloat();
        totalAmount += kg*muz;
        System.out.print("Patlıcan Kaç Kilo ? :");
        kg = input.nextFloat();
        totalAmount += kg*patlican;


        System.out.print("Toplam Tutar: " + totalAmount);

    }
}
