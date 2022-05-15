## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
### Root[6] binary search tree arama yötemine eleman eklerken ilk olarak Root'a sorularak eklenecek eleman Root dan büyükmü küçükmü olduğu referans alınır eğer küçükse Root'un soluna büyükse Root'un sağına yazılır ve eklenecek diğer elemanlar alt dallardaki elemandan büyükse sağına küçükse soluna yazılarak eklenir
```
                                         6
                                      /    \
                                     5      7
                                    /        \        
                                   1          8
                                  / \          \
                                 0   3          9
                                    / \
                                   2    4
```
### Sırasıyla eleman ekleme aşamaları
* 6'yi root kabul ettik ağacımızın en başına yazdık
* 7'yi eklemek istiyoruz root[6] a soruyoruz 7 senden büyükmü evet 7 root'dan büyük 7'yi root'un sağına ekliyoruz
* 5'i eklemek istiyoruz root'a soruyoruz 5 senden büyükmü hayır 5 root'dan küçük root'un soluna yazıyoruz
* 1'i eklemek istiyoruz root'a soruyoruz 1 senden büyükmü hayır 1 root'dan küçük root'un soluna geçiyoruz ama burda 5 var 5 e soruyoruz 1 senden büyükmü hayır 1 5'den küçük 5'in soluna 1'i yazıyoruz
* 8'i eklemek istiyoruz ve sırasıyla bakıyoruz 8 root'dan büyük sağına ğeçiyoruz sonrasında 8 7'den büyük 7'nin sağına 8'i ekliyoruz
* 3'ü eklemek istiyoruz sırasıyla bakıyoruz 3 root'dan küçük soluna geçiyoruz bakıyoruz 3 5'den küçük soluna geçiyoruz 3 1'den büyük 3 ü 1'in sağına ekliyoruz
* 0'ı eklemek istiyoruz sırasıyla bakıyoruz 0 root'dan küçük soluna geçiyoruz 0 5'den küçük soluna geçiyoruz 0 1'den küçük 0' 1'in soluna ekliyoruz
* 9'u eklemek istiyoruz sırasıyla bakıyoruz 9 root'dan büyük sağına geçiyoruz 9 7'den büyük sağına geçiyoruz 9 8'den büyük 9'u 8'in sağına yazıyoruz
* 4'ü eklemek istiyoruz sırasıyla bakıyoruz 4 root'dan küçük soluna geçiyoruz 4 5'den küçük soluna geçiyoruz 4 1'den büyük sağına geçiyoruz 4 3'den büyük 4'ü 3'ün sağına yazıyoruz
* 2'yi eklemek istiyoruz sırasıyla bakıyoruz 2 root'dan küçük soluna geçiyoruz 2 5'den küçük soluna geçiyoruz 2 1'den büyük sağına geçiyoruz 2 3'den küçük 2'yi 3'ün soluna ekliyoruz