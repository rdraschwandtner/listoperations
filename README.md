# listoperations
This package is enhancing Python's built-in list operations with artithmetic operations while preserving the structure of the lists.

Useage:
```Python
import arithmetic
a = [1,2,3,4,[5,6,7,8]]
b = [10,20,30,40,[50,60,70,80]]
c = arithmetic.listsum(a,b)
c
```
will result in
```Python
[11, 22, 33, 44, [55, 66, 77, 88]]
```

## Experiments
Data driven decisions for implementation. E.g. runtime behavior on Kaggle.

Experiments can be found under experiments/ .


## Testcases
Tests in testcases/ need to run through for commits.

## Next steps
- Scalar as input argument
- Unary arithmetic operations
- Comparison operators
- Handle tuples
- Handle Series and DataFrames inside of lists
- Boolean operators
