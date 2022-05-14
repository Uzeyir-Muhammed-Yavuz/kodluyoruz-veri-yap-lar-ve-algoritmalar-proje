# [16,21,11,8,12,22] -> Merge Sort
## 1. Soru: Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız
* **1. aşama:** tek eleman kalana kadar 2 ye bölüyoruz
* **2. aşama:** tek eleman kaldıktan sonra hangisi küçükse sola yazıp birleştiriyoruz

|                    | | | |16|21|11|8 |12|22| | | |
|------------------- |-|-|-|-|-|-|-|-|-|-|-|-|
|Diziyi 2ye bölüyoruz| | | |16|21|11| |8 |12|22|
|                    | | | | | | | | | | | | | | | | |
|tekrar 2ye bölüyoruz| |16|21| |11| |8 |12| |22|
|                    | | | | | | | | | | | | | | | | |
|tekrar 2ye bölüyoruz| |16| |21| |11| |8| |12| |22| | |
| |
|küçük olan solda olacak şekilde birleştiriyoruz|16|21| |8|11 | |12|22|
| |
| |8|11|16|21| |12|22|
| | 
|merge sort sıralı dizin son hali |8|11|12|16|21|22
## 2. Soru: Big-o gösterimini yazınız:
*  ### O(n log n)