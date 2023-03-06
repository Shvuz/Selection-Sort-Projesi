# Selection-Sort-Projesi
[7, 3, 5, 8, 2, 9, 4, 15, 6] => [3, 7, 5, 8, 2, 9, 4, 15, 6]
[3, 7, 5, 8, 2, 9, 4, 15, 6] => [3, 5, 7, 8, 2, 9, 4, 15, 6]
[3, 5, 7, 8, 2, 9, 4, 15, 6] => [2, 3, 5, 7, 8, 9, 4, 15, 6]
[2, 3, 5, 7, 8, 9, 4, 15, 6] => [2, 3, 5, 7, 8, 4, 9, 15, 6]
[2, 3, 5, 7, 8, 4, 9, 15, 6] => [2, 3, 5, 7, 4, 8, 9, 15, 6]
[2, 3, 5, 4, 7, 8, 9, 15, 6] => [2, 3, 4, 5, 7, 8, 9, 15, 6]
[2, 3, 4, 5, 7, 8, 9, 15, 6] => [2, 3, 4, 5, 7, 8, 9, 6, 15]
[2, 3, 4, 5, 6, 7, 8, 9, 15] => [2, 3, 4, 5, 6, 7, 8, 9, 15]

Yukarıdaki sıralama için Big-O gösterimi O(n^2) dir.

Dizi sıralandıktan sonra 18 sayısı worst case kapsamına girer. Yani, aradığımız sayının dizinin sonunda olması durumunda O(n) zaman kompleksitesi gerektirir.

[7, 3, 5, 8, 2, 9, 4, 15, 6] dizisinin Selection Sort'a göre ilk 4 adımı:

[2, 3, 5, 8, 7, 9, 4, 15, 6]
[2, 3, 4, 8, 7, 9, 5, 15, 6]
[2, 3, 4, 5, 7, 9, 8, 15, 6]
[2, 3, 4, 5, 6, 9, 8, 15, 7]





