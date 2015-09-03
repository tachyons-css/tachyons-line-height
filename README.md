# tachyons-line-height
1.1.0

Performance based css module.

## Install
```
npm install --save-dev tachyons-line-height
```

or download the css on github and include in your project:

```
git clone git@github.com:mrmrs/tachyons-line-height
```

## The Code
```
/*

   LINE HEIGHT / LEADING

*/

.lh       { line-height: 1; }
.lh-title { line-height: 1.3; }
.lh-copy  { line-height: 1.6; }

@media screen and (min-width: 48em) {
  .lh-ns       { line-height: 1; }
  .lh-title-ns { line-height: 1.3; }
  .lh-copy-ns  { line-height: 1.6; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .lh-m       { line-height: 1; }
  .lh-title-m { line-height: 1.3; }
  .lh-copy-m  { line-height: 1.6; }
}

@media screen and (min-width: 64em) {
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

