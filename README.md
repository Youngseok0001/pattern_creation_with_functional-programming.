# Functional way to generate a pattern.

----
## Tasks
* generate the following 8 patterns

 ![](figures/image001.png)

----
## solution

* given any pattern, create functions that can,
    *   Transpose
    *   Flip Horizontally 
    *   Flip Vertically -- f(Transpose, Flip Horizontally) 
    *   create Mirror Image
```python
pattern = \
*....
.*...
..*..
...*.
....*
transpose(pattern) = \ 
*....
.*...
..*..
...*.
....*
Flip Horizontally(pattern) = \
....*
...*.
..*..
.*...
*....

Create Mirror(pattern) = \
*.......*
.*.....*.
..*...*..
...*.*...
....*....
...*.*...
..*...*..
.*.....*.
*.......*

comopse(Create Mirror,Create Mirror)(pattern) = \
*.......*.......*
.*.....*.*.....*.
..*...*...*...*..
...*.*.....*.*...
....*.......*....
...*.*.....*.*...
..*...*...*...*..
.*.....*.*.....*.
*.......*.......*
.*.....*.*.....*.
..*...*...*...*..
...*.*.....*.*...
....*.......*....
...*.*.....*.*...
..*...*...*...*..
.*.....*.*.....*.
*.......*.......*
```
---
## Inspired by

* Lecture by John Hughes [link](https://www.google.com)
* Learn You a Haskell [link](http://learnyouahaskell.com/chapters)


