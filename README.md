# Heathkit ET-3400 Clone

This repository contains various programs and information related to [Jeff Tranter's clone of the Heathkit ET-3400](https://github.com/jefftranter/6800). The ET-3400 was a simple single board computer (SBC) trainer. It included a hex keypad and an LED display. Courses that taught about the use of the Motorola MC6800 family of processors were available.

## Hello World!
The first program here is a simple Hello World! program written in assembly langague. It was written using the [A68 Assembler](https://www.retrotechnology.com/restore/a68.html) originally written by William Colley and updated by Herb Johnson.

To use the program, you should use the DO F400 (`DF400`) command from the ET-3400 clone's keyboard to enter the FANTOM monitor. At the `MON>` command, type `L0` and then upload the hw6800.s file.

Once that is done, press reset and then use D 1000 (`D1000`) to execute the program. You should see the "Hello World!" message appear on the terminal. You must reset the machine to exit the loop it is put in after printing the message.

I use the minicom terminal program under Ubuntu and set delays between characters of 25 ms and between lines of 250 ms. I have not tinkered with the settings to speed things up and those values feel fairly conservative.

## Credit where credit is due...
Thanks to Jeff Tranter for developing this project and making it available. Also thanks to the people at Heathkit that made this and many other great hobby and educational products availabe.

## And the fine print...
The licenses and copyrights for some of this material may be held by others and subject to various terms and conditions. I have tried to recognize those involved and have left any notices or attribution in place with the files used.

This material is intended for personal use for educational and hobby purposes only. Any material shared is shared in the belief that it falls into the category of "fair use". Any material will be removed at the request of the copyright holder or those holding other rights to it.

To the extent applicable, any original work herein is:

Copyright 2022 by James McClanahan and made available under the terms of The MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
