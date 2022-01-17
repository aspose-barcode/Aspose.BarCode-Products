---
title: Java Barcode Generation
url: /java/generate/
description: Create barcode images of various 1D and 2D symbologies via Java library
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Generate Barcode Images Via Java" h2="Create barcodes of various 1D and 2D symbologies, including Codabar, Code 11, Code 128, Code 39, Code 93, EAN, Aztec, DataMatrix, PDF417, and others within Java applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

Barcodes are mainly used in E-commerce and retail to facilitate purchasing, tracking, and inventory of goods. Using barcode systems, stores can keep accurate records of their products, supplies, and items that are pivotal to their operations. Barcode generation functionality can be easily implemented using Aspose Java API that supports multi-format (1D and 2D) barcode symbologies. This API provides class [BarcodeGenerator](https://apireference.aspose.com/barcode/java/com.aspose.barcode.generation/BarcodeGenerator) that requires specifying the target barcode type in the [EncodeTypes](https://apireference.aspose.com/barcode/java/com.aspose.barcode.generation/EncodeTypes) property, by setting it, for example, to .CODE_128, AZTEC, or EAN_13. An object of class [BarcodeGenerator](https://apireference.aspose.com/barcode/java/com.aspose.barcode.generation/BarcodeGenerator) needs to be used for setting barcode input text and saving the generated barcode in the relevant image format. 
 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Creating UPC Barcode Images" %}}

Besides various 1D and 2D symbologies, Java Barcode API supports UPC-A, UPC-E, UPC-A GS1 Code 128 Coupon, and UPC-A GS1 DataBar Coupon barcodes. The Universal Product Code (UPC / UPC Code with 12 numeric digits assigned to each trade item) is a barcode standard used to track trade items in stores. A barcode of this type can be transformed into an EAN-13 symbol by prefixing it with a zero. Its nominal dimensions are 1.469 inches wide and 1.02 inches high. To generate a barcode, it is necessary to create an object of class BarcodeGenerator passing EncodeTypes.UPCA_GS_1_DATABAR_COUPON or EncodeTypes.UPCA_GS_1_CODE_128_COUPON as a parameter and set the input text to encode, for example, 512345678900(8110)001234502239811110555 or 514141100906(8102)03, respectively. Finally, the Save method needs to be called to output the generated barcode in the desired format.

{{% blocks/products/pf/feature-page-code h3="Java Code Sample for Generating UPCA GS1-128 AI 8102 Coupon Extended Barcode" %}}

{{< gist "aspose-com-gists" "08ed28dd8995051700db37a74b55b040" "generate-upca-gs1-128-ai-8102-coupon-extended-barcode.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="Java Code to Generate UPCA GS 1 Databar Coupon" %}}

{{< gist "aspose-com-gists" "08ed28dd8995051700db37a74b55b040" "create-upca-gs1-databar-coupon.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=" PDF 417 Barcode Generation" %}}

Java Barcode API also supports 2D symbologies, including Aztec, DataMatrix, PDF417, QR Code, and others. The process of generating a PDF417 barcode is similar to that explained above. First, it is necessary to create an object of class BarcodeGenerator setting the EncodeTypes field to EncodeTypes.PDF_417 and customizing the relevant parameters of the same object, including compaction mode, error correction level, the number of rows and columns, and others. Finally, the generated PDF417 barcode image can be saved into the desired image format. Using this logic, developers can create barcodes of many other popular 1D and 2D symbologies, as shown in the example below.
 

{{% blocks/products/pf/feature-page-code h3="Java Code for  PDF417 Code Generation" %}}

{{< gist "aspose-com-gists" "08ed28dd8995051700db37a74b55b040" "pdf-417-code-generation.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Barcode">}}