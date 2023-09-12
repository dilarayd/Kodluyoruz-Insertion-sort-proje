1. # [22,27,16,2,18,6] -> Insertion Sort

# 1.1. # Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6]--------> İkinci elemanı solundaki sayıyla kıyaslarız. 27>22 olduğu için değişiklik olmaz ve üçüncü eleman olan 16 sayısını solundaki sayılarla kıyaslarız. 16<22<27 olduğu için 16 en başa geçer.
[16,22,27,2,18,6]-------->Dördüncü eleman olan 2 için aynı işlemi yaparız ve 2 en başa geçer.
[2,16,22,27,18,6]-------->Beşinci eleman olan 18 için aynı işlemi yaparız ve üçüncü sıraya geçer.
[2,16,18,22,27,6]-------->Son eleman olan 6 için aynı işlemi yaparız ve ikinci sıraya geçer.
[2,6,16,18,22,27]- Dizinin son hali bu şekilde olur. 

# 1.2. # Big-O gösterimini yazınız.

0+1+2+3+4…..+n-1 = [n*(n-1)]/2 = (n^2-n)/2

 O(n^2)

# 1.3. # Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

Aradığımız 18 sayısı dizinin ortasında olduğu için Average case kapsamına girer.


 2. # [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Dizinin en küçük öğesi olan 2 sayısı en başa yazılır.Bunun için en baştaki sayı olan 7 ile yer değiştirmesi gerekir. 
[2,3,5,8,7,9,4,15,6]

En baştaki öğre sabitlendiği için ikinci öğeden itibaren aynı işlemler dizinin sağ tarafındaki sayılar arasında tekrarlanır. En küçük ikinci sayı 3 olduğu için bu aşamada dizi değişmez, bu nedenle bir sonraki sayıya geçilir.Dizinin üçüncü en küçük sayısı 4 olduğu için üçüncü sırada yer alan 5 ile yer değiştirmesi gerekir.
[2,3,4,8,7,9,5,15,6]

Dizinin dördüncü en küçük sayısı 5 olduğu için dizinin dördüncü sırasında yer alan 8 ile yer değiştirmesi gerekir.
[2,3,4,5,7,9,8,15,6]

Dizinin beşinci en küçük sayısı 6 olduğu için dizinin beşinci sırasında yer alan 7 ile yer değiştirmesi gerekir.
[2,3,4,5,6,9,8,15,7]