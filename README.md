Proje 1

[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

Average case: Aradığımız sayının ortada olması
Worst case: Aradığımız sayının sonda olması
Best case: Aradığımız sayının dizinin en başında olması.

Cevap:

1. adım 22, 27, 16, 2, 18, 6
2. adım 16, 22, 27, 2, 18, 6
3. adım 2, 16, 22, 27, 18, 6
4. adım 2, 16, 18, 22,  27, 6
5. adım 2, 6, 16, 18, 22, 27

Big-O Gösterimi:
Worst Case -> O(n**2)
Average Case -> O(n**2)
Best Case O(n)

-> 18 average case kapsamına giriyor.

Proje 2

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

Cevap:

**Dizi:** `[16, 21, 11, 8, 12, 22]`

**Merge Sort Aşamaları:**
* **Adım 1 (Bölme):** `[16, 21, 11]` ve `[8, 12, 22]`
* **Adım 2 (Bölme):** `[16]`, `[21, 11]` ve `[8]`, `[12, 22]`
* **Adım 3 (Bölme):** `[16]`, `[21]`, `[11]`, `[8]`, `[12]`, `[22]`
* **Adım 4 (Birleştirme):** `[16]`, `[11, 21]` ve `[8]`, `[12, 22]`
* **Adım 5 (Birleştirme):** `[11, 16, 21]` ve `[8, 12, 22]`
* **Adım 6 (Birleştirme):** `[8, 11, 12, 16, 21, 22]`

**Big-O Gösterimi:**
* **Best Case:** $O(n \log n)$
* **Average Case:** $O(n \log n)$
* **Worst Case:** $O(n \log n)$

Proje 3

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

**Dizi:** `[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]`

**Binary Search Tree Aşamaları:**

* **7:** Root (kök) düğümdür.
* **5:** 7'den küçük olduğu için 7'nin solunda bulunur.
* **1:** 7 ve 5'ten küçük olduğu için 5'in solunda bulunur.
* **8:** 7'den büyük olduğu için 7'nin sağında bulunur.
* **3:** 7 ve 5'ten küçük, 1'den büyük olduğu için 1'in sağında bulunur.
* **6:** 7'den küçük, 5'ten büyük olduğu için 5'in sağında bulunur.
* **0:** 7, 5 ve 1'den küçük olduğu için 1'in solunda bulunur.
* **9:** 7 ve 8'den büyük olduğu için 8'in sağında bulunur.
* **4:** 7 ve 5'ten küçük, 1 ve 3'ten büyük olduğu için 3'ün sağında bulunur.
* **2:** 7 ve 5'ten küçük, 1'den büyük, 3'ten küçük olduğu için 3'ün solunda bulunur.
