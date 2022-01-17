---
title: C# Barcode Recognition
url: /net/recognize/
description: Read barcodes of various 1D and 2D symbologies using .NET library
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Recognize Barcodes Via C#" h2="Read barcodes of various 1D and 2D symbologies, including  EAN 13, EAN 8, Codeblock, Code 128, Aztec, PDF417, QR Code, UPC, and others to build cross-platform .NET applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

**To recognize barcodes in C#**, Aspose provides the specified .NET barcode API that allows programmers to read barcodes of various symbologies at any angle. API includes the [BarCodeReader](https://apireference.aspose.com/barcode/net/aspose.barcode.recognition/barcodegenerator) class. All barcodes presented in an image can be detected using the [ReadBarCodes](https://apireference.aspose.com/barcode/net/aspose.barcode.barcoderecognition/barcodereader/methods/readbarcodes) method that is iterated for each barcode to get its type and encoded text. To perform barcode reading, it is required to pass the following parameters to the [ReadBarCodes](https://apireference.aspose.com/barcode/net/aspose.barcode.barcoderecognition/barcodereader/methods/readbarcodes) method: the name of a source barcode image and target barcode symbologies specified as the fields of [DecodeType](https://apireference.aspose.com/barcode/net/aspose.barcode.barcoderecognition/decodetype), e.g. *DecodeType.Code39*.  

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Recognize PDF417 Barcode" %}}

**C# BarCode Scanner API** is capable of reading multiple barcodes from a single image. Below, the process of decoding PDF417 barcodes is illustrated as an example. First, it is necessary to create an instance of class [BarCodeReader](https://apireference.aspose.com/barcode/net/aspose.barcode.recognition/barcodegenerator) passing the name of a source barcode image and DecodeType.Pdf417 as parameters. Then, this process needs to be reiterated for each barcode in an image.

{{% blocks/products/pf/feature-page-code h3="C# Code to Decode PDF417 Barcode" %}}

{{< gist "aspose-com-gists" "c8556eabef70104ce3471fb0c8fb9e1c" "read-pdf417-barcode.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="C# Code to Read Multiple Symbologies in an Image" %}}

{{< gist "aspose-com-gists" "c8556eabef70104ce3471fb0c8fb9e1c" "read-multiple-symbologies-in-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="QR Code Reader" %}}

For any .NET-based QR Code reader and scanner application, developers can easily integrate and enhance the below code according to their specific requirements. The process of reading QR codes is similar to that described above; namely, a BarCodeReader class object with the relevant image and symbology parameters needs to be created.

{{% blocks/products/pf/feature-page-code h3="C# Code for QR Code Recognition" %}}

{{< gist "aspose-com-gists" "c8556eabef70104ce3471fb0c8fb9e1c" "qr-code-reader.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Reader">}}