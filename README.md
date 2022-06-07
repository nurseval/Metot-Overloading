# Metot-Overloading
Metot Overloading ve Out Parametre Kullanımı




namespace metotoverloading
{


        class Program
        {
            static int ortalama(int sayi1, int sayi2)
            {
                int sonuc = (sayi1 + sayi2) / 2;
                return sonuc;
            }

            static int ortalama(int sayi1, int sayi2, int sayi3)
            {
                int sonuc = (sayi1 + sayi2 + sayi3) / 2;
                return sonuc;
            }
             static void Main(string[] args)
            {
                Console.WriteLine(ortalama(13, 5));
                Console.WriteLine(ortalama(13, 8, 7));
                Console.ReadKey();
            }
        }




}

    
  /*                
public class RefOutExample

{
    public static void Main()

    {
        int refValue = 5;
        //başlangıç değeri atanması zorunludur.

        int outValue;
        //başlangıç değeri atanması zorunlu değildir.

        ChangeMethod(out outValue, ref refValue);

        Console.WriteLine("ChangeMethod'dan sonra refValue : " + refValue); //Output 7
        Console.WriteLine("ChangeMethod'dan sonra outValue: " + outValue); //Output 8
    }

    static void ChangeMethod(out int i, ref int j)
    {
        i = 8; // i argümanına bir değer atamak zorunludur
        j = j + 2; // j için böyle bir zorunluluk yoktur
    }
}*/

[Patika Dev Sayfam](https://app.patika.dev/sevaalnuur)