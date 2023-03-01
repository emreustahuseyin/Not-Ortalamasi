# Not-Ortalamasi

        import java.util.Scanner;

       public class DersOrnek {

    public static void main(String[] args) {
        // Degiskenleri olustur
        int mat, fizik, kimya, turkce, tarih, muzik;

                //Scanner sınıfımızı tamamladık
        Scanner inp = new Scanner(System.in);

        // Kullanıcıdan değerleri al
        System.out.print("Matematik Notunuz : ");
        mat = inp.nextInt();

        System.out.print("Fizik Notunuz : ");
        fizik = inp.nextInt();

        System.out.print("Kimya Notunuz : ");
        kimya = inp.nextInt();

        System.out.print("Turkce Notunuz : ");
        turkce = inp.nextInt();

        System.out.print("Tarih Notunuz : ");
        tarih = inp.nextInt();

        System.out.print("Muzik Notunuz : ");
        muzik = inp.nextInt();

        double toplam = (mat+fizik+kimya+turkce+tarih+muzik);
        double sonuc= toplam/6.0;
                System.out.print("Ortalamaniz : " + sonuc);


                String str = (sonuc >= 60) ? " Sinifi Basari İle Gectiniz" : " Sinif Tekrari Yapacaksiniz";
                System.out.println(str);

             }
           }
