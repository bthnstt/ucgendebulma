# ucgendebulma
import java.util.Scanner;

public class Giris {
    public static void main(String[] args) {
        //değişkenler
        int a,b;
        double c,u,alan;


        //veriler
        Scanner input= new Scanner(System.in);
        System.out.print("1. kenarı giriniz:");
        a=input.nextInt();
        System.out.print("2. kenarı giriniz:");
        b=input.nextInt();

        c= Math.sqrt((a*a) + (b*b));
        System.out.println("Hipotenüs:" + c);

        u=((a+b+c)/2);
        System.out.println("çevre:"+ u);
        alan=u*(u-a)*(u-b)*(u-c);
        System.out.println("Alanı"+ alan);

    }

}
