# PROJE 1 

# Soru 1 - [22,27,16,2,18,6] Insertion Sort

### 1.Öncelikle soldan başlayarak kıyaslamalar yapıyoruz. 22 sayısını 27 ile kıyaslıyoruz. 22 daha küçük bu yüzden yerleri değişmiyor.
`[22,27,16,2,18,6]`

### 2. Sonra bir sonraki sayı olan 27'yi 16 ile kıyaslıyoruz. 16 daha hem 27 hem de 22'den küçük olduğu için en sola geçiyor. Çünkü sıralama soldan sağa doğru küçükten büyüğe.
`[22,27,16,2,18,6]`  ---->  `[16,22,27,2,18,6]`

### 3. Sonra bir sonraki sayı olan yine 27'yi 2 ile kıyaslıyoruz. 2 sayısı solundaki tüm sayılardan küçük olduğu için en sola geçiyor. Çünkü sıralama soldan sağa doğru küçükten büyüğe.
`[16,22,27,2,18,6]`  ---->  `[2,16,22,27,18,6]`

### 4. Sonra bir sonraki sayı olan yine 27'yi 18 ile kıyaslıyoruz. 18 sayısı solundaki 22 ve 27 sayılarından daha küçük olduğu için onların soluna geçiyor. Çünkü sıralama soldan sağa doğru küçükten büyüğe.
`[2,16,22,27,18,6]`  ---->  `[2,16,18,22,27,6]` 

### 5. Son olarak, bir sonraki sayı olan yine 27'yi 6 ile kıyaslıyoruz. 6 sayısı solundaki 16,18, 22 ve 27 sayılarından daha küçük olduğu için onların soluna geçiyor. Çünkü sıralama soldan sağa doğru küçükten büyüğe.
`[2,16,18,22,27,6]`  ---->  `[2,6,16,18,22,27]`

### - Big-O = O(n²)
### - Average case kapsamına girer. Çünkü 18 sayısı ortadaki elemandır.
### +

# Soru 2 - [7,3,5,8,2,9,4,15,6] Selection Sort (İlk 4 basamak)

### 1. Öncelikle ilk elemanı minimum değer olarak referans alıp daha küçük değer var mı diye liste tek tek taranır. Bulunan en küçük değere sahip eleman ilk eleman ile yer değiştirir.
`[7,3,5,8,2,9,4,15,6]`  ---->  `[2,3,5,8,7,9,4,15,6]`

### 2. Sonra ikinci elemanı minimum değer olarak referans alıp daha küçük değer var mı diye liste yine tek tek taranır. Eğer yoksa aynen bırakılır.  
`[2,3,5,8,7,9,4,15,6]` ---->   `[2,3,5,8,7,9,4,15,6]`

### 3. Sonra üçüncü elemanı minimum değer olarak referans alıp daha küçük değer var mı diye liste yine tek tek taranır. Bulunan en küçük değere sahip eleman üçüncü eleman ile yer değiştirir. 
`[2,3,5,8,7,9,4,15,6]` ---->   `[2,3,4,8,7,9,5,15,6]`

### 4. Sonra dördüncü elemanı minimum değer olarak referans alıp daha küçük değer var mı diye liste yine tek tek taranır. Bulunan en küçük değere sahip eleman dördüncü eleman ile yer değiştirir. 
`[2,3,4,8,7,9,5,15,6]` ---->   `[2,3,4,5,7,9,8,15,6]`


# PROJE 2 - [16,21,11,8,12,22] Merge Sort

### 1. Öncelikle liste ortadan ikiye bölünür.
`[16,21,11,8,12,22]` ---->   `[16,21,11]` ve `[8,12,22]`

### 2. Sonra ayrılan parçalar tekli ve ikili parçalara ayrılır. 
`[16,21,11]` ----> `[16]` ve `[21,11]`

`[8,12,22]`  ---->  `[8,12]` ve `[22]`

### 3. İkili parçalar küçükten büyüğe sıralanır. 
`[16]` ve `[21,11]`  ----> `[16]` ve `[11,21]`

`[8,12]` ve `[22]`  ---->  `[8,12]` ve `[22]`

### 4. Sıralanan ikili parçalar tekli parçalar ile birleştirilerek küçükten büyüğe sıralanır.
`[16]` + `[11,21]` ----> `[11,16,21]`

`[8,12]` + `[22]` ---->  `[8,12,22]`

### 5. Son olarak, sıralanan üçlü parçalar birleştirilerek küçükten büyüğe sıralanır.
`[11,16,21]` + `[8,12,22]`  ---->  `[8,11,12,16,21,22]`

### - Big-O = O(nlogn)

# PROJE 3 - [7,5,1,8,3,6,0,9,4,2]  Binary Search Tree

![Binary Search Tree](https://github.com/handeerkovan/Algoritma_Odev_Proje_1-2-3/blob/main/images/binary_search_tree.png?raw=true)
