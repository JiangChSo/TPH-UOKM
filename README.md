# TPH-UOKM

This repository contains a reference implementation of **TPH-UOKM: Threshold Password-Hardening Updatable Oblivious Key Management**.

> ⚠ **WARNING:** This is an academic prototype and should not be used in applications without code review.

## How to Run

### Dependencies

Ensure the following dependencies are installed:

- [Crypto++ 8.6.0](https://www.cryptopp.com/)
- [PBC 0.5.14](https://crypto.stanford.edu/pbc/)
- [NTL 11.5.1](https://libntl.org/)

### Running the Repo

1. Clone this repository and navigate to the project directory.
2. Ensure `g++` and `cmake` are installed on your Linux system.
3. Build and run the experiment locally:

   ```sh
   cd Build
   cmake ..
   make
   ./build < ../Param/a.param
