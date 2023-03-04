# PROJE 1

INSERTION SORT

| array  | 22 | 27 | 16 | 2  | 18 | 6  | Dizinin verilen hali bu şekildedir.                                                                   |
|--------|----|----|----|----|---:|----|-------------------------------------------------------------------------------------------------------|
| 1.step | 22  | 27 | 16 | 2 | 18 | 6  | İlk adımda 22 < 27 işlemine bakılır ve değişim olmaz.                                                 |
| 2.step | 16  | 22  | 27 | 2 | 18 | 6 | 2. adımda 27 > 16 işlemine göre 16 sayısı listenin en başına eklenir.                                 |
| 3.step | 2  | 16  | 22 | 27 | 18 | 6 | 3. adımda 27 > 2  işlemine göre 2 sayısı listenin en başına eklenir.                                  |
| 4.step | 2  | 16  | 18 | 22 | 27 | 6 | 4. adımda 27 > 18  işlemine göre 18 sayısı 27 ve 22 sayılarıyla yer değiştirir.                       |
| 5.step | 2  | 6  | 16 | 18 | 22 | 27 | 4. adımda 22 > 6  işlemine göre 6 sayısı listenin ikinci elemanı olarak alınır.                       |

Big-O gösterimi, tek bir for ile O(n^2) şeklindedir. İç içe 2 for döngüsü kullanır.

Dizi sıralandıktan sonra, 18 sayısı dizinin ortalarında bulunduğundan Avarage Case'e girer.


SELECTION SORT

| array  | 7  | 3  | 5  | 8  |  2 | 9 | 4 | 15 | 6 |
|--------|----|----|----|----|---:|---|---|----|---|
| 1.step | 3* | 7* | 5  | 8  |  2 | 9 | 4 | 15 | 6 |
| 2.step | 3  | 5* | 7* | 8  |  2 | 9 | 4 | 15 | 6 |
| 3.step | 3  | 5  | 7* | 8* |  2 | 9 | 4 | 15 | 6 |
| 4.step | 3  | 5  | 7  | 2* | 8* | 9 | 4 | 15 | 6 |
