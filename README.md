# proje-1
A.
Insertion Sort Aşamaları
[22, 27, 16, 2, 18, 6]

[22, 27, 16, 2, 18, 6] .... 1
[16, 22, 27, 2, 18, 6]
[2, 16, 22, 27, 18, 6]
[2, 16, 18, 22, 27, 6] .... n-1
[2, 6, 16, 18, 22, 27] .... n

Big-0 gösterimi
worst case O(n^2)
0+1+2+3+4…..+n-1 = [n*(n-1)]/2 : n^2

Zaman karmaşıklığı
best case: O(n)
average case: O(n^2)
worst case: O(n^2)

sıralı dizinde 18 sayısı, average case: O(n^2) kapsar.

B.
[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
[7,3,5,8,2,9,4,15,6]

[3,7,5,8,2,9,4,15,6]
[3,5,7,8,2,9,4,15,6]
[3,5,7,8,2,9,4,15,6]
[3,5,7,2,8,9,4,15,6]
