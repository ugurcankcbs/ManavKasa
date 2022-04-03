import java.util.Scanner;

public class Manav {
    public static void main(String[] args){
        double elma, kelma=3.67, armut, karmut=2.14, domat, kdomat=1.11, muz, kmuz=0.95, patlican, kpatlican=5.00;
        Scanner input = new Scanner(System.in);
        System.out.println("Elma kaç kg: ");
        elma = input.nextDouble();
        double elmaucret = elma * kelma;

        System.out.println("Elma için ödenecek tutar: " + elmaucret + "TL");


        System.out.println("Armut kaç kg: ");
        armut = input.nextDouble();
        double armutucret = armut * karmut;

        System.out.println("Domates için ödenecek tutar: " + armutucret + "TL");


        System.out.println("Domates kaç kg: ");
        domat = input.nextDouble();
        double domatucret = domat * kdomat;

        System.out.println("Domates için ödenecek tutar: " + domatucret + "TL");


        System.out.println("Muz kaç kg: ");
        muz = input.nextDouble();
        double muzucret = muz * kmuz;

        System.out.println("Muz için ödenecek tutar: " + muzucret + "TL");


        System.out.println("Patlıcan kaç kg: ");
        patlican = input.nextDouble();
        double patlicanucret = patlican * kpatlican;

        System.out.println("Patlıcan için ödenecek tutar: " + patlicanucret + "TL");

        double total = patlicanucret + muzucret + elmaucret + armutucret + domatucret;
        System.out.println("Toplam Tutar: " + total);
    }
}
