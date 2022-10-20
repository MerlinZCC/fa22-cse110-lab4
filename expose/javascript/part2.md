1. It will print 3, since var can be accessed anywhere inside the function it is defined in and in the for loop, it breaks when i incremented to 3 at line 6.
2. It will print 150, since  var can be accessed anywhere inside the function it is defined in and for the last iteration of the loop, at line 7 it will calculate the third price in discountPrices which is 300*(1-0.5) = 150
3. It will print 150, since for the last iteration of the loop, at line 8 it will calculate 150*100/100 = 150
4. It will returns [50, 100, 150], since the function iterates over the given prices[100, 200, 300] and push prices after applying the discount in the output array discounted.
5. Returns an error, since no reference "i" is defined within scope and variable "i" declared in the for block is only accessible inside
6. Returns an error, since no reference "discountedPrice" is defined within scope and variable "discountedPrice" declared in the for block is only accessible inside
7. It will print 150, since for the last iteration of the loop, at line 8 it will calculate 150*100/100 = 150
8. It will returns [50, 100, 150], since the function iterates over the given prices[100, 200, 300] and push prices after applying the discount in the output array discounted.
9. Returns an error, since no reference "i" is defined within scope and variable "i" declared in the for block is only accessible inside
10. It will print 3, since at line 4, length is a constant which is the size of the input prices
11. It will returns [50, 100, 150], since the function iterates over the given prices[100, 200, 300] and push prices after applying the discount in the output array discounted.
12. A. student.name
    B. student["Grad year"]
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. A. '32', since 2 map to the exact string representation '2' and then concatenation makes '32'
    B. 1, since string '3' converts to number 3, then 3-2=1.
    C. 3, since numeric coversion null becomes 0, 3+0 =3
    D. '3null', since null converts to string representation 'null' and then concatenation makes '3null'
    E. 4, since numeric coversion true becomes 1, 1+3=4
    F. 0, since numeric coversion false becomes 0 and null becomes 0 as well, 0+0=0
    G. '3undefined', since undefined converts to string representation 'undefined' and then concatenation makes '3undefined'
    H. NaN, since string '3' converts to number 3 and undefined becomes NaN in Numeric conversion, 3-NaN = NaN
14. A. true, string '2' becomes a number 2 > 1
    B. false, dictionary comparison, first char "2" is greater than the first char "1".
    C. true, string '2" becomes a number 2
    D. false, because the types are different
    E. false, true becomes 1 != 2
    F. true, boolean of 2 is true, which equals to true in values and type
15. A strict equality operator === checks the equality as well as the data types of the operands while the == operator does the type conversion of the operands before comparison

17.The result would be [ 2, 4, 6 ]. First we call function modifyArray with inoput array [ 1, 2, 3] and a call back function doSomething. Inside the function, it iterates through the length of the input array and pass in each array element into the callback function, doSomething, which will double the number. Then it will push each of resultant number into newArr and return the newArr, [ 2, 4, 6 ]

19.1 4 3 2