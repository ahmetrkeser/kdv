# www.patika.dev
KDV HESAPLAMA:

```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        double urun ;
        Scanner inp = new Scanner(System.in);

        System.out.print("Ürün fiyatını giriniz: ");
        urun = inp.nextInt();

        double kdv = (urun)*0.18;
        System.out.println("ürün kdv değeri : " + kdv);
        double kdvli = (urun+kdv);
        System.out.println("ürün kdv'li değeri : " + kdvli);

    }
}

