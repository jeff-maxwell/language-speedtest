# Language Speed Test

Looking at various Speed Tests from around the internet to find the best performing languages.

We will be only evaluating languages from the top 20 languages listed on the [TIOBE Index](https://www.tiobe.com/tiobe-index/)

1. Python
2. C++
3. Java
4. C
5. C# (.NET)
6. JavaScript
7. Go
8. FORTRAN
9. Visual Basic (.NET)
10. SQL**
11. Delphi/Object Pascal
12. PHP
13. MATLAB**
14. Rust
15. Swift
16. Scratch**
17. Ruby
18. R**
19. Assembly Language
20. Kotlin

** These languages either do not compile to a executable or run inside of another application so cannot be evaluated for performance tests.

## Performance Tests

There are a lot of different performance tests/results on the web.  This repository will try to bring the results into one place for the top used languages.

- [Münchausen Numbers](https://github.com/jabbalaci/SpeedTests) - [Details Below](#münchausen-numbers)


## Münchausen Numbers
A [Münchausen number](https://en.wikipedia.org/wiki/Perfect_digit-to-digit_invariant)
is a number equal to the sum of its digits raised to each digit's power.

For instance, 3435 is a Münchausen number because
3<sup>3</sup>+4<sup>4</sup>+3<sup>3</sup>+5<sup>5</sup> = 3435.

0<sup>0</sup> is not well-defined, thus we'll consider 0<sup>0</sup>=0.
In this case there are four Münchausen numbers: 0, 1, 3435, and 438579088.

| Language         | Compiler/Enhancements | Runtime (sec)  |
|------------------|-----------------------|----------------|
| **Python**       |                       |                |
|                  | Python 3              | 257.15 ± 1.472 |
|                  | mypyc                 | 80.481 ± 0.574 |
|                  | Nim Compiler          | 46.772 ± 0.203 |
|                  | Rust                  | 40.263 ± 1.152 |
|                  | pypy3                 | 20.05 ± 0.019  |
|                  | Numba Compiler        | 5.526 ± 0.435  |
|                  | Codon Compiler        | 5.369 ± 0.006  |
| **C++**          |                       |                |
|                  | g++ (GCC)             | 3.849 ± 0.012  |
|                  | clang++               | 2.827 ± 0.015  |
| **Java**         |                       |                |
|                  | JDK (21)              | 5.003 ± 0.002  |
| **C**            |                       |                |
|                  | gcc                   | 3.892 ± 0.001  |
|                  | clang                 | 2.672 ± 0.001  |
| **C#**           |                       |                |
|                  | .NET 8                | 5.614 ± 0.097  |
| **JavaScript**   |                       |                |
|                  | node.js               | 6.819 ± 0.001  |
| **Go**           |                       |                |
|                  |                       | 3.5 ± 0.045    |
| **FORTRAN**      |                       |                |
|                  | gfortran              | 3.884 ± 0.054  |
| **Visual Basic** | Not Evaluated         |                |
| **SQL**          | Not Evaluated         |                |
| **Delphi**       | Not Evaluated         |                |
| **PHP**          |                       |                |
|                  | php                   | 181.492 ± 0.536|
| **MATLAB**       | Not Evaluated         |                |
| **Rust**         |                       |                |
|                  | cargo                 | 2.936 ± 0.078  |
| **Swift**        |                       |                |
|                  | swiftc                | 3.335 ± 0.004  |
| **Scratch**      | Not Evaluated         |                |
| **Ruby**         |                       |                |
|                  | ruby --jit            | 75.863 ± 1.174 |
| **R**            | Not Evaluated         |                |
| **Assembly**     | Not Evaluated         |                |
| **Kotlin**       |                       |                |
|                  | kotlinc               | 5.092 ± 0.004  |