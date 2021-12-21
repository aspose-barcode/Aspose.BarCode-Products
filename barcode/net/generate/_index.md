---
title: C# Barcode Generation
url: /net/generate/
description: Create barcode images of various 1D and 2D symbologies with few lines of C# code via .NET library
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Generate Barcode Images Via C#" h2="Create various 1D and 2D symbologies including  EAN 13, EAN 8, Codeblock, Code 128, Aztec, PDF 417, QR, UPC and more to build cross-platform .NET applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

**How to generate barcodes in C#**, .NET Barcode API can do it easily. Programmers can save generated barcode labels to a database, within a specified directory or can integrate the barcode generation feature into some external applications. API provides [BarcodeGenerator](https://apireference.aspose.com/barcode/net/aspose.barcode.generation/barcodegenerator), which supports different 1D symbologies including Codabar, Code 11, Code 39 (Standard, Extended), Code 93 (Standard, Extended), EAN13, EAN8 etc and 2D symbologies such as Aztec, DataMatrix, PDf417, QR code. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Creating EAN Barcode Images" %}}

C# BarCode API supports Linear EAN 13 and EAN 8 symbologies. EAN-13 barcode having 13 digits code with the first two or three digits as country code, the next five to seven digits as the manufacturer code and the next three to five digits as the product code and the last one is for the checksum digit. Process of generating EAN barcode symbologies is, Create the BarcodeGenerator instance with relevant EAN Type it may be EAN13, EAN14, EAN8 with relevant code text. Set the relevant parameters and finally call the Save method with relevant image with full path and image type.

{{% blocks/products/pf/feature-page-code h3="C# Code for Creating EAN 13 Barcode Image" %}}

{{< gist "aspose-com-gists" "33952eb590b3e09a245329dd58079c00" "create-ean13-barcode-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="C# Code to Generate EAN 8 Barcode Image" %}}

{{< gist "aspose-com-gists" "33952eb590b3e09a245329dd58079c00" "generate-ean8-barcode-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="QR Code Generation" %}}

.NET BarCode API also supports 2D symbologies including Aztec, DataMatrix, PDf417 and QR code. Process of creating QR code is almost same i.e create BarcodeGenerator class object, set the relevant parameters of the same object like QrEncodeMode, QrECIEncoding, XDimension etc. and finally save into the required image format. Developers can also generate many other popular barcode symbologies listed below. 

 

{{% blocks/products/pf/feature-page-code h3="C# Code for QR Code Generation" %}}

{{< gist "aspose-com-gists" "33952eb590b3e09a245329dd58079c00" "qr-code-generation.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Barcode">}}