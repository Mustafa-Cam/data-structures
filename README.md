# Selection sort 
---------------------------------------------------------------
[22,27,16,2,18,6] => selection sort

selection sorta göre sıralamamızı yapmaya çalışacağız

1. => en küçük sayımız 2, 2 yi en başa alıyoruz yer değişikliği yapıyoruz >>
n tane işlem  >>
[2,27,16,22,18,6]

2. => 2. en küçük sayımız 6 onu da 2. sıraya alalım >>
n-1 tane işlem >>
[2,6,16,22,18,27]

3. => bu mantıkla devam 3. sayımız zaten sıralanmış 4. geçelim >>
n-2 tane işlem  >>
[2,6,16,18,22,27]

4. [2,6,16,18,22,27] >> burda da 1 işlem oldu

sıralamamız tamamdır

notasyonda da katsayıları vs atarsak n^2 Big O notasyonumuza ulaşıyoruz

----------------------------------------------------------------

18 sayımız ise ortada olduğu için average notasyonuna giriyor

---
```
[7,3,5,8,2,9,4,15,6]

1.adım => [2,3,5,8,7,9,4,15,6] 
2.adım => [2,3,4,8,7,9,5,15,6] 
3.adım => [2,3,4,5,7,9,8,15,6] 
4.adım => [2,3,4,5,7,8,9,15,6] 

```
-----------------------------------

# Marge Sort

[16,21,11,8,12,22] -> Merge Sort

[16,21,11]  [8,12,22]

16 [21,11] -- 8 [12,22]

[11,16,21] --  [8,12,22]

burda 11 ile 8 karşılaştırılır sonra 8 11 şeklinde yazılır sonra 16 ile 12 ,, 12 16  şeklinde yazılır böyle böyle gider 

[8,11,12,16,21,22]
sonuç

Big O >> ilk 2 ye bölünüyor o kısımdan logn geliyor sonra n elemanlı için n-1 sorgulama yapılıyor ordan da n geliyor çarpınca Big O notasyonumuz (nlogn) oluyor 

---