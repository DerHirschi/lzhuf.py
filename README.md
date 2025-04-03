# lzhuf.py
A Python implementation of the LZHUF compression algorithm, ported from the C version at ARSFI/Winlink-Compression. Supports encoding and decoding data using a binary search tree and Huffman coding. Ideal for retro computing, ASCII art compression, or experimental projects.

# LZHUF.py - A Python implementation of the LZHUF algorithm

This project is a Python port of the LZHUF compression algorithm, originally written in C and available at [ARSFI/Winlink-Compression](https://github.com/ARSFI/Winlink-Compression). The algorithm combines LZSS compression with Huffman coding and has been adapted and optimized with support from Grok 3-beta (xAI).

## Features

- **Compression**: Encoding input data (text, binary data) into a compressed format.
- **Decompression**: Reverting to the original data.
- **Robustness**: Contains protection mechanisms such as maximum iteration limits and buffer checks.
- **Application areas**: Retro-computing, ASCII art compression, or experimental data processing.

## Installation

Since it's a single Python file, no additional dependencies are required. Simply download the `lzhuf.py` file and copy it to your project directory.

### Requirements
- Python 3.x (tested with Python 3.8+)
