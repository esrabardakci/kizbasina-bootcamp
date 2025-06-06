Binary Search Tree Projesi
Proje 3

1. [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

- **Yanıt**
  >**Root'tan büyük elemanlar sağ düğüme, küçük olanlar ise sol düğüme yerleştirilir, sonraki düğümler için de bu tekrar edilir.**
> Listedeki ilk eleman 7 root olarak belirlenir. 
> 5, 7'den küçüktür, sola alırız.

> 1 hem 7'den hem 5'ten küçüktür, 5'in soluna alırız.

> 8, 7'den büyüktür, 7'nin sağına alırız.

> 3 hem 7'den, hem 5'ten küçüktür, fakat 1'den büyüktür, 1'in sağına alırız.

> 6, 7'den küçük, 5'ten büyüktür, 5'in sağına alırız.

> 0, 7'den, 5'ten ve 1'den küçük, 1'in soluna alırız.

> 9, 7'den ve 8'den büyük, 8'in sağına alırız.

> 4, 7'den ve 5'ten küçük, 1'den ve 3'ten büyük, 3'ün sağına alırız.

> 2, 7'den ve 5'ten küçük, 1'den büyük, 3'ten ise küçüktür, 3'ün soluna alırız.

![BinaryTreeSearchPNG](https://github.com/esrabardakci/kizbasina-bootcamp/blob/main/PatikaDev-Cohorts/VeriYapilariveAlgoritmalar/img/BinaryTreeSearch.png)
