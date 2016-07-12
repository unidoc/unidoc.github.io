At [FoxyUtils](https://foxyutils.com) we have been using various libraries for manipulating PDF libraries
over the years and never been completely happy with what we have used. In the last couple of years we
have been leaning towards [Golang](https://golang.org) for our architecture. This means we have been having
to shell out and calling external APIs. As a result we have been developing a library in the background and
are pleased to announce that our baby has been born and is ready for the prime time. FoxyUtils.com has been
updated to entirely use the new library for the following services:
 * MergePDF
 * SplitPDF
 * ProtectPDF
 * UnlockPDF

We have big plans to improve it to support a lot for functionality:

 * Compress PDF
 * JPG to PDF
 * PDF to JPG
 * High-level API to create PDF
 * Search/replace PDFs - Edit functionality
 * OCR engine to generate searchable PDF from scanned data
 * Conversions from any format to another that makes sense e.g. PDF to Word, Word to PDF.

We are releasing this under a dual AGPL/Commercial license.
