# Insertion-Sort
www.patika.dev insertion sort projesi

## Proje 1

[22,27,16,2,18,6]

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

1- 
    [22,27,16,2,18,6]
    [2,27,16,22,18,6]
    [2,6,16,22,18,27]
    [2,6,16,18,22,27]
    
2-
   n tane elemanımız var ve işlem 1 eleman kalana kadar devam edecek. Bunun için formülümüz n*(n+1)/2= (n^2+n)/2
    
   Big O Notation'da domine eleman dikkate alındığı için : O(n^2)
    
3-
    *Average case: O(n)
    *Worst case: O(n^2)
    *Best case: O(n)
    
4-
    Dizi sıralandıktan sonra 18 dizinin ortasında bulunduğu için Avarage Case kapsamına girer.
    
    
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

   [2,3,5,8,7,9,4,15,6]
   [2,3,4,8,7,9,5,15,6]
   [2,3,4,5,7,9,8,15,6]
   [2,3,4,5,6,9,8,15,7]

