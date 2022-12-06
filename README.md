1.PROJE
[22,27,16,2,18,6] -> Insertion Sort
Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1Average case: Aradığımız sayının ortada olması
2Worst case: Aradığımız sayının sonda olması
3Best case: Aradığımız sayının dizinin en başında olması.
.
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
-------------------------------------------------------
çözüm
1;

[2,27,16,22,18,6] -> 1 [2,6,16,22,18,27] -> 2 [2,6,16,18,22,27] -> 3

2;

22,27,16,2,18,6] dizisinde 6 tane eleman vardır, yani 6 tane işlem yapılacaktır demektir. ilk adımda n-> 6 tane işlem, n + (n-1) + (n-2) + (n-3) .... 1 A Bu algoritmada n+(n-1)+(n-2)+(n-3)+(n-4)+1 kadar işlem yapılır. Bu işlemin formülü: [n(n+1)]/2'dir. Bu formül sadeleştirilerek: (n²+n)/2 elde edilir.
Big-O değeri = O(n²)

3; Aradığımız sayı 18 dizinin ortasında olduğu için bu avarage case'dir.

4;

[2|3,5,8,7,9,4,15,6] [2,3|5,8,7,9,4,15,6] 3 [2,3,4|7,9,5,15,6] 4 2,3,4,5,7,9,8,15,6]
