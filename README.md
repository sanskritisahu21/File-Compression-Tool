# Huffman Compression
A minimal huffman compression program using C++ language.


## Executing program
```
g++ huffman-compression.cpp
[a.exe | ./a.out] -c|-dc [filename_to_be_compressed] 
(The order must be same: first: option to compress/decompress and then second: filename)
```
The file to be compressed will generate a file with extension '.abiz', which is the compressed version of the original one.

> **Note**: 
> - Compressing files other than ASCII based text files (e.g., audio (.mp3), video (.mp4), pdfs, document (.doc/.docx), etc.) can have little or no effect on the resulting size.
