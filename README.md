# InsertionSortProject

## Patika.dev Profilim = [https://app.patika.dev/krgzsalih](https://app.patika.dev/krgzsalih)


Verilen dizinin insertion sort türüne göre aşamaları

[22,27,16,2,18,6] -> Insertion Sort 

## Soru - 1
Yukarı verilen dizinin sort türüne göre aşamaları.


    [22,27,16,2,18,6]   n

    [2,27,16,22,18,6]   n-1

    [2,6,16,22,18,27]   n-2

    [2,6,16,18,22,27]   1

## Soru - 2
Big-O gösterimini yazınız.

    Sayıların toplamını : n + (n-1) + (n-2) + 1 yolu ile bulabileceğimizden,

    n*(n+1) / 2 formülüne ulaşabiliriz.
    Buradan da Big-O notation için dominant faktörü önemli olduğundan
    O(n^2) olarak buluruz. 

## Soru - 3
[22,27,16,2,18,6] dizisine göre Time Complexity: 

    Average case: Aradığımız sayı 2 olabilir,
    Worst case: Aradığımız sayı 6 olabilir, 
    Best case: Aradığımız sayı [2,6,16,18,22,27] olduğu gibi 2 olabilir.

## Soru - 4
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer ?
  
    [2,6,16,18,22,27] son hali olarak baktığımız da 18 sayısı ortada olduğundan dolayı Average case kısmına girmektedir. 


## Soru - 5 
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı şu şekilde yazılabilir.

        [7,3,5,8,2,9,4,15,6]    n

        [2,3,5,8,7,9,4,15,6]    n-1

        [2,3,4,8,7,9,5,15,6]    n-2
        
        [2,3,4,5,7,9,8,15,6]    n-3

