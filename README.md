# Insertion-sort-proje-Proje-1-
Kodluyoruz Eğitimi kapsamında Insertion sort proje (Proje 1)
Insertion Sort
Insertion sort algoritmasını kullanarak verilen diziyi sıralayalım:

Başlangıç: [22, 27, 16, 2, 18, 6]

Adım: [22, 27, 16, 2, 18, 6] - 27 ve 22 yerinde çünkü 27 > 22
Adım: [16, 22, 27, 2, 18, 6] - 16, 22 ve 27'nin önüne gelir çünkü 16 < 22
Adım: [2, 16, 22, 27, 18, 6] - 2, tüm elemanların önüne gelir çünkü 2 < 16
Adım: [2, 16, 18, 22, 27, 6] - 18, 22 ve 27'nin önüne gelir çünkü 18 < 22
Adım: [2, 6, 16, 18, 22, 27] - 6, 16, 18, 22 ve 27'nin önüne gelir çünkü 6 < 16
Sonuç: [2, 6, 16, 18, 22, 27]

Big-O Gösterimi
Insertion Sort'un en kötü durumu (worst case) ve ortalama durumu (average case) O(n^2) ve en iyi durumu (best case) O(n)'dir.

18 Sayısının Time Complexity Durumu
18 sayısı sıralandıktan sonra [2, 6, 16, 18, 22, 27] dizisinde ortada yer alır. Bu nedenle 18 sayısı "Average case" kapsamına girer.

Selection Sort
[7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Selection Sort'a göre ilk 4 adımı:

Başlangıç: [7, 3, 5, 8, 2, 9, 4, 15, 6]

Adım: En küçük eleman olan 2, 7'nin yerine geçer.
[2, 3, 5, 8, 7, 9, 4, 15, 6]

Adım: İkinci en küçük eleman olan 3, zaten yerinde.
[2, 3, 5, 8, 7, 9, 4, 15, 6]

Adım: Üçüncü en küçük eleman olan 4, 5'in yerine geçer.
[2, 3, 4, 8, 7, 9, 5, 15, 6]

Adım: Dördüncü en küçük eleman olan 5, 8'in yerine geçer.
[2, 3, 4, 5, 7, 9, 8, 15, 6]
