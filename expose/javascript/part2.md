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

Part2.13.:
A. '3'+2 = '32', as + operator performs string concatenation after a string, and therefore converted the 2 into a string for the concatenation.
B. '3'-2 = 1, as - operator only works for numerical minus, thus converted '3' into number 3.
C. 3+null = 3, as null is the equivalence of number 0.
D. '3'+null = '3null', as null has been autoconverted into its string equivalence "null" as + operator is performing string concatenation.
E. true+3 = 4, as the numerical equivalence of true is 1.
F. false+null = 0, as the numerical equivalence of both false and null are 0.
G. '3'+undefined = '3undefined' s + operator performs string concatenation after string '3' and therefore converted undefined into its string equivalence 'undefined' for concatenation.
H. '3'-undefined = NaN (not a number), as - operator only works for numerical minus, and there isn't a meaningful numerical equivalence for undefined, which results in NaN (not a number).

Part2.14.:
A. '2'>1 is true, which '2' is converted into number 2.
B. '2'<'12' is false, as in string (lexicographic) comparison, '2' comes after '1', so '2' is after, or larger, than '12'.
C. 2=='2' is true, as == performs type casting and '2' is casted as numerical 2.
D. 2==='2' is false, as === don't perform type casting and thus 2 and '2' are in different types.
E. true==2 is false, as the numerical equivalence of true is 1.
F. true===Boolean(2) is true, as Boolean(2) converts 2 to true as 2 is a non-zero number.

Part2.15.: == performs type casting when comparing values of different type, while === does not, which counts in type difference in comparison. Therefore, it's possible for == to return true when comparing values of different type, but impossible for === as it strictly requires identical type.