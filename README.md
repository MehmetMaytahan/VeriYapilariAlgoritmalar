Bu repository [Patika](https://app.patika.dev/) Veri Yapıları ve Algoritmalar eğitimi için hazırlamıştır ve İçerisinde Veri Yapıları ve Algoritmalar dersinin sorularını ve cevaplarını içeren bir adet README dosyası barındırıyor.

---

# _Soru_1_

<details close> 
<summary> Soru & Cevap </summary>

[22,27,16,2,18,6] -> Insertion Sort

- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  ```
  [22,27,16,2,18,6] -> (n)
  [2,27,16,22,18,6] -> (n-1)
  [2,6,16,22,18,27] -> (n-2)
  [2,6,16,18,22,27] -> (1)
  ```
- Big-O gösterimini yazınız.

  ```
  n + (n-1) + (n-2) + 1 = ?

  n.(n+1) / 2 = ?

  (n^2 + n) / 2 = ?

  O(n^2)

  ```

- Time Complexity:
  - **Average case** : Aradığımız sayının ortada olması.
    ```
    [2,6,16,18,22,27] = 16 - 18
    ```
  - **Worst case** : Aradığımız sayının sonda olması.
    ```
    [2,6,16,18,22,27] = 27
    ```
  - **Best case** : Aradığımız sayının dizinin en başında olması.
    ```
    [2,6,16,18,22,27] = 2
    ```
- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
    ```
    [2,6,16,-18-,22,27] = Average case
    ```

- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
    ```
    [7,3,5,8,2,9,4,15,6] -> (n)
    [2,3,5,8,7,9,4,15,6] -> (n-1)
    [2,3,4,8,7,9,5,15,6] -> (n-2)
    [2,3,4,5,7,9,8,15,6] -> (n-3)
    ```
</details>
