# [22,27,16,2,18,6] -> Insertion Sort
## 1. Soru Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız

* 1. **Aşama**: [22|,27,16,2,18,6] 22 nin solunda kıyaslanacak rakam olmadığından kendi içinde sıralıdır büyüzden değişiklik yapılmaz 2. aşamaya geçer
* 2. **Aşama**: [22,27|,16,2,18,6] 27 ilen 22 yi kıyaslanır 27 22 den büyüktür değişiklik yapmaz 3. aşamaya geçer
* 3. **Aşama**: [22,27,16|,2,18,6] 16 ile 27 yi kıyaslanır 16 27 den küçüktür yer değişirler -> [22,16,27|,2,18,6] sonrasında 16 ilen 22 kıyaslanır 16 22 den küçüktür yer değişirler -> [16,22,27|,2,18,6] 16 nın solunda kıyaslanacak rakam kalmadığından sonraki aşamaya geçer
* 4. **Aşama**: [16,22,27,2|,18,6] 2 ilen 27 yi kıyaslanır 2 27 den küçüktür yer değişirler -> [16,22,2,27|,18,6] 2 22 ilen kıyaslanır 2 22 den küçüktür yer değişirler -> [16,2,22,27|,18,6] 2 16 ilen kıyaslanır 2 16 dan küçüktür yer değişirler -> [2,16,22,27|,18,6] 2 nin solunda kıyaslanacak rakam kalmadığından sonraki aşamaya geçer
* 5. **Aşama**: [2,16,22,27,18|,6] 18 ile 27 kıyaslanır 18 27 den küçüktür yer değişirler -> [2,16,22,18,27|,6] 18 22 ile kıyaslanır 18 22 den küçüktür yer değişirler -> [2,16,18,22,27|,6] 18 16 ile kıyaslanır 18 16 dan büyüktür değişiklik yapılmaz sonraki aşamaya geçer
* 6. **Aşama**: [2,16,18,22,27,6|] 6 ile 27 kıyaslanır 6 27 den küçüktür yer değişirler -> [2,16,18,22,6,27|] 6 ile 22 kıyaslanır 6 22 den küçüktür yer değişirler -> [2,16,18,6,22,27|] 6 ile 18 kıyaslanır 6 18 den küçüktür yer değişirler -> [2,16,6,18,22,27|] 6 ile 16 kıyaslanır 6 16 dan küçüktür yer değişirler -> [2,6,16,18,22,27|] 6 ile 2 kıyaslanır 6 2 den büyüktür değişiklik yapılmaz SIRALANACAK ELEMAN KALMADIĞINDAN işlem sonlanır
## 2. Soru Yukarıda verilen dizinin Big-o gösterimini yazınız
