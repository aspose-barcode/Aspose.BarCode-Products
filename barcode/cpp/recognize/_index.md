---
title: C++ Barcode Recognition
url: /cpp/recognize/
description: Read barcode images of different 1D and 2D symbologies via C++ library
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Recognize Barcodes Via C++" h2="Read various Linear and 2D symbologies, including EAN, Codeblock, Code 39, Code 128, Aztec, DataMatrix, PDF417, QR Code, OPC, and others within C++ applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

**To read barcodes in C++**, developers can use the Aspose barcode C++ library that allows easily recognizing barcodes of various symbologies at any angle. This API provides class [BarCodeReader](https://apireference.aspose.com/barcode/cpp/class/aspose.bar_code.bar_code_recognition.bar_code_reader) that requires defining a source barcode image and target symbologies (DecodeType) as parameters. Then, all barcodes presented in the image can be recognized via the Read() method by iterating it for each barcode and getting its type and input text.  

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Recognize Code 39 Barcode" %}}

**Aspose C++ Barcode Scanner API** is capable of reading multiple symbologies from a single image. Below, the process of recognizing Code 39 barcodes is represented for example. It is required to create an instance of class [BarCodeReader](https://apireference.aspose.com/barcode/cpp/aspose.barcode.recognition/barcodegenerator) passing the name of a source barcode image and DecodeType.Code39Standard for Standard CODE 39 or DecodeType.Code39Extended for Extended CODE 39 (property [DecodeType](https://apireference.aspose.com/barcode/cpp/class/aspose.bar_code.bar_code_recognition.decode_type)) as parameters. Then, this process needs to be reiterated for each barcode in an image. 

{{% blocks/products/pf/feature-page-code h3="C++ Code Snippet to Read Code 39 Barcode" %}}

{{< gist "aspose-com-gists" "fefb019a921fda6c0143bd4db9ad3d2c" "read-code39-barcode.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="QR Code Reader" %}}

For any QR code reader and scanner application based on C++, developers can easily integrate the code snippet provided below or modify it according to their specific requirements. Even when an image may contain several different symbologies at the same time among which a QR code symbol, Aspose API can easily detect each symbology and decode its input text. The process of reading QR codes is similar to that described above; namely, a BarCodeReader class object with the relevant image and symbology parameters needs to be created. Using this logic, developers can read barcodes of many other widespread 1D and 2D symbologies, as explained in the code example below. 

{{% blocks/products/pf/feature-page-code h3="C++ Code for QR Code Reader" %}}

{{< gist "aspose-com-gists" "fefb019a921fda6c0143bd4db9ad3d2c" "qr-code-reader.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Reader">}}