# Veri Yapıları ve Algoritmalar Projeleri 
<br>

> **Proje 1** [22,27,16,2,18,6] -> Insertion Sort
>1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
>1. Big-O gösterimini yazınız.
>1.  Time Complexity: Average case: Aradığımız sayının ortada olması
><br> Worst case: Aradığımız sayının sonda olması
><br> Best case: Aradığımız sayının dizinin en başında olması.
>1. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
>1. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


```
1.  [22,27,16,2,18,6]    n 
    [2,27,16,22,18,6]    n-1 
    [2,6,16,22,18,27]    n-2 
    [2,6,16,18,22,27]    n-3

2. O(n²)

3. Avarage Case: O(n²) 
   Worst Case: O(n²) 
   Best Case: O(n)

4. Avarage Case

5.   [2,3,5,8,7,9,4,15,6]
     [2,3,4,8,7,9,5,15,6]
     [2,3,4,5,7,9,8,15,6]
     [2,3,4,5,6,9,8,15,7]
```
<br>

> **Proje 2** [16,21,11,8,12,22] -> Merge Sort
>1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
>1. Big-O gösterimini yazınız.


```
1.  [16,21,11,8,12,22]
    [16,21,11] [8,12,22]
    [16] [21,11] [8,12] [22]
    [16] [21] [11] [8] [12] [22]
    [16] [11,21] [8,12] [22]
    [11,16,21] [8,12,22]
    [8,11,12,16,21,22]

2. O(6(log6)) 


```
<br>

> **Proje 3** [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] -> Binary Search Tree 
>* Yukarı verilen dizinin binary search tree aşamalarını yazınız.

```
1.  7 rakamı root olarak belirlenir.

             7 (root)

2. 5 sayısı 7'den küçük olduğundan 7'nin soluna yazılır.


             7
             /
          5  

3. 1 sayısı 5'ten ve 7'den küçük olduğundan 7 ve 5'in soluna yazılır.

             7
             /
          5
        /
       1

4. 8 sayısı 7'den büyük olduğundan 7'nin sağına yazılır.

             7
             / \
           5      8
        /
       1

5. 3 sayısı 7'den ve 5'ten küçük olduğundan 5'in soluna, 1'den büyük olduğundan 1'in sağına yazılır.

             7
             / \
          5      8
        /  \       
       1
      / \
    0    3  

6. 6 sayısı 7'den küçük olduğundan 7'nin soluna, 5'ten büyük olduğundan 5'in sağına yazılır.

             7
             / \
          5      8
        /  \
       1    6
        \
         3  

7. 0 sayısı 7'den, 5'ten ve 1'den küçük olduğundan 1'in soluna yazılır.

             7
             / \
          5      8
        /  \ 
       1    6
      / \
    0    3  

8. 9 sayısı 7'den ve 8'den büyük olduğundan 8'in sağına yazılır

             7
             / \
          5      8
        /  \       \
       1    6       9
      / \
    0    3  

9. 4 sayısı 7'den ve 5'ten küçük olduğundan 5'in soluna, 1'den ve 3'ten büyük olduğundan 3'ün sağına yazılır

             7
             / \
          5      8
        /  \       \
       1    6       9
      / \
    0    3  
           \       
            4

10. 2 sayısı 7'den ve 5'ten küçük olduğundan 5'in soluna, 1'den büyük olduğundan 1'in sağına ve 3'ten küçük olduğundan 3'ün soluna yazılır

             7
             / \
          5      8
        /  \       \
       1    6       9
      / \
    0    3  
        /  \       
       2    4
```

<br><br>

## Patika.Dev <br> [/furkancomert](https://app.patika.dev/furkancomert)
