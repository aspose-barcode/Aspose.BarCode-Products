---
title: Java Barcode Recognition
url: /java/recognize/
description: Read barcode images of different 1D and 2D symbologies via Java library
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Recognize Barcodes Via Java" h2="Read various Linear and 2D symbologies, including  EAN, Codeblock, Code 128, Aztec, DataMatrix, PDF417, QR Code, UPC, and others within Java applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

**To read barcodes in Java**, developers can use the Aspose Java barcode API that enables reading barcodes of various symbologies at any angle in a fast and easy way. This library provides class [BarCodeReader](https://apireference.aspose.com/barcode/java/com.aspose.barcode.barcoderecognition/BarCodeReader) that requires specifying a source barcode image and target symbologies (DecodeType) as parameters. Then, all barcodes presented in the image can be recognized via the [ReadBarCodes](https://apireference.aspose.com/barcode/java/com.aspose.barcode.barcoderecognition/BarCodeReader#readBarCodes--) method by iterating it for each barcode and getting its type and input text. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Recognize Code 128 Barcode" %}}

**Java Barcode Scanner API** is capable of reading multiple barcodes of different symbologies that are presented in a single image. The process of reading Code 128 barcodes is discussed as an example further. An instance of class [BarCodeReader](https://apireference.aspose.com/barcode/java/com.aspose.barcode.barcoderecognition/BarCodeReader) needs to be created passing the name of a source barcode image as a parameter and setting the [DecodeType](https://apireference.aspose.com/barcode/java/com.aspose.barcode.barcoderecognition/DecodeType) property to DecodeType.CODE_128. Then, these steps must be reiterated for each barcode in an image. 

{{% blocks/products/pf/feature-page-code h3="Java Code Sample to Read Code 128 Barcode" %}}

{{< gist "aspose-com-gists" "3883a51102fd07862d547ca950e05253" "read-code-128-barcode.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="Java Code Sample to Read Barcodes of Various Symbologies, including Code 128" %}}

{{< gist "aspose-com-gists" "3883a51102fd07862d547ca950e05253" "read-multiple-symbologies-in-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="QR Code Reader" %}}

For any QR code reading and scanning application implemented in Java, programmers can easily integrate the below code or modify it according to specific needs. The process of recognizing QR codes is similar to that described above. it is necessary to create an object of class BarCodeReader passing the relevant image and symbology parameters. Using this logic, developers can perform barcode recognition for many other widespread 1D and 2D symbologies, as explained in the code example below. 

{{% blocks/products/pf/feature-page-code h3="Java Code Sample for QR Code Reader" %}}

{{< gist "aspose-com-gists" "3883a51102fd07862d547ca950e05253" "qr-code-reader.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Reader">}}