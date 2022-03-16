
# kidRSA

## Description

Hmmm, is this a part of the RSAF in Singapore?

- a = 5
- b = 7
- a1 = 3
- b1 = 4

Whats the value of n to the nearest integer? `FLAG{number}`

## Solution

Basic Math, can use Python or calculator

- M = a* b-1 = 34
- e = a1* M + a = 107
- d = b1 * M + b = 143
- n = (e*d) / M = 450.02941176470586 = 450(nearest int)

`FLAG{450}`
