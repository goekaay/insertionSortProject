# insertionSortProject

# Insertion Sort Aşamaları

Yer değiştiren elemanlar işaretlenmiştir.

1. [**22**,27,16,**2**,18,6]
2. [2,**6**,16,22,18,**27**]
3. [2,6,16,**18**,**22**,27]

# Big-O Gösterimi

| (n*(n+1)/2) = (n^2 + n)/2 = n^2/2 + n/2 |
| --------------------------------------- |
|                                         |

O(n^2)

# Time Complexity

### Average Case: 

Aradığımız sayının (18) ortada olması:			[2,6,16,18,22,27]

### Worst Case:

Aradığımız sayının (2) sonda olması:				[27,22,18,16,6,2]

### Best Case:

Aradığımız sayının (2) başta olması:				[2,6,16,18,22,27]



# Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?

18' in ortanca değer olduğunu yukarıdaki sıralamalarda gördük. Bu yüzden average case.



# **[7,3,5,8,2,9,4,15,6**] dizisinin Insertion Sort'a göre ilk 4 adımı

1. [**2**,3,5,8,**7**,9,4,15,6]
2. [2,3,**4**,8,7,9,**5**,15,6]
3. [2,3,4,**5**,7,9,**8**,15,6]
4. [2,3,4,5,**6**,9,8,15,**7**]

[Patika.dev](https://www.patika.dev/tr)
