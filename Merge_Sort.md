# Başlangıç Seviye Veri Bilimi Patikası

## Proje 2

[16,21,11,8,12,22] -> Merge Sort

### 1 -Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

#### Merge Sort için; diziyi iki parçaya bölüp , kendi arasında sıraladıktan sonra birleştirme işlemi yapılır. Tek bir eleman kalana kadar bu işleme devam edilir.

                                    [16,21,11,8,12,22]
                             [16,21,11]               [8,12,22]
                       [16,21]      [11]          [8,12]     [22]  
                    [16]    [21]      [11]      [8]    [12]      [22]
                      [16,21]         [11]        [8,12]         [22]
                            [11,16,21]                  [8,12,22]
                                      [8,11,12,16,21,22]


### 2 - Big-O gösterimini yazınız.

Linearithmic time , çok büyük veri kümeleriyle iyi performans gösterme yeteneğine sahiptir. Merge sort için bu algoritma kullanılır ve Big- o gösterimi : O(nlogn) şeklindedir.