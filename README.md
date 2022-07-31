# Merge-Sort-Projesi  
[16,21,11,8,12,22] -> Merge Sort
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

ÇÖZÜM:
1) [16,21,11,8,12,22] dizisini ikiye bölünür.

2) [16,21,11] ve [8,12,22] olmak üzere iki dizi oluşturulur.

3) [16,21] - [11] ve [8,12] - [22] olarak tekrar böleriz.

4) Verileri teker teker olmak üzere ayırırız: [16]-[21]-[11]-[8]-[12]-[22]

5) Birer parçaya ayırdığımız verileri küçükten büyüğe kendi grupları içinde bölüştürülür: [16,21]-[11]-[8,12]-[22] => [11,16,21] - [8,12,22]

6) Son olarak,iki grup da birleştirilir. [8,11,12,16,21,22]

Big-O gösterimini yazınız.
CEVAP:
O(nlogn) 'dir
