# TYPE

  A Mobile-first type scale
  Set any element to the desired font-size for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install type.css --save-dev
```
or download the css on github and include in your project.

```

.f1    { font-size: 5rem; }
.f2    { font-size: 2.7rem; }
.f3    { font-size: 1.5rem; }
.f4    { font-size: 1rem; }
.f5    { font-size: 1rem; }
.f6,
.small { font-size: .85rem; }

@media screen and (min-width: 48em) {
  .f1-ns    { font-size: 5rem; }
  .f2-ns    { font-size: 2.7rem; }
  .f3-ns    { font-size: 1.5rem; }
  .f4-ns    { font-size: 1rem; }
  .f5-ns    { font-size: 1rem; }
  .f6-ns,
  .small-ns { font-size: .85rem; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .f1-m    { font-size: 5rem; }
  .f2-m    { font-size: 2.7rem; }
  .f3-m    { font-size: 1.5rem; }
  .f4-m    { font-size: 1rem; }
  .f5-m    { font-size: 1rem; }
  .f6-m,
  .small-m { font-size: .85rem; }
}

@media screen and (min-width: 64em)  {
  .f1-l    { font-size: 5rem; }
  .f2-l    { font-size: 2.7rem; }
  .f3-l    { font-size: 1.5rem; }
  .f4-l    { font-size: 1rem; }
  .f5-l    { font-size: 1rem; }
  .f6-l,
  .small-l { font-size: .85rem; }
}

```

# License

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

