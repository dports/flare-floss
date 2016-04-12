# FLOSS test: test-decode-to-global

Purpose: Demonstrate extraction of strings decoded to a global buffer.
Decoding algorithm: single byte xor
Input buffer location: global
Output buffer location: global

Decoded strings:
hello world

Source files:
test-decode-to-global.c

Build instructions (Windows):
eg. cl.exe test-decode-to-global.c /Fetest-decode-to-global.exe

Build instructions (Linux):
eg. clang test-decode-to-global.c -o test-decode-to-global

Build instructions (Cross compile for Windows on Linux):
i686-w64-mingw32-clang test-decode-to-global.c -o test-decode-to-global.exe