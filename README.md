JAWS, a Windows Multi-Functions software relying on API calls on remote SHIFT nodes for commands

Just Another Wallet for Shift

Enjoy it

note: this is just an alpha version. Use it at your own risk

Uses only tls 1.2 to communicate to Secure Site

visual studio 2015 express source code attached.

![Alt text](./image.PNG?raw=true "Optional Title")


#### Building from source
Clone the repo on your hard disk, Open the file WALLISK.vbproj with Visual Studio 2015 or superior, then go to menu "Build" >> Build Wallisk
you will find the compiled exe inside the bin/Release folder



### Installation

JAWS requires [Net framework 4.5](https://www.microsoft.com/it-it/download/details.aspx?id=30653) to run.
and has included in exe resources the [Json.NET library](https://github.com/JamesNK/Newtonsoft.Json) and [nuGet NBitcoin library](http://www.nuget.org/packages/NBitcoin/)
(as soon as you run the exe a Newtonsoft.Json.dll and NBitcoin.dll are automatically created in exe folder)

### Windows Binary

[download]: <./bin/Release/JAWS.exe?raw=true>
[Download already compiled Windows Binary] [download]

###  Credits
A special thank to gr33ndrag0n for his help in solving a TLS 1.2 issue when communicating with his node
https://github.com/Gr33nDrag0n69

A special thank to "ralfs" for helping me to find the right name for this piece of code




License
MIT

Copyright (c) 2017 corsaro1

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


Free Software, Hell Yeah!
