# [22,27,16,2,18,6] -> Insertion Sort
## 1. Soru Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız

* 1. **Aşama**: [22|,27,16,2,18,6] 22 nin solunda kıyaslanacak rakam olmadığından kendi içinde sıralıdır buyüzden değişiklik yapılmaz sonraki aşamaya geçer
* 2. **Aşama**: [22,27|,16,2,18,6] 27 ilen 22 yi kıyaslanır 27 22 den büyüktür değişiklik yapmaz 3. aşamaya geçer
* 3. **Aşama**: [22,27,16|,2,18,6] 16 ile 27 yi kıyaslanır 16 27 den küçüktür yer değişirler -> [22,16,27|,2,18,6] sonrasında 16 ilen 22 kıyaslanır 16 22 den küçüktür yer değişirler -> [16,22,27|,2,18,6] 16 nın solunda kıyaslanacak rakam kalmadığından sonraki aşamaya geçer
* 4. **Aşama**: [16,22,27,2|,18,6] 2 ilen 27 yi kıyaslanır 2 27 den küçüktür yer değişirler -> [16,22,2,27|,18,6] 2 22 ilen kıyaslanır 2 22 den küçüktür yer değişirler -> [16,2,22,27|,18,6] 2 16 ilen kıyaslanır 2 16 dan küçüktür yer değişirler -> [2,16,22,27|,18,6] 2 nin solunda kıyaslanacak rakam kalmadığından sonraki aşamaya geçer
* 5. **Aşama**: [2,16,22,27,18|,6] 18 ile 27 kıyaslanır 18 27 den küçüktür yer değişirler -> [2,16,22,18,27|,6] 18 22 ile kıyaslanır 18 22 den küçüktür yer değişirler -> [2,16,18,22,27|,6] 18 16 ile kıyaslanır 18 16 dan büyüktür değişiklik yapılmaz sonraki aşamaya geçer
* 6. **Aşama**: [2,16,18,22,27,6|] 6 ile 27 kıyaslanır 6 27 den küçüktür yer değişirler -> [2,16,18,22,6,27|] 6 ile 22 kıyaslanır 6 22 den küçüktür yer değişirler -> [2,16,18,6,22,27|] 6 ile 18 kıyaslanır 6 18 den küçüktür yer değişirler -> [2,16,6,18,22,27|] 6 ile 16 kıyaslanır 6 16 dan küçüktür yer değişirler -> [2,6,16,18,22,27|] 6 ile 2 kıyaslanır 6 2 den büyüktür değişiklik yapılmaz SIRALANACAK ELEMAN KALMADIĞINDAN işlem sonlanır
* - ***son sıralı şekli*** -> [2,6,16,18,22,27]
## 2. Soru Yukarıda verilen dizinin Big-o gösterimini yazınız
* **Insertion sort Big-o gösterimi**: worst case O(n²) best case O(n) dir
## 3. Soru Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
* **Average case** kapsamına girer çünkü 18 sayısı sıralamanın ortasındadır
# [7,3,5,8,2,9,4,15,6] -> Insertion Sort
## Yukarıda verilen dizinin sort türüne göre ***ilk 4 aşamasını yazınız***
* 1. **Aşama**: [7|,3,5,8,2,9,4,15,6] 7 nin solunda kıyaslanacak rakam olmadığından kendi içinde sıralıdır buyüzden değişiklik yapılmaz sonraki aşamaya geçer
* 2. **Aşama**: [7,3|,5,8,2,9,4,15,6] 3 7 ile kıyaslanır 3 7 den küçüktür yer değişirler -> [3,7|,5,8,2,9,4,15,6] 3 ün solunda kıyaslanacak rakam kalmadığından sonraki aşamaya geçilir
* 3. **Aşama**: [3,7,5|,8,2,9,4,15,6] 5 7 ile kıyaslanır 5 7 den küçüktür yer değişirler -> [3,5,7|,8,2,9,4,15,6] 5 ile 3 kıyaslanır 5 3 den büyüktür değişiklik yapılmaz sonraki aşamaya geçilir
* 4. **Aşama** [3,5,7,8|,2,9,4,15,6] 8 7 ile kıyaslanır 8 7 den büyüktür değişiklik yapılmaz sonraki aşamaya geçilir
