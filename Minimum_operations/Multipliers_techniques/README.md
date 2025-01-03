
# here you are in multiplier advanced methods

## requirements 

- additions
- substractions

somewhere else in this repository
(maybe WIP or not finished yet)
 else you can use the default way (the simplest one)

## known algorithms

| **Algorithm**                | **exact Complexity**          | ** Simplified notation \( O() \)**     | **aproximations**           |
|-------------------------------|--------------------------------|--------------------------------------|-----------------------------|
| **naive method/defalut**              | O(n<sup>2</sup>)                  | O(n<sup>2</sup>)                 | = n<sup>2</sup>  |
| **Karatsuba**                  | O(n<sup>log<sub>2</sub>3<sup>})        | \( O(n^{1.585}) \)                   | ≈ n<sup>1.585</sup>  |
| **Toom-Cook (Toom-3)**         | \( O(n^{\log_3 5}) \)         | \( O(n^{1.464}) \)                   | ≈ n<sup>1.464</sup>  |
| **Schönhage-Strassen (FFT)**   | \( O(n \log n \log \log n) \) | \( O(n \log n) \)                    | ≈ n\*log(n)\*log(log(n)) |
| **Fürer (theoretical optima)**  | \( O(n \log n) \)             | \( O(n \log n) \)                   | ≈ n*log(n)      |



<!--end page-->
