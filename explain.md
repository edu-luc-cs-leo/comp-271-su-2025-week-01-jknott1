# COMP-271-SU25 - Assignment for Week 01 - Explanation

## Use of `arr.lenth` as an index for the `temporary` array:

The length of the new array length constructed and to be assigned to `arr` should be one greater than the original. However, as java's arrays are immutable, a temporary container array variable is needed to create a new array with the desired value added on. This added value should be at the end of the array.  

The index of the elements of the arrays start at zero. So, to access the *n*th term of an array, the index *n - 1* should be used. That being said, to access the last element of an array `arr.length + 1` long, the index `arr.length + 1 - 1` or `arr.length` is needed to access that last element.
