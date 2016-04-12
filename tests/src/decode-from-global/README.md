# FLOSS test: test-decode-from-global

Purpose: Demonstrate extraction of strings decoded from a global buffer.
Decoding algorithm: single byte xor
Input buffer location: global
Output buffer location: global

Decoded strings:
hello world

Source files:
test-decode-from-global.c

Build instructions (Windows):
eg. cl.exe test-decode-from-global.c /Fetest-decode-from-global.exe

Build instructions (Linux):
eg. clang test-decode-from-global.c -o test-decode-from-global

Build instructions (Cross compile for Windows on Linux):
i686-w64-mingw32-clang test-decode-from-global.c -o test-decode-from-global.exe