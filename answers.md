# CMPS 2200 Recitation 7
## Answers

**Name:** Ruoqin Ji


Place all written answers from `recitation-07.md` here for easier grading.



- **d.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt    |          1340           |        826        |  0.62
alice29.txt    |         1039367            |        676374        |  0.65
asyoulik.txt    |         876253            |        606448        |  0.69
grammar.lsp    |          26047           |        17356        |  0.67
fields.c    |         78050            |       56206         |  0.72

The ratio of Huffman coding cost to fixed-length coding cost is about 0.67. 


- **e.**
If evert character in the alphabet $\sum$ has the same frequency. The expected cost of a Huffman encoding should be about the same as the cost of fixed-length encoding. 
I test 3 files with same-frequency characters, the ratios of Huffman encoding to fixed-length are respectly 0.98, 0.85, 1. 
