# TACHYONS-LINE-HEIGHT

http://tachyons.io

Work In Progress. Pull requests and open issues welcome.

## Install
```
npm install --save-dev tachyons-line-height
```
or download the css on github and include in your project.

## The Code
```

/*

   LINE HEIGHT

*/

.lh       { line-height: 1; }
.lh-title { line-height: 1.3; }
.lh-copy  { line-height: 1.6; }

@include break(not-small) {
  .lh-ns       { line-height: 1; }
  .lh-title-ns { line-height: 1.3; }
  .lh-copy-ns  { line-height: 1.6; }
}

@include break(medium) {
  .lh-m       { line-height: 1; }
  .lh-title-m { line-height: 1.3; }
  .lh-copy-m  { line-height: 1.6; }
}

@include break(large) {
  .lh-l       { line-height: 1; }
  .lh-title-l { line-height: 1.3; }
  .lh-copy-l  { line-height: 1.6; }
}
```

## Author

[mrmrs](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

