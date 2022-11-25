# VeriYapilariveAlgoritmalar1
[22,27,16,2,18,6] için Instertion Sort ;
1. adım ; 2 en küçük sayı olduğu için 22 ile yer değiştirerek başa geçer [2,27,16,22,18,6]
2. adım ; 6 2 den sonra en küçük sayı olduğu için 2nin sağına geçer ve 27 ile yer değiştirir [2,6,16,22,18,27]
3. adım ; 16 doğru yerde olduğundan 18 ve 22 nin yerlerinin değişmesi yeterli olacaktır. [2,6,16,18,22,27]
 tüm sayılar küçüktenm büyüğe doğru sıralanmıştır

 Dizimizdeki eleman sayısı n olduğundan işlem sayımız da n olacaktır. Ve işlemimiz son işlem sayısı 1 olana kadar devam edecektir.(n,n-1,n-2...,1)
 Böylece yaptığımız işlem sayısı n+(n-1)+(n-2)+(n-3)+(n-4)+1 ----> (n^2+n)/2
 yani Big-O Notation = O(n^2)

[2,6,16,18,22,27] olarak sonuçlandığı için ve "18" ortada kaldığı için Average case'e girer.

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı

En küçük "2" olduğu için, 2 ve 7'nin yerini değiştireceğiz. [2,3,5,8,7,9,4,15,6]
4 rakamı 3 ve 5 arasına konularak 3 ve 5 yer değiştirmeden düzen sağlanır [2,3,4,5,8,7,9,15,6] 
6 , 5 ve 8 arasına geçer. [2,3,4,5,6,8,7,9,15] 
7, 6 ve 8 arasına geçer. [2,3,4,5,6,7,8,9,15]
