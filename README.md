
**Sample code for generating PDF/A document with PDFKit.**

The PDF/A spec is an extension of the regular PDF standard with a few extra
requirements designed to facilitate archiving, for example:

 - Color profiles must be embedded.
 - Fonts must be embedded.
 - Documents cannot be encrypted.

PDFKit can be used to generate PDF/A documents by manually adding the required
metadata and color profile and avoiding features which are not compatible with
the PDF/A spec.

This repository demonstrates how to generate a PDF/A 3b document with PDFKit.
