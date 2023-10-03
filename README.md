# Binary-Search-Tree-proje
Patikalar Academy Projects #3
Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

İlk elemanı kök (root) olarak ayarlıyoruz: Root = 7

5, 1, 8, 3, 6, 0, 9, 4 ve 2 elemanlarını sırayla ekliyoruz:

5, root'un solundan gelir: Root'un solunda 5 bulunur.
1, 7'nin solundan gelir: 7'nin solundaki 5'in solunda 1 bulunur.
8, 7'nin sağından gelir: 7'nin sağına 8 eklenir.
3, 5'in sağından gelir: 5'in sağındaki 3'e eklenir.
6, 5'in sağından gelir: 5'in sağındaki 3'ün sağına 6 eklenir.
0, 1'in solundan gelir: 1'in solundaki 0'a eklenir.
9, 8'in sağından gelir: 8'in sağına 9 eklenir.
4, 3'ün sağından gelir: 3'ün sağına 4 eklenir.
2, 1'in sağından gelir: 1'in sağındaki 0'ın sağına 2 eklenir.

        7
       / \
      5   8
     / \   \
    1   3   9
   /   / \
  0   2   4
       \
        6
