---
title: C++ BarCode Generation
url: /cpp/generate/
description: Create barcode images of various 1D and 2D symbologies via C++ library
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Generate BarCode Images Via C++" h2="Generate different Linear and 2D symbologies including Codabar, Code 11, Code 128, Code 39, Code 93, EAN, QR, Aztec, DataMatrix, PDf 417 and more to build C++ applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

Barcodes visually represent the data in the machine-readable form, having a printed series of parallel bars or lines of different width. Normally used in the automated checkout systems deployed in stores and supermarkets. There are various types such as linear or 2D. C++ barcode library supports both types and it is easy for programmers to generate barcode images of various symbologies. API provides a [BarcodeGenerator Class](https://apireference.aspose.com/barcode/cpp/class/aspose.bar_code.generation.barcode_generator) that deals with different barcode symbologies creation. Delevelpers can set any type such as [EncodeTypes](https://apireference.aspose.com/barcode/cpp/class/aspose.bar_code.generation.encode_types)::EAN8, Code93Extended, Code93Standard, Standard2of5, Matrix2of5 etc. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Creating Code 93 Barcode Images" %}}

Code 93 is an alphanumeric, variable length symbologyc, primarily used by Canada Post to encode supplementary delivery information. C++ barcode API supports code-93 standard and extended symbologies. EncodeTypes::Code93Extended and EncodeTypes::Code93Standard specifies that the data should be encoded with Extended and Standard CODE 93 barcode specification simultaneously. Process of generation is, use the BarcodeGenerator class with relevant code type and text as parameters. Using the same object set the additional settings and finally call the Save method to store into the relevant image format.  


{{% blocks/products/pf/feature-page-code h3="C++ Code for Generating Code 93 Standard Barcode" %}}

{{< gist "aspose-com-gists" "9e969164126f31f17fc931c1da9827d3" "generate-code-93-standard-barcode.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="C++ Code to Generate Code 93 Extended Barcode" %}}

{{< gist "aspose-com-gists" "9e969164126f31f17fc931c1da9827d3" "generate-code93-extended-barcode.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Data Matrix Barcode Generation" %}}

C++ BarCode API also supports 2D symbologies including Aztec, Data Matrix, PDf-417 and QR code. Process of generating Data Matrix code is almost same i.e create BarcodeGenerator class object with DataMatrix EncodeTypes as parameter, set the relevant parameters of the same object. Finally save into the required image format. Developers can also create many other popular barcode images of various linear and 2D symbologies listed below. 
 

{{% blocks/products/pf/feature-page-code h3="C++ Code for Data Matrix Code Generation" %}}

{{< gist "aspose-com-gists" "9e969164126f31f17fc931c1da9827d3" "data-matrix-code-generation.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Barcode">}}