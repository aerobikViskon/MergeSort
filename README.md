# Merge Sort - Proje 2

## Verilen Dizi:
[16, 21, 11, 8, 12, 22]

## Merge Sort Aşamaları:

1. **İlk Bölme (Divide):**  
   Dizi ikiye bölünür.  
   [16, 21, 11] ve [8, 12, 22]

2. **İlk Alt Bölme (Divide):**  
   İlk alt dizi [16, 21, 11] ikiye bölünür:  
   [16] ve [21, 11]  
   - [21, 11] tekrar ikiye bölünür:  
     [21] ve [11]

3. **Birleştirme (Merge):**  
   - [21] ve [11] sıralanarak birleştirilir: [11, 21]
   - [16] ve [11, 21] sıralanarak birleştirilir: [11, 16, 21]

4. **İkinci Alt Bölme (Divide):**  
   İkinci alt dizi [8, 12, 22] ikiye bölünür:  
   [8] ve [12, 22]  
   - [12, 22] tekrar ikiye bölünür:  
     [12] ve [22]

5. **Birleştirme (Merge):**  
   - [12] ve [22] sıralanarak birleştirilir: [12, 22]
   - [8] ve [12, 22] sıralanarak birleştirilir: [8, 12, 22]

6. **Son Birleştirme (Merge):**  
   Son olarak [11, 16, 21] ve [8, 12, 22] sıralanarak birleştirilir:  
   [8, 11, 12, 16, 21, 22]

## Sonuç:
[8, 11, 12, 16, 21, 22]

## Big-O Gösterimi:
- Merge Sort'un en kötü, en iyi ve ortalama zaman karmaşıklığı O(n log n)'dir.  
- Bu, her bir bölme adımının O(log n) karmaşıklığına sahip olduğu ve her bir birleştirme adımının O(n) karmaşıklığına sahip olduğu için toplamda O(n log n) karmaşıklığı elde edilir.
