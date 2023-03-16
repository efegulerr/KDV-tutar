# KDV-tutar
// patika ödev kdv tutarı ve kdvli fiyat hesaplama

import java.util.Scanner;
public class main {
    public static void main(String[] args) {
int urun;
Scanner inp = new Scanner(System.in);
        System.out.println("ürününüzün fiyatı nedir?");
        urun = inp.nextInt();
    int kdv= (( urun / 100) * 18);
    int kdvp= urun+kdv;
    System.out.println("Ürüne eklenecek kdv tutarı:" + kdv );
    System.out.println("Toplam tutar:" + kdvp);
    }
    
}  
