# Features

Here is a list of our features with documented examples.

## Read and extract PDF metadata
We are able to extract information from PDF files. See this ([example](https://github.com/unidoc/unidoc-examples/blob/master/pdf/pdf_extract_metadata.go)).

## Merge PDF
We are able to concatenate multiple PDF files into one big. See this ([example](https://github.com/unidoc/unidoc-examples/blob/master/pdf/pdf_merge.go)).

## Split PDF
We are able to split one PDF into multiple small ones. See this ([example](https://github.com/unidoc/unidoc-examples/blob/master/pdf/pdf_split.go)).

## Protect PDF
We are able to add protection to a PDF file. See this ([example](https://github.com/unidoc/unidoc-examples/blob/master/pdf/pdf_protect.go)).

## Unlock PDF
We are able to remove password and restrictions from the PDF file. In many cases a password is not required, however if it is you need to know it.
See this [example](https://github.com/unidoc/unidoc-examples/blob/master/pdf/pdf_unlock.go)).

## Rotate PDF
We are able to rotate PDF files. See this ([example](https://github.com/unidoc/unidoc-examples/blob/master/pdf/pdf_rotate.go)).

## Crop PDF
We are able to crop PDF files. See this ([example](https://github.com/unidoc/unidoc-examples/blob/master/pdf/pdf_crop.go)).

## Add Images
We are able to add images to PDF files. See this ([example](https://github.com/unidoc/unidoc-examples/blob/master/pdf/pdf_add_images.go)).
This example uses the standard Golang [image package](https://golang.org/pkg/image/) which is slow for any serious work.

## Add Images (using VIP backend)
We are able to add images to PDF files. See this ([example](https://github.com/unidoc/unidoc-examples/blob/master/pdf/pdf_add_images_fast.go)).
This example uses the bimg/VIP library as a backend to the ImageHandler interface UniDoc exposes. UniDoc is therefore flexible enough to allow
implementors to use the image manipulation library of choice while defaulting to the one in Go. Hopefully the one is Go gets faster over time.
