# CSS FONT WEIGHT

  Mobile-first classes for css-font-weight.
  Set the desired css-font-weight on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-font-weight
```
or download the css on github and include in your project.

## File Size


## The Code
```
.fwn { font-weight: normal; }
.b   { font-weight: bold; }

.fw-light  { font-weight: lighter; }
.fw-bolder { font-weight: bolder; }

.fw1 { font-weight: 100; }
.fw2 { font-weight: 200; }
.fw3 { font-weight: 300; }
.fw4 { font-weight: 400; }
.fw5 { font-weight: 500; }
.fw6 { font-weight: 600; }
.fw7 { font-weight: 700; }
.fw8 { font-weight: 800; }
.fw9 { font-weight: 900; }

@include break(not-small) {
  .fwn-ns { font-weight: normal; }
  .b-ns   { font-weight: bold; }
  .fw-light-ns  { font-weight: lighter; }
  .fw-bolder-ns { font-weight: bolder; }
  .fw1-ns { font-weight: 100; }
  .fw2-ns { font-weight: 200; }
  .fw3-ns { font-weight: 300; }
  .fw4-ns { font-weight: 400; }
  .fw5-ns { font-weight: 500; }
  .fw6-ns { font-weight: 600; }
  .fw7-ns { font-weight: 700; }
  .fw8-ns { font-weight: 800; }
  .fw9-ns { font-weight: 900; }
}

@include break(medium) {
  .fwn-m { font-weight: normal; }
  .b-m   { font-weight: bold; }
  .fw-light-m  { font-weight: lighter; }
  .fw-bolder-m { font-weight: bolder; }
  .fw1-m { font-weight: 100; }
  .fw2-m { font-weight: 200; }
  .fw3-m { font-weight: 300; }
  .fw4-m { font-weight: 400; }
  .fw5-m { font-weight: 500; }
  .fw6-m { font-weight: 600; }
  .fw7-m { font-weight: 700; }
  .fw8-m { font-weight: 800; }
  .fw9-m { font-weight: 900; }

}

@include break(large) {
  .fwn-l { font-weight: normal; }
  .b-l  { font-weight: bold; }
  .fw-light-l  { font-weight: lighter; }
  .fw-bolder-l { font-weight: bolder; }
  .fw1-l { font-weight: 100; }
  .fw2-l { font-weight: 200; }
  .fw3-l { font-weight: 300; }
  .fw4-l { font-weight: 400; }
  .fw5-l { font-weight: 500; }
  .fw6-l { font-weight: 600; }
  .fw7-l { font-weight: 700; }
  .fw8-l { font-weight: 800; }
  .fw9-l { font-weight: 900; }
}

```

## Author

[http://mrmrs.cc](http://mrmrs.cc - Entire internet gateway to all things mrmrs)
[http://mrmrs.io](http://mrmrs.io - Open source projects)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

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

