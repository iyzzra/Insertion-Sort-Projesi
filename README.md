# Insertion-Sort-Projesi
[22,27,16,2,18,6] dizininin Insertion Sort'a göre aşamalarını yazınız.

[2|,27,16,22,18,6] (n)
[2,6|,16,22,18,27] (n-1)
[2,6,16|,22,18,27] (n-2)
[2,6,16,18|,22,27] (1)
[2,6,16,18,22,27]
Big-O gösterimi: (n.(n+1))/2=(n^2+n)/2= 0(n^2)

Time Complexity: 
Avarage Case:Aradığımız sayının dizinin ortasında veya ortalarında olması. [2,6,16,(18),22,27]
Worst Case:Aradığımız sayının sonda olması veya büyükten küçüğe sıralanmış olması. [27,22,18,16,6,(2)] 
Best Case:Aradığımız sayının dizinin en başında olması. [(2),6,16,18,22,27]

Dizi Sıralandıktan sonra avarage case sınıfına girer çünkü 18 sayısı ortalardadır. [2,6,16,|18|,22,27]

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6]  n
[2|,3,5,8,7,9,4,15,6] n-1
[2,3|,5,8,7,9,4,15,6] n-2
[2,3,4|,8,7,9,5,15,6] n-3
[2,3,4,5|,7,9,8,15,6] n-4
