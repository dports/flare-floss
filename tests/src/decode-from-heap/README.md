# FLOSS test: test-decode-from-headp

Purpose: Demonstrate extraction of strings decoded from an allocated heap buffer.
Decoding algorithm: single byte xor
Input buffer location: heap
Output buffer location: stack

Decoded strings:
hello world

Source files:
test-decode-from-heap.c

Build instructions (Windows):
eg. cl.exe test-decode-from-heap.c /Fetest-decode-from-heap.exe

Build instructions (Linux):
eg. clang test-decode-from-heap.c -o test-decode-from-heap

Build instructions (Cross compile for Windows on Linux):
i686-w64-mingw32-clang test-decode-from-heap.c -o test-decode-from-heap.exe