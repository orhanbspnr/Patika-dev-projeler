# MERGE SORT

[Patika.dev](https://www.patika.dev/tr)

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

1.Dizi iki gruba ayrılır.
[16,21,11] [8,12,22]

2. [16] [21,11] [8,12] [22] -> Dizi tekrar bölündü.

3. [16] [21] [11] [8] [12] [22] -> Dizi tekli gruplara ayrıldı.

4.  [16] [11,21] [8,12] [22] -> Gruplar sıralanarak ikili gruplara dönüştürüldü.

5. [11,16,21] [8,12,22] -> Sıralanarak üçlü gruplar oluşturuldu.

6. [8,11,12,16,21,22] -> Tüm grup sıralı bir şekilde birleştirildi. 

Big-O gösterimini yazınız.

1. O(nlogn)
