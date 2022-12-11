# Binary-Search-Tree-Projesi
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
---> Root'u 6 olarak belirleyelim.

6'dan küçük değerler 6 nın soluna, 6 dan büyük değerler ise sağına yazılacak.


                6
               / \ 
             5     7   ---> 5, 6 dan büyük olduğundan 6 nın soluna, 7 ise 6dan büyük olduğu için sağına koyduk.
            /       \
          1          8  ---> 1, 5ten küçük olduğu için 5 in soluna koyduk; 8, 7 den büyük olduğu için sağına koyduk.
         / \          \
        0   3          9 ---> 0, 5ten ve 1 den küçük olduğu için hep soldan ilerledik, 3 ise 1 den büyük olduğu için 1 in sağına koyduk. 9, 8 den büyük bu nedenle 8 in sağına koyduk.
           / \
          2   4          ---> 2, 3ten küçük dolayısıyla sol tarafa;İ 4, 3ten büyük bu yüzden sağ tarafa koyduk.
