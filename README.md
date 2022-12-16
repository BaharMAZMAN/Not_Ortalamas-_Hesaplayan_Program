# Not_Ortalamas-_Hesaplayan_Program
import java.util.Scanner;
public class Baslangic {
    public static void main(String[] args) {

        // Değişkenleri oluştur.
        int mat, fizik, kimya, turkce, tarih, muzik;

        // Scanner sınıfımızı tanımladık.
        Scanner inp = new Scanner(System.in);

        // Kullanıcıdan değerleri al.
        System.out.print("mat notunu giriniz:");
        mat = inp.nextInt();

        System.out.print("fizik notunu giriniz:");
        fizik = inp.nextInt();

        System.out.print("kimya notunu giriniz:");
        kimya = inp.nextInt();

        System.out.print("turkce notunu giriniz:");
        turkce = inp.nextInt();

        System.out.print("tarih notunu giriniz:");
        tarih = inp.nextInt();

        System.out.print("muzik notunu giriniz:");
        muzik = inp.nextInt();

        int toplam=(mat + fizik + kimya + turkce + tarih + muzik);
        double sonuc=toplam/6.0;
        System.out.println("Ortalamanız :"+sonuc);

        var o = sonuc > 60 ? "Geçti" : "Kaldı";
        System.out.println(o);
