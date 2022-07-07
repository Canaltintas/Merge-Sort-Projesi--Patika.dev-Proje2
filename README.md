# Merge-Sort-Projesi--Patika.dev-Proje2
www.patika.dev profilim : https://app.patika.dev/cans06

## Merge Sort Proje 2

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

## Merge Sort Türüne Göre Aşamaları
[16,21,11,8,12,22]
Dizi tek bir eleman kalana kadar her adımda bölünüyor.İşlem sonunda sıralı bir şekilde dizi elemanları birleştirilerek dizi sıralı bir hale getiriliyor.

Dizinin ikiye bölünmesi :
1-[16,21,11] , [8,12,22]
2-[16],[21,11] ,[8],[12,22]
3-[16],[11],[21],[8],[12],[22] - parçalara ayrılan diziler için bir sıralama işlemide gerçekleştirilir
-İşlemler aynı şekilde birleştirilerek devam edilir.
4-[11,16,21],[8,12,22]
5-[8,11,12,16,21,22]


## Big-O Gösterimi :
n=6.

Yapılan sorgu sayısı n-1 olup BigO Gösterimi Log(n) dir.


