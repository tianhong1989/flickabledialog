# flickabledialog
	
This dialog can flick and make it easy to dismiss sensuously.
You can show your infromation to users with minimum stress.

## Download 

Gradle : 

```
compile 'com.tkurimura:flickabledialog:0.3.0'
```

## Require

Java7 and Android minimum API level (SDK) 11 (Andorid 3.0)

## Usage

```
FlickableDialog dialog = FlickableDialog.newInstance(R.layout.your_dialog_layout);
dialog.show(getSupportFragmentManager(),dialog.getClass().getSimpleName());

```
and you can override FlickableDialog with any additional function

## Sample 

![Flick](https://github.com/t-kurimura/flickabledialog/blob/master/sample_throw.gif)

![come back](https://github.com/t-kurimura/flickabledialog/blob/master/sample_back.gif)

## Liscense

```
The MIT License (MIT)
Copyright (c) 2016 Takahisa Kurimura

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

```