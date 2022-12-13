## Merge Sort Projesi

[16,21,11,8,12,22]-> Merge Sort

***Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.***

***Big O gösterimini yapınız.***

- Merge sort bir listeyi her adımda parçaya ayırıp, tek eleman kalıncaya kadar bölüyor. Böldükten sonra sıralı bir şekilde sunuyor. Buna göre;

- Sayı dizisini önce ikiye bölüyoruz.

```[16,21,11]  [8,12,22]```

- Sonra tekrar ikiye bölüyoruz.

```[16] [21,11]    [8,12] [22]```

- Tek elemanlar oluşturuluyor.

```[16] [21] [11]   [8] [12] [22]```

- Bu aşamada elemanlar ***sıralı*** olarak ikişerli gruplar halinde birleştiriliyor.

```[16] [11,21]   [8,12] [22]```

- Elemanlar sıralı olarak tekrar iki grup halinde birleştiriliyor.

```[11,16,21]   [8,12,22]```

- Tüm elemanlar sıralı bir şekilde birleştirilerek merge sort tamamlanıyor.

```[8,11,12,16,21,22]```

- Big O gösterimi: ```"O (nlogn)'dir."```

[PatikaDev](https://app.patika.dev/meryemarikusu)