#this is not the title but there are 58 trues and 38 falses
1. If replace = True, then when an object is picked out of the equation, the sample size remains the same.This allows a user to sample more objects than are available, as the object is able to be picked again due to it being replaced. When replace is false, the size decreases, for example, if there are 10 objects, if replace = False, the sample size would decrease to 9 
2. SuS <- (MyMatrix*1)

SuS
     [,1] [,2] [,3] [,4] [,5] [,6] [,7] [,8] [,9] [,10] [,11] [,12]
     
[1,]    1    1    1    1    1    1    1    1    1     1     1     1

[2,]    0    0    0    1    0    1    1    1    1     0     0     1

[3,]    0    0    1    1    1    1    0    0    1     1     1     1

[4,]    1    0    0    1    1    0    1    1    1     1     0     1

[5,]    1    1    0    1    1    1    0    1    0     1     0     0

[6,]    1    1    0    1    0    0    1    1    1     1     0     0

[7,]    1    0    1    0    1    0    0    1    1     1     1     0

[8,]    0    0    1    1    0    1    1    1    0 
    1     1     0
    
3. (Actually number 3 but i can't figure out how to edit this) rowSums(MyMatrix) == ncol(MyMatrix) states if the number of trues in a row equals the number of columns, telling whether it's true or false.

#section 2
1. 16 times
2. using sum(MyMatrix[,x] gives you the sum of column x; using colSums gives you the sum of all the columns
3. f 
4. 
4. 33 values but i counted on hand, i don't know if it's possible to count by a command
4. 