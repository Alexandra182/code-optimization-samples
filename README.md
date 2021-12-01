# code-optimization-samples

- **InvOrderBits.cpp** 

  Reverses the bit order of a 64 bits number. Optimized using OpenMP.
  ```
  g++ -std=c++14 InvOrderBits.cpp -fopenmp -O3 -o InvOrderBits
  ./InvOrderBits
  ```

- **L1.cpp** 

  L1 distance calculation (the sum of the absolute values). Optimized using OpenMP.
  ```
  g++ -std=c++14 L1.cpp -fopenmp -O3 -o l1
  ./l1
  ```
  
- **L2.cpp** 

  L2 distance calculation (the square root of the sum of the squared values). Optimized using OpenMP and Intel Intrinsics.
  ```
  g++ -std=c++14 L2.cpp -fopenmp -O3 -march=corei7-avx -o l2  
  ./l2
  ```
