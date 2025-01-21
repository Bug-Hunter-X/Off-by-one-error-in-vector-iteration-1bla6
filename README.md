# Off-by-One Error in Vector Iteration

This repository demonstrates a common off-by-one error in C++ when iterating over a `std::vector`.  The error occurs when the loop condition `i <= vec.size()` attempts to access an element at the index equal to the vector's size, which is one beyond the last valid index.