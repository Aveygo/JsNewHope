## A Javascript implention of NewHope

This script was heavily relient on scottwn/PyNewHope and more of a play around/learning experience to quantum cryptography.
It has been tested and produces the same output as PyNewHope, given same seed and random noise.
Cant vouch for the 'quantum security' of this method, other than the 128 bit reference in the original [paper](https://eprint.iacr.org/2015/1092.pdf)

### TODO:
- [x] Double check for errors
- [x] Create a working example page
- [x] Triple check for errors

### Quick use
There's an example key exchange between Alice and Bob: testNewHope() and a benchmarking function: benchmark(n_rounds) inside NewHope.js
