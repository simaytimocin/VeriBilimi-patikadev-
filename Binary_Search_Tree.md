# Başlangıç Seviye Veri Bilimi Patikası

## Proje 3

### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

#### Binary-Search-Tree içerisinde bir düğümün sağ tarafında kendisinden büyük elemanlar, sol tarafında ise kendisinden küçük elemanlar bulunur.

root = 7

                                                (7)
                                             /      \
                                          (5)         (8)
                                         /   \           \
                                      (1)     (6)         (9)
                                     /    \
                                   (0)     (3)
                                           /   \
                                          (2)  (4)
                                 

                                 

5 < 7 olduğu için sol tarafa ekledik.
1 < 7  ve 1 < 5 olduğu için sol tarafa ekledik.
8 > 7 olduğu için sağ tarafa ekledik.
3 < 7 olduğu için önce sol tarafa ve 3 > 1 olduğu için sonra sağ tarafa ekledik.
0 < 7 ve 0 < 1 olduğu için sol tarafa ekledik.
9 > 7 ve 9 > 8 olduğu için sağ tarafa ekledik.
4 < 7 olduğu için önce sol tarafa 4 > 3 olduğu için sonra sağ tarafa ekledik.
2 < 7 ve 2 < 3 olduğu için sol tarafa ekledik.
