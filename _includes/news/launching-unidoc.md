Today we are releasing [UniDoc](http://unidoc.io) version 1.0, a comprehensive open source PDF toolkit written in [Go](https://golang.org).

## Background

At [FoxyUtils](https://foxyutils.com) we have been using various libraries for PDF manipulation
over the years and never been completely happy with what we have used. In the last couple of years we
have been migrating our code-base to [Golang](https://golang.org) and have completed porting of our
existing python code. In order to use the same libraries as used in python we had to to shell out and call
external APIs. As a result we have been developing a PDF toolkit in Go and
we are pleased to announce that our baby has been born and is ready for the prime time. [FoxyUtils.com](https://foxyutils.com) has been
updated to entirely use the new library for the following services:

 * [MergePDF](https://foxyutils.com/mergepdf/)
 * [SplitPDF](https://foxyutils.com/splitpdf/)
 * [ProtectPDF](https://foxyutils.com/protectpdf/)
 * [UnlockPDF](https://foxyutils.com/unlockpdf/)

[UniDoc](http://unidoc.io) is starting out as a PDF toolkit for Go, but will be expanding to a general document
processing libraries with support to read and write PDF, Doc, DocX and more formats. Contribution from the
community is crucial to help us achieve our goal.

## Installation
~~~
go get github.com/unidoc/unidoc
~~~

## Overview and features

* Read and extract PDF metadata.
* Merge PDF ([example](https://github.com/unidoc/unidoc/blob/master/examples/pdf/pdf_merge.go)).
* Split PDF ([example](https://github.com/unidoc/unidoc/blob/master/examples/pdf/pdf_split.go)).
* Protect PDF ([example](https://github.com/unidoc/unidoc/blob/master/examples/pdf/pdf_protect.go)).
* Unlock PDF ([example](https://github.com/unidoc/unidoc/blob/master/examples/pdf/pdf_unlock.go)).
* The library aims to be fast and we process large PDF's in large quantities.
* Self contained and depends only on the Go standard library.
* Developer friendly.

## Examples

See the [examples](https://github.com/unidoc/unidoc/tree/master/examples) folder.

## Roadmap

We have big plans to improve it to support a lot of functionality:

 * Compress PDF.
 * JPG to PDF.
 * PDF to JPG.
 * High-level API to create PDF.
 * Search/replace PDFs - Edit functionality.
 * OCR engine to generate searchable PDF from scanned data.
 * Conversions from any format to another that makes sense e.g. PDF to Word, Word to PDF.
 * Create nice interface for generating reports with export capabilities to PDF and DocX.

We feel we are about to start an exciting journey of bringing the Go community an exciting document manipulation library.

## Languages

Go has an excellent toolchain which makes it possible to create language bindings for:

 * [Go](https://golang.org) - The library is written in Go so it works out of the box.
 * Python - We are considering [GoPy](https://github.com/go-python/gopy) for this. This will be the first step towards language bindings.
 * Java and C# if there is interest and demand.
 * Ruby if there is interest and demand.
 * Other languages will be considered if there is interest and demand.

## Licensing/Pricing

We are releasing this under a dual AGPL/Commercial license as we need to help fund further development to achieve our goals. See [pricing](http://unidoc.io/pricing).

## More information

For information see [GitHub](https://github.com/unidoc/unidoc) and the project [website](http://unidoc.io).

## Stay up to date

* Follow us on [twitter](https://twitter.com/unidoclib)
* Sign-up for our [newsletter](http://eepurl.com/b9Idt9)
