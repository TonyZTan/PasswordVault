# PasswordVault
A simple python-based password manager that encrypts login credentials using a key derived from a master username, password, and salt.

Written in the summer of 2014.

## Warning
Even though this application makes use of common cryptographic algorithms such as AES-256 and SHA2, the security of this implementation has not been audited or verified and may contain security problems or otherwise be insecure for real-world use.

All login credentials are encrypted and stored locally on the user's computer.

Please do not rely on this program to protect highly-sensitive information.

##License
The MIT License (MIT)

Copyright (c) 2015 [Tony Zhaocheng Tan](https://tonytan.io/about) <<tony@tonytan.io>>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
