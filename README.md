# Language Speed Test

Looking at various Speed Tests from around the internet to find the best performing languages.

We will be only evaluating languages from the top 20 languages listed on the [TIOBE Index](https://www.tiobe.com/tiobe-index/)

| Top 1 - 10             | Top 11 - 20              |
|------------------------|--------------------------|
| 1) Python              | 11) Delphi/Object Pascal |
| 2) C++                 | 12) PHP                  |
| 3) Java                | 13) MATLAB**             |
| 4) C                   | 14) Rust                 |
| 5) C# (.NET)           | 15) Swift                |
| 6) JavaScript          | 16) Scratch**            |
| 7) Go                  | 17) Ruby                 |
| 8) FORTRAN             | 18) R**                  |
| 9) Visual Basic (.NET) | 19) Assembly Language    |
| 10) SQL**              | 20) Kotlin               |

** These languages either do not compile to a executable or run inside of another application so cannot be evaluated for performance tests.

## Performance Tests

There are a lot of different performance tests/results on the web.  This repository will try to bring the results into one place for the top used languages.

- [Münchausen Numbers](https://github.com/jabbalaci/SpeedTests) - [Details Below](#münchausen-numbers)
- [Calulating PI (π) by Hand - 100,000,000 Times](https://niklas-heer.github.io/speed-comparison) - [Details Below](#calculating-pi-π-by-hand)


## Münchausen Numbers
This GitHub Repository https://github.com/jabbalaci/SpeedTests compares different programs and how fast they can calculate Münchausen number.

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

## Calculating PI (π) by Hand

This GitHub Repository https://niklas-heer.github.io/speed-comparison compares several languages and the speed of calculating PI by hand.

| Language         | Compiler/Enhancements | Runtime (sec)  |
|------------------|-----------------------|----------------|
| **Python**       |                       |                |
|                  | Python 3              | 5.84           |
|                  | Nim Compiler          | 0.068          |
|                  | pypy3                 | 0.067          |
| **C++**          |                       |                |
|                  | g++ (GCC)             | 0.068          |
|                  | clang++               | 0.068          |
| **Java**         |                       |                |
|                  | JDK (19)              | 0.199          |
| **C**            |                       |                |
|                  | gcc                   | 0.068          |
|                  | clang                 | 0.069          |
| **C#**           |                       |                |
|                  | .NET 7                | 0.209          |
| **JavaScript**   |                       |                |
|                  | node.js 18            | 0.305          |
| **Go**           |                       |                |
|                  | go                    | 0.136          |
| **FORTRAN**      |                       |                |
|                  | gfortran              | 0.068          |
| **Visual Basic** | Not Evaluated         |                |
| **SQL**          | Not Evaluated         |                |
| **Delphi**       | Not Evaluated         |                |
| **PHP**          |                       |                |
|                  | php                   | 2.911          |
| **MATLAB**       | Not Evaluated         |                |
| **Rust**         |                       |                |
|                  | cargo                 | 0.693          |
| **Swift**        |                       |                |
|                  | swiftc                | 0.141          |
| **Scratch**      | Not Evaluated         |                |
| **Ruby**         |                       |                |
|                  | ruby                  | 12.782         |
| **R**            |                       |                |
|                  | 4.2                   | 0.783          |
| **Assembly**     | Not Evaluated         |                |
| **Kotlin**       | Not Evaluated         |                |


