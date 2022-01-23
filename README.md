# Numsectorlisp
Numsectorlisp is a library for [SectorLISP](https://github.com/jart/sectorlisp),
for scalar, vector, and matrix multiplication of fixed-point numbers.
The number of bits for the fractional part and the decimal part can be easily configured.
The default setting implements 16-bit fixed-point numbers with 12 bits for the fractional part,
3 bits for the integer part, and 1 bit for the sign.
Instructions for configuring the bit sizes are available inside the source code.

An in-depth explanation of the implementation details are available in my blog post,
[Building a Neural Network in Pure Lisp Without Built-In Numbers Using Only Atoms and Lists](https://woodrush.github.io/blog/posts/2022-01-16-neural-networks-in-pure-lisp.html).

Examples uses of numsectorlisp are available in these projects:

- [A Neural Network written in SectorLISP](https://github.com/woodrush/sectorlisp-nn), from [Building a Neural Network in Pure Lisp Without Built-In Numbers Using Only Atoms and Lists](https://woodrush.github.io/blog/posts/2022-01-16-neural-networks-in-pure-lisp.html)
- [Mandelbrot set plotter](https://github.com/woodrush/sectorlisp-examples/blob/main/lisp/mandelbrot.lisp), from [sectorlisp-examples](https://github.com/woodrush/sectorlisp-examples)
