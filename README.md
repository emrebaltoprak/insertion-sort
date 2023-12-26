<!-- Verilen dizinin sort türüne göre aşamalarını yazınız. -->


[22,27,16,2,18,6] -> Insertion Sort

* step 1      [2 | 27, 16, 22, 18, 6]
* step 2      [2, 6 | 16, 22, 18, 27]
* step 3      [2, 6, 16 | 22, 18, 27]
* step 4      [2, 6, 16, 18 | 22, 27]
* step 5      [2, 6, 16, 18, 22 | 27]
* step 6      [2, 6, 16, 18, 22, 27]
***
<!-- Big-O gösterimini yazınız. -->

n+(n-1)+(n-2)...+1 = (n*(n+1))/2 = (n^2+n)/2

O(n^2)
***
<!-- Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması. -->

18 sayısı ortada olduğu için Average case dir.
***
<!-- [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.  -->

* [2 | 3,5,8,7,9,4,15,6]
* [2,3 | 5,8,7,9,4,15,6]
* [2,3,4 | 8,7,9,5,15,6]
* [2,3,4,5 | 7,9,8,15,6]
