Part2.1.: At line 12, console.log(i) will successfully log the value of i (which is 3 in this call) as i is declared as var variable and thus has function scope instead of block scope.

Part2.2.: At line 13, console.log(discountedPrice) will successfully log the last assigned value for variable discountedPrice (which is 150 in this call) as discountedPrice is declared as var variable and thus has function scope, beyond its own block.

Part2.3.: At line 14, console.log(finalPrice) will successfully log the last assigned value for variable finalPrice (which is 150 in this call) as finalPrice is declared as var variable and thus has function scope, and we are still within the scope of finalPrice at this call.

Part2.4.: The function will return the discounted array (\[50,100,150\]) correctly as discounted is a var variable (array) and has function scope, thus we will still be in the scope of the variable when we are accessing it, and the return will be successful.

Part2.5: an error will occur: ReferenceError: i is not defined. This error occured as i is defined as a let variable and is defined in the loop block, and we are out of its scope when trying to assess it outside of the loop block.

Part2.6: an error will occur: ReferenceError: discountedPrice is not defined. This error occured as discountedPrice in defined as a let variable and is defined in the loop block, and we are out of its scope when trying to assess it outside of the loop block.

Part2.7.: At line 14, console.log(finalPrice) will successfully log the last assigned value for variable finalPrice (which is 150 in this call) as we are accessing the let variable finalPrice in the same block where it's declared.

Part2.8.: The function will return the discounted array (\[50,100,150\]) correctly as discounted is a let variable (array) but still has function scope as it's being defined in the function block, thus we will still be in the scope of the variable when we are accessing it, and the return will be successful.

Part2.9.: At line 11, an error will occur: ReferenceError: i is not defined. This error occured as i is defined as a let variable and is defined in the loop block, and we are out of its scope when trying to assess it outside of the loop block.

Part2.10.: At line 12, the console.log(length) will successfully log the last assigned length value (which is 3 in this call) as we are accessing the const variable length in the same block where it's declared.

Part2.11.: This function will successfully return the discounted array (\[50,100,150\]) without any error as it's declared as a const variable and we are accessing it within its own block. The const only remark that we can't reassign the array itself, but it doesn't limit what we can do to the elements of the array, so no error occurs while elements are being pushed to the array.

Part2.12.:
A. student.name
B. student['Grad Year']
C. student.greeting()
D. student['Favorite Teacher'].name
E. student.courseLoad[0]

