---
title: Java BarCode Generation
url: /java/generate/
description: Create barcode images of various 1D and 2D symbologies via Java library
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Generate BarCode Images Via Java" h2="Create various Linear and 2D symbologies including Codabar, Code11, Code128, Code39, Code93, EAN, Aztec, DataMatrix, PDf417 and more to build cross-platform Java applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

Barcodes are mainly the base of ecommerce and retail that helps in purchasing, tracking and inventory. Stores can keep accurate records of their products, supplies and items that are pivotal to their operations. Generating barcodes is easy using Java API that supports multi-format (1D and 2D) barcode symbologies. API provides [BarcodeGenerator class](https://apireference.aspose.com/barcode/java/com.aspose.barcode.generation/BarcodeGenerator) that takes encoding type such as [EncodeTypes](https://apireference.aspose.com/barcode/java/com.aspose.barcode.generation/EncodeTypes).CODE_128, AZTEC, EAN_13 etc as parameter. Use the object for setting code text and save it into relevant image format. 
 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Creating UPC Barcode Images" %}}

Java BarCode API supports UPCA, UPC-E, UPC A GS1 Code 128 Coupon, UPC-A GS1 DataBar Coupon barcodes. The Universal Product Code (UPC / UPC code having 12 numeric digits assigned to each trade item) is a barcode symbology for tracking trade items in stores and can be transformed into an EAN-13 symbol by prefixing it with a zero. It's nominal dimensions are 1.469 inches wide and 1.02 inches high. Process is, Create BarcodeGenerator class object having EncodeTypes.UPCA_GS_1_DATABAR_COUPON or EncodeTypes.UPCA_GS_1_CODE_128_COUPON as parameter. Set the code text like 512345678900(8110)001234502239811110555 or 514141100906(8102)03 respectively. Finally call the save method to save into the desired format.

{{% blocks/products/pf/feature-page-code h3="Java Code for Generating UPCA GS1-128 AI 8102 Coupon Extended Barcode" %}}

{{< gist "aspose-com-gists" "08ed28dd8995051700db37a74b55b040" "generate-upca-gs1-128-ai-8102-coupon-extended-barcode.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="Java Code to Generate UPCA GS 1 Databar Coupon" %}}

{{< gist "aspose-com-gists" "08ed28dd8995051700db37a74b55b040" "create-upca-gs1-databar-coupon.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2=" PDF 417 Barcode Generation" %}}

Java BarCode API also supports 2D symbologies including Aztec, Data Matrix, PDf-417 and QR code. Process of generating PDf-417 code is almost same i.e create BarcodeGenerator class object with EncodeTypes.PDF_417 as parameter, set the relevant parameters of the same object including setting rows and columns, compaction mode, correction levels using setPdf417ErrorLevel. Finally save into the required image format. Developers can also create many other popular barcode images of different symbologies listed below. 

 

{{% blocks/products/pf/feature-page-code h3="Java Code for  PDF-417 Code Generation" %}}

{{< gist "aspose-com-gists" "08ed28dd8995051700db37a74b55b040" "pdf-417-code-generation.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" afterslug="Barcode">}}