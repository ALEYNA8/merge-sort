# merge-sort
Verilen Dizi:[16,21,11,8,12,22]

1.Diziyi ikiye böl:
 -sol dizi:[16,21,11]
 -sağ dizi:[8,12,22]
2.Her iki alt diziyi de tekrar ikiye böl:
-sol dizi[16,21,11] = [169 ve [21,11]
-sağ dizi[8,12,22]=[8] ve [12,22]
3.Daha fazla bölme işlemi yap:
-[21,11] = [21] ve [11]
-[12,22] = [12] ve [22]
4.Şimdi dizileri sıralayıp birleştirelim:
-[21] ve [11] birleşir:[11,21]
-[12] ve [22] birleşir:[12,22]
5.Bir üst seviyedeki dizileri sıralı bir şekilde birleştirin:
-[16] ve [11,21] birleşir:[11,16,21]
-[8] ve [12,22] birleşir:[8,12,22]
6.Son olarak iki alt diziyi birleştirin:
-[11,16,21] ve [8,12,22] birleşir.[8,11,12,16,21,22]
Sonuç: Sıralanmış dizi [8,11,12,16,21,22] olur.

Big-O gösterimi:
Merge Sort algoritmasının Big-O karmaşıklığı: O(n log n)
