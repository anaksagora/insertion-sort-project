# insertion-sort-project
Patika Academy Introduction To Data Analysis
Proje 1
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.
.



[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Çözüm 1 
[22,27,16,2,18,6] İlk elemanın sıralı olduğu varsayılarak ikinci eleman birinci elemanla karşılaştırılarak birinci elemandan büyükse birinci elemanın sağına, küçükse soluna yazılır
[22,27,16,2,18,6] Üçüncü eleman ilk iki elamanla karşılaştırılarak doğru konuma yazılır.
[16,22,27,2,18,6] Dördüncü eleman ilk üç elemanla karşılaştırılarak doğru konuma yazılır.
[2,16,22,27,18,6] Beşinci eleman ilk dört elemanla karşılaştırılarak doğru konuma yazılır.
[2,6,16,22,27,18] Altıncı eleman ilk beş elemanla karşılaştırılarak doğru konuma yazılır.
[2,6,16,18,22,27]


Big-O gösterimi O-(n²) ->   O-(36)

18 Sayısı average case kapsamındadır.

Çözüm 2 
[7,3,5,8,2,9,4,15,6] içerisinden en küçüğü bulunup en sola yazılır.
[2,7,3,5,8,9,4,15,6] içerisinden en küçüğü bulunup en sola yazılır.
[2,3,7,5,8,9,4,15,6] içerisinden en küçüğü bulunup en sola yazılır.
[2,3,4,7,5,8,9,15,6] içerisinden en küçüğü bulunup en sola yazılır.
[2,3,4,5,7,8,9,15,6] içerisinden en küçüğü bulunup en sola yazılır.
[2,3,4,5,6,7,8,9,15]  
/*
