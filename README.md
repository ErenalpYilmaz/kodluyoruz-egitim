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

**Dizi:** `[16, 21, 11, 8, 12, 22]`[cite: 2]

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
