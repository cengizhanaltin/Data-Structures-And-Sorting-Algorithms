##Selection Sort Örneği

#####[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

-Average case: Aradığımız sayının ortada olması
-Worst case: Aradığımız sayının sonda olması
-Best case: Aradığımız sayının dizinin en başında olması.

------------------------------------------------------------
Bu durumda en küçük elemanı bulmamız ve en baştaki sayı ile yer değiştirmemiz daha sonra en küçük 2. elmanı bulmamız ve 2. sıradaki elemanla  yer değiştirmemiz gerekmektedir. Liste sıralı hale gelene kadar bu işlemleri tekrarlarız. 

1. [2,27,16,22,18,6] n işlem
2. [2,6,16,22,18,27] n-1 işlem
3. [2,6,16,22,18,27] n-2 işlem
4. [2,6,16,18,22,27] 1

-Big-O gösterimi O(n<sup>2</sup>) dir.

-18 sayısı ortada olduğundan Avarage case dir.

#####[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

1. [2,3,5,8,7,9,4,15,6]
2. [2,3,5,8,7,9,4,15,6]
3. [2,3,4,8,7,9,5,15,6]
4. [2,3,4,5,7,9,8,15,6]

şeklindedir.

https://app.patika.dev/cengo




