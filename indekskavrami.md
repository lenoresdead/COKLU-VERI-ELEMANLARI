# İndeks Kavramı
Çoklu verideki her bir elemanın konumu indeks ile belirtilir.İndeks, her daim 0'dan başlar ve toplam eleman sayısının bir eksiğinde sonlanır.

Yani,çoklu verinin bulunduğu konumun indseksi 0'dır.

Örneğin;

liste=[1,2,3,4,5]
print(liste[2])

3 sayısı gösterilir.

veya

liste[3]=a

listedeki 4 sayısını a harfi olarak yeniden adlandırır.

  İndeks kullanarak liste içindeki sayılarla işlem yapma örneği;

  b= [1,3,-5,-7]

  pozitiflerintoplami=b[0]+b[1]
  
  negatiflerintoplami=b[2]+b[3]

  # Dilimleme Yapısı
  Özel aralıklar ile çoklu verilerden elemanlara ulaşmamızı sağlar.Başlangıç indeksi dahildir.Bitiş indeksi değildir.

  p=[0,0,0,0,0,0,1,1,1,0,0,0,0]

  dilimleme=p[6:9]

  # artış miktarı
   kullanımı

   liste[başlangıç:bitiş:artış miktarı]


   İndeks hakkında güzel bir örnek;

   bilgi; Palindram kelime, düz de ters de okunuşu aynı olan kelimelerdir.

   bunu pytgon yazılım dili kullanarak kelimeleri teyit etmek istersek şöyle bir kod yazabiliriz:


  kelime=input("Lutfen kontrol edilecek kelimeyi giriniz:")
  print(kelime==kelime[::-1])
  
   
