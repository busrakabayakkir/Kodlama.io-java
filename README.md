# Kodlama.io-java
## Asal Sayı Bulma Algoritması

public class Main {
    public static void main(String[] args) {

        int sayi;
        sayi=14;
        boolean kontrol = true;

       for(int i=1;i<sayi;i++){

           if(sayi%i==0){
               if (i!=1)
               {
                   System.out.println("Sayi asal degil");
                   kontrol = false;
                   break;
               }
           }
       }

       if (kontrol==true)
       {
           System.out.println("Sayi asal");
       }
---

## Sesli Harfin Kalın mı İnce mi? Algoritması


public class Main {
    public static void main(String[] args) {
        char harf = 'a';
        String mesajKalınSesli= "Kalın Sesli Harf";
        String mesajInceSesli= "İnce Sesli Harf";

        switch(harf){
            case  'a' :
            case  'ı' :
            case  'o' :
            case  'u' :
                System.out.print(mesajKalınSesli);
                break;
            default: System.out.print(mesajInceSesli);

---

## Mükemmel Sayı Bulma Algoritması


public class Main {
    public static void main(String[] args) {

        int sorgulananSayi,sayininBolenToplami;
        sorgulananSayi = 15;
        sayininBolenToplami=0;

        for(int i=0;i<sorgulananSayi;i++){
            if(sorgulananSayi%i==0){
                sayininBolenToplami=sayininBolenToplami+i;
            }
        }
        if(sayininBolenToplami=sorgulananSayi){
            System.out.print("Mükemmel sayıyı buldunuz");
        }
        else{
            System.out.print("Mükemmel sayıyı bulamadınız");
        }

    }
}

---
