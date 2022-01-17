---
title: C++ Barcode Generation
url: /cpp/generate/
description: Create barcode images of various 1D and 2D symbologies via C++ library
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Generate Barcodes Via C++" h2="Generate various barcodes of 1D and 2D symbologies, including Codabar, Code 11, Code 128, Code 39, Code 93, EAN, QR Code, Aztec, DataMatrix, PDF417, and others within C++ applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

Barcodes serve to visually represent the data in the machine-readable form and are normally used in automated checkout systems deployed in stores and supermarkets. Barcode is a printed series of parallel bars or lines of different width. There are various barcode types, including linear and 2D symbologies. Aspose C++ barcode library supports multiple barcode standards of both types; therefore, developers can easily generate barcode images of various symbologies. API provides a [BarcodeGenerator Class](https://apireference.aspose.com/barcode/cpp/class/aspose.bar_code.generation.barcode_generator) that deals with different barcode symbologies creation. For barcode generation, developers can set any of the supported barcode types using the [EncodeTypes](https://apireference.aspose.com/barcode/cpp/class/aspose.bar_code.generation.encode_types) property, including such symbologies as EAN 8, Code 93 Extended, Code 93 Standard, Standard 2-of-5, Matrix 2-of-5, and many others. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Creating Code 93 Barcode Images" %}}

Code 93 is an alphanumeric variable-length symbology primarily used by Canada Post to encode supplementary delivery information. Aspose C++ barcode API supports the Code 93 standard and the corresponding extended symbologies. By setting EncodeTypes::Code93Extended and EncodeTypes::Code93Standard, developers can specify that the barcode data should be encoded using the Extended and Standard Code 93 barcode specifications simultaneously. To generate a barcode, it is necessary to create an instance of class BarcodeGenerator passing the required symbology and inout text as parameters. Using the same object set, it is possible to customize additional settings; finally, the Save method needs to be called to output the generated barcode image into the relevant image format.  


{{% blocks/products/pf/feature-page-code h3="C++ Code for Generating Code 93 Standard Barcode" %}}

{{< gist "aspose-com-gists" "9e969164126f31f17fc931c1da9827d3" "generate-code-93-standard-barcode.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="C++ Code to Generate Code 93 Extended Barcode" %}}

{{< gist "aspose-com-gists" "9e969164126f31f17fc931c1da9827d3" "generate-code93-extended-barcode.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="DataMatrix Barcode Generation" %}}

Aspose C++ Barcode API supports 2D symbologies, including Aztec, DataMatrix, PDF417, and QR code. The process of generating a DataMatrix barcode is similar to that described above; namely, it is necessary to create an object of class BarcodeGenerator setting the EncodeTypes property to DataMatrix and defining the relevant parameters of the same object. Finally, the generated barcode label can be saved into the required image format. Using this logic, developers can create barcodes of many other popular linear and 2D symbologies, as shown in the example below. 
 

{{% blocks/products/pf/feature-page-code h3="C++ Code for DataMatrix Code Generation" %}}

{{< gist "aspose-com-gists" "9e969164126f31f17fc931c1da9827d3" "data-matrix-code-generation.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Barcode">}}