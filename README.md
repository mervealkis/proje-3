# proje-3
Binary search tree

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Binary search tree de bir düğüm her iki tarafada referans verir. Eleman eklerken roota bakılır. Rootun sağ tarafında kendinden büyük elemanlar, sol tarafında kendinden küçük elemanlar bulunur.

*Root* 7 dir. Dizideki sayılara tek tek baktığımızda; 5 sayısı 7 den küçük yedinin sol tarafında olur. 1 sayısı 7 den küçük yedinin sol tarafında, 5 ten küçük sol tarafına eklenir. 8 sayısı 7 den büyük yedinin sağ tarafına ekleriz. 3 sayısı 7 den küçük sol tarafında,5sayısının sol tarafnda, bir sayısının sağ tarafına eklenir. 6 sayısı 7 den küçük sol tarafında 5 sayısında büyük beşin sağ tarafına eklenir. 0 sayısı 7 den küçük sol tarafında, 5 ten küçük sol tarafında 1 den küçük sol tarafına eklenir. 9 sayısı 7 den büyük sağ tarafında, 8 den büyük sağ tarafına eklenir. 4 sayısı 7 den küçük sol tarafında, 5 ten küçük sol tarafında, 1 ve 3 ten büyük olduğu için sağ tarafına eklenir. 2 sayısı 7 den küçük sol tarafında, 5 ten küçük sol tarafında,1 den büyük sağında, üçten küçük sol tarafına eklenir.


|root *7* sayısı                   |  |  |     |  |  |  |  |  |  |  |  |
|--                                |--|--|-    |- |- |- |- |- |- |- |- |
|                                  |  |  |     |  |  |  | 7|  |  |  |  |  
|                                  |  |  |     |  |  | /|  |\ |  |  |  | 
|                                  |  |  |     |  | 5|  |  |  |8 |  |  | 
|                                  |  |  |     | /|  |\ |  |  |  |\ |  | 
|                                  |  |  | 1   |  |  |  |6 |  |  |  | 9|
|                                  |  | /|     |\ |  |  |  |  |  |  |  |
|                                  | 0|  |     |  | 3|  |  |  |  |  |  |
|                                  |  |  |     | /|  |\ |  |  |  |  |  |
|**en son 2 sayısını ekledik**     |  |  |**2**|  |  |  |4 |  |  |  |  |
