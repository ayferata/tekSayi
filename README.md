# tekSayi
import java.util.Scanner;
public class Main {
    //4 ün katlarını topla. Tek sayı girerse programı bitir.
    public static void main(String[] args) {
            Scanner tursu = new Scanner(System.in);
            int number,sum=0;
                System.out.println("Bir sayı giriniz: ");
                number=tursu.nextInt();
                while(number%2==0){
                    if(number%4==0){
                        sum=sum+number;
                    }
                    System.out.println("Bir sayı giriniz: ");
                    number=tursu.nextInt();
                }
                System.out.println("Toplam: " + sum);
    }
}
