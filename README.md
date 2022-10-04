# Kodlama.io-java

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
