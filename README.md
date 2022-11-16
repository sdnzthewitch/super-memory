# super-memory


[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.


[22,27,16,2,18,6] -> Dizinin ilk elemanını sıralanmış eleman j olarak seçiyoruz.
[22,27,16,2,18,6] -> Dizinin sıralanmamış x elemalarıyla j > x karşılaştırmasını yapıyoruz.( 22 < 27 ancak 22>16 ,16 ilk başa geçer)
[16,22,27,2,18,6] -> İkinci sırada yaptığımız işlemi tekrar ederiz. İlk eleman olan 16'dır. ( 16 < 22,27 ancak 16 > 2 , 2 başa geçer.)
[2,16,22,27,18,6] -> Geriye kalan sıralanmamış eleman 18 < 22 den küçüktür. 22 'nin soluna geçer.
[2,16,18,22,27,6] -> Son kalan sıralanmamış eleman 6 <22 den küçüktür ancak işlem devam etmektedir. 6 < 16,18'dir .6 16'nın soluna geçer.
[2,6,16,18,22,27] -> Dizinin küçükten büyüğe sıralanmış hali.

Big-O gösterimi -> O(n^2)
Dizi sıralandıktan sonra 18 sayısı, dizinin ortasında bulunduğundan dolayı average case kapsamına girer.


[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6] -> Dizinin ilk elemanını en küçük eleman olarak seçiyoruz.
[3,7,5,8,2,9,4,15,6] -> Dizinin (ikinci elemanı < en küçük eleman) olduğu için başa alıyoruz.
[3,5,7,8,2,9,4,15,6] -> Dizinin 3. elemanı olan 5, (5 > 7 ) 5 7'nin soluna geçer ancak 5 > 3 tür. 2.sırada kalır.
[2,3,5,7,8,9,4,15,6] -> Dizinin 4.elemanı olan 8 sıralanmış sayılardan büyüktür.8 sayısını atlarız. 2 sayısı kendinden önce gelen sayılardan küçüktür. İlk sıraya geçer.

Dizideki her eleman tek tek incelenir ve kendinden önceki ile karşılaştırılır. Sıralama böyle devam eder.

www.patika.dev

