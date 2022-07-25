## **[16,21,11,8,12,22]** Merge Sort

[16,21,11,8,12,22] ikiye bölünür

[16,21,11]  --- [8,12,22]
[16,21] - [11] --- [8,12] - [22]
[16] - [21] - [11] --- [8] - [12] - [22]

Bu en küçük veri grupları küçükten büyüğe doğru birleştirilir.

 [11,16,21] ve [8,12,22] en son iki grup bir araya getirilir.
 
[8,11,12,16,21,22]

## Big O Notation
Tüm case'lerde time complexity O(nlogn)'dir.
