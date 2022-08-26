# Insertion Sort Projesi

> #### **[22,27,16,2,18,6]** -> Insertion Sort

> 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
>> **start**  
>> [2, 27, 16, 22, 18 ,6]  
>> [2, 6, 16, 22, 18, 27]  
>> [2, 6, 16, 22, 18, 27]  
>> [2, 6, 16, 18, 22, 27]  
>> **end**

> 2. Big-O gösterimini yazınız.
>> O(n^2)
> 3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
>> Best Case: Hepsinin sıralanmış olması durumu, yine de hepsi tekrar tek tek kontrol edilmek zorunda, O(n^2)
>> Average Case: O(n^2)
>> Worst Case: O(n^2)
> 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? 
>> Linear Search için Average Case, Binary Search için Worst veya Best Case (çift sayıda dizi ortanın sağı veya solu alınmasına bağlı) 