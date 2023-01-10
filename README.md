[16,21,11,8,12,22] - Merge Sort

Bu sıralama algoritmasında diziyi ortadan ikiye ayırarak tek eleman olacak şeklinde kalana kadar bölmeye devam ediyoruz.

               [16,21,11,8,12,22]
              [16,21,11]  [8,12,22]
            [16] [21,11]  [8] [12,22]
        [16]  [21]  [11]  [8]  [12]  [22]
           [16]  [11,21]  [8]  [12,22]
              [11,16,21]  [8,12,22]
               [8,11,12,16,21,22]

Big-O gosterimi O(nlogn)