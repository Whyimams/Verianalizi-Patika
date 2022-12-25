[22,27,16,2,18,6] -> Insertion Sort aşamalarini yaziniz.

Big-O gösterimini yapiniz !


Time Complexity: Dizi siralandiktan sonra 18 sayisi aşağidaki caselerden hangisinin kapsamina girer? 

Average case: Aradiğimiz sayinin ortada olmasi
Worst case: Aradiğimiz sayinin sonda olmasi
Best case: Aradiğimiz sayinin dizinin en başinda olmasi.


ANSWER


1.Adim:

Butun sayilara bakiyoruz ve en kucuk olan sayiyi en başa yazip, en kucuk sayiyi aldigimiz indexle yer degistiriyoruz.
[2,27,16,22,18,6]

2.Adim:

Artik 2'nin en kucuk eleman oldugunu biliyoruz. Daha sonra diger sayilar arasinda da ayni islemi yapiyoruz.
[2,6,16,22,18,27]

3.Adim:

Bu adimda en kucuk sayinin yerini bildigimiz icin kalan sayilar arasinda (22,18,27)en kucuk olani secip 4.siraya yaziyoruz.

[2,6,16,18,22,27]

4.Adim:

5.ve 6. sirada yer alan sayilar zaten sirali olduğu için bir işlem yapmiyoruz ve dizinin son hali şu şekilde oluyor
[2,6,16,18,22,27]


Big-O Gösterimi:

n+(n-1)+(n-2)+(n-3)+.......+1

n.(n+1)/2
(n^2+n)/2

Big-O (n^2)

Time Complexity: Dizi siralandiktan sonra 18 sayisi aşağidaki caselerden hangisinin kapsamina girer?

18 Sayisi dizinin ortasinda yer aldigi icin "Average Case" e girer.





