Part1.1.: values added: (sum of num1 and num2)

Part1.2.: final result: (sum of num1 and num2)

Part1.3.：var has no block scope, so it can easily unintendedly become a global variable; if declare in function, it become a function variable. This would lead to confusions as it pierce through if and loop blocks and passes the value, and can lead to more issues like name conflicts. By avoiding var and using let instead we clarify the scope of local variables and thus can avoid this confusion.

Part1.4.: values added: (sum of num1 and num2)

Part1.5.: an error will occur: ReferenceError: result is not defined. This error occurs since result was defined as a let variable in the block, and now we're trying to access it out of the block, it's out of the scope of the result variable.

Part1.6.: an error will occur: TypeError: Assignment to constant variable. This error occurs as we are reassigning value for const variable result, which is not permitted.

part1.7.: an error will occur: ReferenceError: result is not defined. This error occurs since result was defined as a const variable (which also has block scope) in the block, and we are out of its scope when trying to access it out of the block.