# Square Code

The best alternative to QR Code and DataMatrix.

## Comparison

| Aspect                                       | Square Code     | QR Code | DataMatrix
|----------------------------------------------|-----------------|---------|-----------
| Symetric                                     | ✅              | ❌     | ❌
| Human readable                               | ✅ (if colored) | ❌     | ❌
| Metadata size                                | 0               | ~69%    | ~68%
| Lost data restore                            | 75% any data    | 7-30% (except meta data) | 30% (ECC-200 only, except meta data)
| Size for "https://square.hyoo.ru/" (Max ECC) | 32x32           | 27x27   | 20x20
