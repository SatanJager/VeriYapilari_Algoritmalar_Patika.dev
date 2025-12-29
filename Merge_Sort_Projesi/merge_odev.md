# Merge Sort Project
### Project 2

**Autor: Taylan Alp Mühür**

**1-**  **[16,21,11,8,12,22]** -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

*Cevap:*

[16,21,11,8,12,22]
Bölme (Divide):
[16,21,11] || [8,12,22]
[16] | [21,11] || [8] | [12,22]
[16] | [21] [11] || [8] | [12] [22]
Birleşme (Merge):
[16] | [11,21] || [8] | [12,22]
[11,16,21] || [8,12,22]

[8,11,12,16,21,22] 


Zaman karmaşıklığı: O(nlogn)

Bölme aşaması: logn
Birleşme aşaması: n
n * logn => O(nlogn)