# Insertion Sort Projesi
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

### Çözüm

Best Case durumda O(n) ==>> Dizinin sıralı olması durumunda gerçekleşir.    
Average Case durumda O(n^2) ==>> Dizideki sayıların karışık sıralanması sırasında olur.   
Worst Case durumda O(n^2) ==>> Dizi ters şekilde yani en büyükten en küçüğe sıralanmış şekildeyse gerçekleşir. 

Bu örnekte sıralama karışık olduğu için Average case yani O(n^2) geçerlidir.

```
[22,27,16,2,18,6]
[22,16,27,2,18,6]
[16,22,27,2,18,6]
[2,16,22,27,18,6]
[2,16,18,22,27,6]
[2,6,16,18,22,27]
```
Bu örnekte Average Case senaryosu geçerlidir.



[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


```
[7,3,5,8,2,9,4,15,6]
[3,7,5,8,2,9,4,15,6]
[3,5,7,8,2,9,4,15,6]
[2,3,7,5,8,9,4,15,6]
[2,3,4,7,5,8,9,15,6]
```
