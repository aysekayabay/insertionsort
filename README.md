# insertionsort
Proje 1
[22,27,16,2,18,6] -> Insertion Sort
Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız.
Time Complexity: O(n^2)
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? => Average Case

[22*, 27*, 16, 2, 18, 6] 

[16*, 22*, 27*, 2, 18, 6]

[2*, 16*, 22*, 27*, 18, 6]

[2*, 16*, 18*, 22*, 27*, 6] 

[2*, 6*, 16*, 18*, 22*, 27*] 


[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[3*, 7*, 5, 8, 2, 9, 4, 15, 6]

[3*, 5*, 7*, 8, 2, 9, 4, 15, 6]

[3*, 5*, 7*, 8*, 2, 9, 4, 15, 6]

[2*, 3*, 5*, 7*, 8*, 9, 4, 15, 6]

[2*, 3*, 5*, 7*, 8*, 9*, 4, 15, 6]

[2*, 3*, 4*, 5*, 7*, 8*, 9*, 15, 6]

[2*, 3*, 4*, 5*, 7*, 8*, 9*, 15*, 6]

[2*, 3*, 4*, 5*, 6*, 7*, 8*, 9*, 15*]
