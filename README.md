# PDF to Image Converter Using Golang

<a href="https://godoc.org/fyne.io/fyne" style="pointer-events: none;" target="_blank"><img src="https://img.shields.io/badge/go-documentation-blue.svg"></a>
<a href="https://goreportcard.com/report/github.com/Mindinventory/Golang-PDF-to-Image-Converter" style="pointer-events: none;" target="_blank"><img src="https://goreportcard.com/badge/github.com/Mindinventory/Golang-PDF-to-Image-Converter"></a>
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/mindinventory/Golang-PDF-to-Image-Converter/blob/master/LICENSE)

This project is meant to be an **support** for implementation of **PDF-to-IMAGES** conversion without any quality compromising. Our goal for the viewer is to understand the core principles that go behind the development of such a complex conversion model and the nuances of training the individual processes for conversion with same quality. Once the core principles are understood, the various parts of the conversion process can be available at any time for usage in any project.


## Contents
- [Contents](#contents)
- [Overview](#overview)
- [Quickstart](#quickstart)
- [PDF Sample](#pdf-sample)
- [Converted Image Sample](#converted-image-sample)
- [LICENSE](#license)
- [Let us know](#let-us-know)

## Overview

Those who have done conversions from PDF to IMAGES, this repo will be very beneficial for them, because it has no quality compromising and we can increase/decrease the quality as per our requirement:

1. You have a PDF file as an input which you want to convert in IMAGES.
2. Add your PDF file in **pdf** folder.
3. As soon as the conversion program runs the images will generate in **img** folder inside the folder having name same as PDF file name.
4. Whatever the number of pages in PDF file same number of images will generate inside the **img/{PDF_NAME}** folder.

Now let us elaborate the Basic setup steps.

## Quickstart

For those who just want to see converted images, follow the overview steps and run the following code (make sure you have installed the stable **go** in your system):

```bash
go get
go run main.go
```

## PDF Sample
<img src="https://i.ibb.co/Z63MTQk/pdf-to-img-Input.jpg" alt="pdf-input">
<object data="https://github.com/Mindinventory/golang-pdf-to-Image-converter/raw/main/pdf/sample.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://github.com/Mindinventory/golang-pdf-to-Image-converter/raw/main/pdf/sample.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://github.com/Mindinventory/golang-pdf-to-Image-converter/raw/main/pdf/sample.pdf">Download PDF</a>.</p>
    </embed>
</object>

## Converted Image Sample
<img src="https://i.ibb.co/WVbvn9n/pdf-to-img-output.jpg" alt="img-output">
<object data="https://github.com/Mindinventory/golang-pdf-to-Image-converter/raw/main/pdf/sample.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://github.com/Mindinventory/golang-pdf-to-Image-converter/raw/main/pdf/sample.pdf">
        <p>Get the image output <a href="https://github.com/Mindinventory/golang-pdf-to-Image-converter/raw/main/img/sample/">click here</a>.</p>
    </embed>
</object>

## LICENSE

Golang HTML to PDF Converter is [MIT-licensed](https://github.com/mindinventory/golang-pdf-to-Image-converter/blob/main/LICENSE)

## Let us know
We’d be really happy if you sent us links to your projects where you use our component. Just email to sales@mindinventory.com And do let us know if you have any questions or suggestion regarding our work.
