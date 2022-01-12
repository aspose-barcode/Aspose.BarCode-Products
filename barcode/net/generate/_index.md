---
title: C# Barcode Generation
url: /net/generate/
description: Create barcode images of various 1D and 2D symbologies via .NET library
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Generate Barcode Images Via C#" h2="Create barcodes of various 1D and 2D symbologies, including EAN 13, EAN 8, Codeblock, Code 128, Aztec, PDF417, QR Code, UPC, and others to build cross-platform .NET applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

**To generate barcodes in C#**, Aspose has introduced the dedicated .NET barcode API that allows programmers to save generated barcode labels to a database or a specified directory. Moreover, barcode generation functionality can be integrated into external applications. API provides the [BarcodeGenerator](https://apireference.aspose.com/barcode/net/aspose.barcode.generation/barcodegenerator) class that supports different 1D symbologies, such as Codabar, Code 11, Code 39 (Standard, Extended), Code 93 (Standard, Extended), EAN13, EAN8, and many others, as well as 2D symbologies, including Aztec, DataMatrix, PDF417, QR Code, etc. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Creating EAN Barcode Images" %}}

C# BarCode API supports various linear barcode types, including EAN 13 and EAN 8 symbologies. EAN-13 allows encoding 13 digits using the first two or three digits as a country code, the next five to seven digits as a manufacturer code, the following three to five digits as a product code, and the last character is the checksum digit. The process of generating EAN barcodes is discussed further as an example. First, it is required to create an instance of the [BarcodeGenerator](https://apireference.aspose.com/barcode/net/aspose.barcode.generation/barcodegenerator) class passing a relevant EAN type (EAN 13, EAN 14, or EAN 8) and appropriate input text. Then, developers need to set barcode parameters, and finally, call the [Save](https://apireference.aspose.com/barcode/net/aspose.barcode.generation.barcodegenerator/save/methods/1) method specifying the full path of a resulting image and the required image type.

{{% blocks/products/pf/feature-page-code h3="C# Code for Creating EAN 13 Barcode Image" %}}

{{< gist "aspose-com-gists" "33952eb590b3e09a245329dd58079c00" "create-ean13-barcode-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="C# Code to Generate EAN 8 Barcode Image" %}}

{{< gist "aspose-com-gists" "33952eb590b3e09a245329dd58079c00" "generate-ean8-barcode-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="QR Code Generation" %}}

.NET BarCode API also supports different 2D symbologies, including Aztec, DataMatrix, PDF417, and QR code. The process of creating QR codes is similar to that described above. Namely, it is necessary to create a BarcodeGenerator class object, set the relevant parameters for this object, such as QrEncodeMode, QrECIEncoding, XDimension, and others. Finally, the generated barcode can be saved in the required image format. Developers can also generate barcodes using many other widely used barcode symbologies listed below. 

 

{{% blocks/products/pf/feature-page-code h3="C# Code for QR Code Generation" %}}

{{< gist "aspose-com-gists" "33952eb590b3e09a245329dd58079c00" "qr-code-generation.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Barcode">}}