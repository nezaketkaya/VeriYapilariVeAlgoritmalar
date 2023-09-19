# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

İlk eleman olan 7, BST'nin kök düğümü(root) olur.
###              7

5, kökten küçük olduğu için sol alt ağaca eklenir.
###              7
###            /
###          5

1, 7'den küçük olduğu için sola gider:
###              7
###            /
###          5
###        /
###      1

8, kökten büyük olduğu için sağ alt ağaca eklenir.
###              7
###            /   \
###          5       8
###        /
###      1

3, kökten küçük olduğu için sol alt ağacın sol tarafına, 5'in soluna, 1'in sağına eklenir.
###              7
###            /   \
###          5       8
###        /
###      1
###        \
###          3

6 kökten küçük olduğu için 7'nin soluna, 5'ten büyük olduğu için 5'in sağına eklenir.
###              7
###            /   \
###          5       8
###        /   \
###      1       6
###        \
###          3

0 en küçük olduğu için en sola eklenir.
###              7
###            /   \
###          5       8
###        /   \
###      1       6
###    /   \
###   0     3

9 kökten büyük olduğu için 7'nin sağına, 8'in de sağına eklenir.
###              7
###            /   \
###          5       8
###        /   \       \
###      1       6       9
###    /   \
###   0     3

4, 7 ve 5'in soluna, 1 ve 3'ün sağına eklenir.
###              7
###            /   \
###          5       8
###        /   \       \
###      1       6       9
###    /   \
###   0     3
###           \
###             4

2, 7 ve 5'in soluna, 1'in sağına, 3'ün soluna eklenir ve Binary-Search-Tree tamamlanır.
###              7
###            /   \
###          5       8
###        /   \       \
###      1       6       9
###    /   \
###   0     3
###       /   \
###      2     4






