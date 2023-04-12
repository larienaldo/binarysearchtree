# binarysearchtree

##Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

1.adım: Root'u 7 olarak seçtiğimizde;
5 için ; 7>5 olduğu için 7 nin solunda olur.
1; 7>1 olduğu için 7 nin solunda olur. 5>1 olduğu için 5'in soluna gelir.
8; 8>7 olduğu için 7'nin sağında olur.
3; 7>3 oludğu için 7'nin solunda olur. 3>1 olduğu için 3 1'in sağına gelir.
6; 7>6 olduğu için 7 nin solunda olur. 6>5 oldğu için 5'in sağına gelir.
0; 7>0 olduğu için 7 nin solunda olur. 1'den küçük olduğu için 1'in soluna gelir.
9; 9>7 olduğu için 7'nin sağında olur. 9>8 olduğu için 8'in sağına gelir.
4; 7>4 olduğu için 7 nin solunda olur. 4>3 olduğu için 3'ün sağına gelir.
2; 7>2 olduğu için 7 nin solunda olur. 3>2 olduğu için 3'ün sağına gelir.
           
                                        [7]
                                    |        |
                          [5]                     [8]
                       |       |                       |
                                                       [9]  
                     [1]        [6] 
               
                 |        |
                [0]      [3]  
                
                       |     |
                    [2]       [4]
