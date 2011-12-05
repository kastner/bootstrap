OSX Bootstrap
========================================================================

This is a little chef repo that I use for setting up a new mac. I'm
*very* lazy so most of the preferences are hardcoded in the
cookbooks. The result is that this sets up a machine the way I want,
which is quite possibly not how you want. I'll probably make it more
tunable later, but... lazy :D

How Do?
------------------------------------------------------------------------

* check out the repo
* copy `config/example.json` to `config/whatever.json`
* edit your json file to taste
* `rake converge[whatever]`

The MIT License
------------------------------------------------------------------------

Copyright (c) 2011 Ben Bleything <ben@bleything.net>

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY
KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE
WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.