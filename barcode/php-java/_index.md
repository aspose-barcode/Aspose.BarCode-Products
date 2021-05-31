---
title: PHP Barcode Generator and Scanner API - Aspose 
weight: 2070
url: /php-java/ 
description: PHP barcode reader library to recognize mutiple types of barcodes including 1D, 2D and Postal. Use API in core PHP or within framework like codeigniter, cakephp or laravel.
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/upper-banner h1="PHP Barcode Generator and Reader API" h2="Scan or Generate 1D, 2D and postal barcodes from images in any PHP web application." logoImageSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/header/aspose_barcode-for-php-via-java.png" pfName="Aspose.BarCode for PHP via Java" subTitlepfName="for PHP via Java" downloadUrl="https://downloads.aspose.com/barcode/php" >}}

{{< blocks/products/pf/main-container pfName="Aspose.BarCode" subTitlepfName="for PHP via Java" >}}

{{< blocks/products/pf/sub-menu logoImageSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/barcode/272x272/aspose_barcode-for-php-via-java.png" liveDemosLink="" PricingLink="https://purchase.aspose.com/pricing/barcode/php-java" buyLink="" docsLink="https://docs.aspose.com/barcode/java/php-via-java-release-notes/" instalationsDocsLink="" nugetLink="" nugetPackageName="" >}}

{{< blocks/products/pf/tab-content >}}
<p>
 Aspose.BarCode for PHP via Java is a set of barcode generation and reading APIs for PHP applications and scripts. Developers can easily read 1D, 2D and postal barcodes from images at different angles. Barcode generator API creates barcode images within various formats such as JPG, PNG, GIF, BMP.  Moreover, It supports multiple imaging features like manipulating borders, color, rotating images, customizing resolution and a lot more.
</p>

{{< /blocks/products/pf/tab-content >}}

<!--Diagrams Start-->
{{< blocks/products/pf/carousel >}}

{{< blocks/products/pf/carousel-item h3="" description="" >}}
{{< /blocks/products/pf/carousel-item >}}

{{< /blocks/products/pf/carousel >}}
<!--Diagrams End-->

<!--Feature-section Start-->
<div class="container-fluid features-section bg-gray">
 <a class="anchor" id="features" name="features">
 </a>
 <div class="row">
  <div class="container">
   <h2 class="pr-ft">
    Advanced PHP Barcode API Features
   </h2>
   <p>
   </p>
   <div class="col-lg-4">
    <em class="fa fa-exchange ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Generate multiple types of barcodes
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-object-group ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Manage X and Y Dimensions
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-repeat ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Set Height of the Bars
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-refresh ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Set Start and Stop Symbols of Codabar
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-cogs ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Control the Appearance of Code Text
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-anchor ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Manage the Barcode Caption
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-text-width ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Set Code Text for Barcode
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-bolt ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Specify Symbologies for Barcodes
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-signal ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Recognize Multiple Symbologies in Single Image
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-random ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Recognize Specific Barcode Symbology
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-barcode ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Recognize all 1D Barcodes from an Image
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-percent ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Get BarCode Recognition Quality in Percent
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-circle ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Obtain Barcode Region Information from the Image
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-star ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Read Barcode from Specific Region
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-arrows ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Switch Barcode Recognition Modes as of Requirement
    </p>
   </div>
   <div class="col-lg-12">
    <h2 class="h2title">
     QR Code Generation
    </h2>
    <p>
     API has the capability to create barcodes of multiple types including DataMatrix, Aztec, Pdf417, multiple MacroPdf417 barcodes for large or multiple code text values. Here is the code for QR code generation.
    </p>
    <div class="codeblock" id="code">
     <h3>
      PHP QR Code Generator
     </h3>
     <pre><code class="java"> //Instantiate barcode object

$builder = new BarCodeBuilder();



$symbology=new Symbology();

$builder-&gt;setSymbologyType($symbology-&gt;QR);

 

$builder-&gt;setCodeText("1234567890");

 

// Hide code text

$codeLocation=new CodeLocation();

$builder-&gt;setCodeLocation($codeLocation-&gt;None);

 

$builder-&gt;setRotationAngleF(90);

 

// Save the image to your system and set its image format to Jpeg

$builder-&gt;save($dataDir . "CreatingQRBarcode.jpg");

 

// Display or echo Status

</code></pre>
    </div>
   </div>
   <!--<div class="col-lg-12">

<h2 class="h2title">Supported Barcode Symbologies</h2>

<p>Aspose.BarCode for PHP via Java supports a large number of linear, 2D and postal bar code symbologies for both encoding and decoding.</p>

<p>API supported Alpha-Numeric Symbologies include:</p>

<div class="col-lg-6">

<ul class="unstyled">

<li>Code128</li>

<li>Code39 Extended</li>

<li>Code93 Extended</li>

<li>Australia Post</li>

<li>PZN</li>

<li>VIN</li>

</ul>

</div>

<div class="col-lg-6">

<ul class="unstyled">

<li>EAN128</li>

<li>Code39 Standard</li>

<li>Code93 Standard</li>

<li>Matrix 2 of 5</li>

<li>Deutsche Post Identcode</li>

</ul>

</div>

</div>

<div class="col-lg-12">-->
   <!-- <h2 class="h2title">2D Symbologies Include:</h2> -->
   <!--<p>2D types include:</p>

<div class="col-lg-6">

<ul class="unstyled">

<li>Pdf417</li>

<li>QR</li>

<li>Macro PDF 417</li>

</ul>

</div>

<div class="col-lg-6">

<ul class="unstyled">

<li>DataMatrix</li>

<li>Aztec</li>

</ul>

</div>

</div>

--&gt; <!--<div class="col-lg-12"><!-- <h2 class="h2title">Postal Symbologies Include:</h2> -->
   <!--<p>Postal types include:</p>

<div class="col-lg-6">

<ul class="unstyled">

<li>Postnet</li>

<li>Planet</li>

<li>USPS OneCode</li>

<li>Australia Post</li>

<li>Deutsche Post Identcode</li>

</ul>

</div>

<div class="col-lg-6">

<ul class="unstyled">

<li>Deutsche Post Leticode</li>

<li>RM4SCC</li>

<li>SingaporePost</li>

<li>AustralianPosteParcel</li>

<li>SwissPostParcel</li>

<li>UpcaGs1DatabarCoupon</li>

</ul>

</div>

</div>-->
   <!--<div class="col-lg-12">

<h2 class="h2title">Imaging, Rotation & Sizing</h2>

<p>Common manipulation features of the barcode library are modifying barcode image, border and background colors, bar color, margins, width of images and much more. Furthermore, PHP API can adjust the resolution for the resultant images and can rotate images at any angle for generating high-quality images with anti-aliasing.</p>

</div>

<div class="col-lg-12">

<h2 class="h2title">Customizing Symbologies & Appearance</h2>

<p>PHP barcode API allows you to easily customize the codes by specifying different kinds of symbologies, setting code text (data to be encoded to barcode image) and appearance-related properties like font, background color, foreground color, as well as alignment and location (hide, above, below). You can also easily manage caption settings such as font, background color, foreground color, alignment and location (hide, above, below).</p>

</div>-->
  </div>
 </div>
</div>
<!--Feature-section End-->

{{< /blocks/products/pf/main-container >}}


{{< blocks/products/pf/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Learning Resources" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Documentation" href="https://docs.aspose.com/barcode/java/aspose-barcode-java-for-php/" >}}
{{< blocks/products/pf/slr-element name="Source Code" href="https://github.com/aspose-barcode/Aspose.BarCode-for-Java/tree/master/Plugins/Aspose_Barcode_Java_for_PHP" >}}
{{< blocks/products/pf/slr-element name="API References" href="https://apireference.aspose.com/barcode/java" >}}
{{< blocks/products/pf/slr-element name="Tutorial Videos" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Product Support" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Free Support" href="https://forum.aspose.com/c/barcode" >}}
{{< blocks/products/pf/slr-element name="Paid Support" href="https://helpdesk.aspose.com/" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.com/category/barcode/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Why Aspose.BarCode for PHP via Java?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Customers List" href="https://company.aspose.com/customers" >}}
{{< blocks/products/pf/slr-element name="Success Stories" href="https://company.aspose.com/customers/success-stories/aspose-barcode" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/support-learning-resources >}}

{{< blocks/products/pf/download-section downloadFreeTrialLink="https://downloads.aspose.com/barcode/php" pricingInformationLink="https://purchase.aspose.com/pricing/barcode/php-java" >}}

{{< blocks/products/pf/offers-section pfName="Aspose.BarCode" description="Aspose.BarCode offers individual Barcode generation and recognition APIs for other popular development environments as listed below:" >}}

    {{< blocks/products/pf/offers-section-item link="/barcode/net" imgSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/barcode/272x272/aspose_barcode-for-net.png" sdkName=".NET" >}}
    {{< blocks/products/pf/offers-section-item link="/barcode/java" imgSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/barcode/272x272/aspose_barcode-for-java.png" sdkName="Java" >}}
    {{< blocks/products/pf/offers-section-item link="/barcode/cpp" imgSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/barcode/272x272/aspose_barcode-for-cpp.png" sdkName="C++" >}}
    {{< blocks/products/pf/offers-section-item link="/barcode/android-java" imgSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/barcode/272x272/aspose_barcode-for-android-via-java.png" sdkName="Android via Java" >}}
    {{< blocks/products/pf/offers-section-item link="/barcode/sharepoint" imgSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/barcode/272x272/aspose_barcode-for-sharepoint.png" sdkName="SharePoint" >}}
    {{< blocks/products/pf/offers-section-item link="/barcode/reporting-services" imgSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/barcode/272x272/aspose_barcode-for-reporting-services.png" sdkName="Reporting Services" >}}
    {{< blocks/products/pf/offers-section-item link="/barcode/jasperreports" imgSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/barcode/272x272/aspose_barcode-for-jasperreports.png" sdkName="JasperReports" >}}
    {{< blocks/products/pf/offers-section-item link="/barcode/nodejs-java" imgSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/barcode/header/aspose_barcode-for-nodejs-java.png" sdkName="Node.js via Java" >}}

{{< /blocks/products/pf/offers-section >}}

{{< /blocks/products/pf/main-wrap-class >}}