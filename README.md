# PROJE 1

INSERTION SORT

| array  | 22 | 27 | 16 | 2  | 18 | 6  | Dizinin verilen hali bu şekildedir.                                                                   |
|--------|----|----|----|----|---:|----|-------------------------------------------------------------------------------------------------------|
| 1.step | 
```diff
- 22```
-   | 27 | 16 | 2 | 18 | 6  | İlk adımda 22 < 27 işlemine bakılır ve değişim olmaz.                                                 |
| 2.step | 16  | 16  | 27 | 2 | 18 | 6 | 2. adımda 27 > 16 işlemine göre 16 ve 27 sayıları yer değiştirir.                                     |
| 3.step | 22  | 16  | 2 | 27 | 18 | 6 | 3. adımda 27 > 2  işlemine göre 27 ve 2 sayıları yer değiştirir.                                      |
| 4.step | 22  | 2  | 16 | 27 | 18 | 6 | 4. adımda 16 > 2  işlemine göre 16 ve 2 sayıları yer değiştirir.                                      |
| 5.step | 2  | 22  | 16 | 27 | 18 | 6 | 4. adımda 22 > 2  işlemine göre 22 ve 2 sayıları yer değiştirir.                                      |
| 4.step | 22  | 2  | 16 | 27 | 18 | 6 | 4. adımda 16 > 2  işlemine göre 16 ve 2 sayıları yer değiştirir.                                      |
| 4.step | 22  | 2  | 16 | 27 | 18 | 6 | 4. adımda 16 > 2  işlemine göre 16 ve 2 sayıları yer değiştirir.                                      |
| 4.step | 22  | 2  | 16 | 27 | 18 | 6 | 4. adımda 16 > 2  işlemine göre 16 ve 2 sayıları yer değiştirir.                                      |
| 4.step | 22  | 2  | 16 | 27 | 18 | 6 | 4. adımda 16 > 2  işlemine göre 16 ve 2 sayıları yer değiştirir.                                      |

Big-O gösterimi, tek bir for ile O(n^2) şeklindedir. İç içe 2 for döngüsü kullanır.

Dizi sıralandıktan sonra, 18 sayısı dizinin ortalarında bulunduğundan Avarage Case'e girer.





