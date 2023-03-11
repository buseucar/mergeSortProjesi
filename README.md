# mergeSortProjesi
merge sort projesi
## [16,21,11,8,12,22] -> Merge Sort

### Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
### Big-O gösterimini yazınız.
    1. aşama: dizi ortadan ikiye ayrılır. 
    (16,21,11) ve (8,12,22) 
    2. aşama: oluşturulan diziler tekrar ikiye bölünür. 
    (16,21), (11), (8,12), (22)
    3. sıralama yapılır. 
    (11,16,21) ve (8,12,22)
    4. son kalan diziler küçükten büyüğe sıralanır. 8 11'den daha küçük olduğu için başa alınır. Sonra 16 ve 12 karşılaştırılır. Son olarak 21 ve 22 karşılaştırılır.  
    [8,11,12,16,21,22]

    Big-O gösterimi:
    O(nlogn)