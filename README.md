# Kaitai Struct: runtime library for Python

This library implements Kaitai Struct API for Python.

[Kaitai Struct](http://kaitai.io) is a declarative language used for
describe various binary data structures, laid out in files or in memory:
i.e. binary file formats, network stream packet formats, etc.

It is similar to Python's [construct] and [Construct3], but it is
language-agnostic. The format description is done in YAML-based .ksy
format, which then can be compiled into a wide range of target languages.

[construct]: https://pypi.python.org/pypi/construct
[Construct3]: http://tomerfiliba.com/blog/Survey-of-Construct3/

Further reading:

* [About Kaitai Struct](http://kaitai.io/)
* [About API implemented in this library](http://doc.kaitai.io/stream_api.html)
* [Python-specific notes](http://doc.kaitai.io/lang_python.html)

## Installing

### Using `requirements.txt`

If you want to use Kaitai Struct runtime in your project and you use
`requirements.txt` to manage your dependencies, just add the following
line to it:

```
kaitaistruct
```

and then run `pip install -r requirements.txt` to update all your
dependencies.

### Using `pip` directly

You can use

```shell
pip install kaitaistruct
```

to install the package manually using `pip` Python package manager.

## Licensing

Copyright 2015-2017 Kaitai Project: MIT license

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
