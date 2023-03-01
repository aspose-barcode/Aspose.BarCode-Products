---
title: Scan Data Matrix code Images via Python via Java
weight: 1510
url: /python-java/recognize/datamatrix/
description: Python source code for Data Matrix code recognition using Java Runtime Environment.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Read Data Matrix Barcodes with Python via Java" h2="Read Data Matrix code in Python using server-side Aspose.BarCode for Python via Java API" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/barcode/headers/aspose_barcode-for-python-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="Data Matrix" pfName="Aspose.BarCode" subTitlepfName="for Python via Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="SVG" >}}

{{< blocks/products/pf/main-container pfName="Aspose.BarCode " subTitlepfName="for Python via Java" >}}
{{< blocks/products/pf/sub-menu autoRecognizedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/barcode/aspose_barcode-for-python-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-barcode" liveDemosLink="https://products.aspose.app/barcode/family" docsLink="https://docs.aspose.com/barcode/python-java/" installationsDocsLink="https://docs.aspose.com/barcode/python-java/installation" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/barcode/python-java/" learnAsLink="https://docs.aspose.com/barcode/python-java/" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-barcode" >}}

{{% blocks/products/pf/agp/content h2="How to Read Data Matrix code Using Python via Java" %}}
To scan and decode Data Matrix code, install [Aspose.BarCode for Python via Java](https://products.aspose.com/barcode/python-java/) API, a versatile, powerful, and easy-to-use barcode library for Python-based applications. Get the latest version directly from the [Aspose releases](https://releases.aspose.com/barcode/python-java/) portal or install 'aspose-barcode' from pip by running the following command:

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```ps1
  pip install aspose-barcode 

```

{{% /blocks/products/pf/agp/code-block %}}{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps for Scanning Data Matrix code in Python" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.BarCode allows developers to read Data Matrix code barcodes from stream or image with few lines of code

{{% /blocks/products/pf/agp/text %}}

<ul><li>Create an object of Aspose.BarCode.BarCodeReader class</li><li>Define the source file path containing Data Matrix code as a parameter</li><li>Determine the required barcodes types in DecodeType as the second parameter</li><li>Loop through the decoding outcomes</li><li>Get the barcode text using the CodeText property</li></ul>

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

Aspose APIs are supported on all major platforms and operating systems. Before executing the code sample below, please make sure that your system comply with the following requirements.

{{% /blocks/products/pf/agp/text %}}

<ul><li>Microsoft Windows, Linux, or any OS compatible with Python-based developement environments</li><li>Java 8 or above</li><li>Python 3.6 or above</li><li>PHP/Java Bridge installed</li><li>FastCGI and Tomcat Server 8.0 or above</li></ul>

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< blocks/products/pf/agp/feature-section2 >}}
<!-- BEGIN LCS -->
<div class="barcode-read-lcs" style="width: 100%;">
    <style>
        .barcode-read-lcs {
            width: 100%;
            box-sizing: border-box;
        }
        .barcode-read-lcs-controls {
            display: flex;
            flex-wrap: wrap;
        }
        .barcode-read-lcs-drop {
            cursor: pointer;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-width: 350px;
            box-sizing: border-box;
            margin: 0 15px 15px 0;
            padding: 15px 15px 10px 15px;
            border: dashed 3px #73b5fb;
            border-radius: 10px;
            background-color: #ffffff;
        }
        .barcode-read-lcs-drop input {
            display: none !important;
        }
        .barcode-read-lcs-drop-preload {
            display: none;
        }
        .barcode-read-lcs-drop svg {
            width: 48px;
            margin-bottom: 5px;
            filter: invert(70%) sepia(12%) saturate(3506%) hue-rotate(183deg) brightness(101%) contrast(97%);
        }
        .barcode-read-lcs-drop span {
            font-size: 18px;
            text-align: center;
        }
        .barcode-read-lcs-filename {
            display: none;
        }
        .barcode-read-lcs-filename span {
            font-style: italic;
        }
        .barcode-read-lcs-recognizing {
            display: none;
        }
        .barcode-read-lcs-recognizing span {
            font-style: italic;
        }
        .barcode-read-lcs-mods {
            display: flex;
            flex-direction: column;
        }
        .barcode-read-lcs-mods select {
			margin-bottom: 7px;
			padding: .6em 1.4em .5em .8em;
			border:  solid 2px #73b5fb;
			border-radius: .5em;
			line-height: 1.3;
			font-family: arial,sans-serif,-apple-system,BlinkMacSystemFont,segoe ui,Roboto,helvetica neue,apple color emoji,segoe ui emoji,segoe ui symbol;
			font-size: 16px;
			font-weight: 700;
			color: #73b5fb;
			-moz-appearance: none;
			-webkit-appearance: none;
			appearance: none;
			background-color: #ffffff;
			background-image: url('data:image/svg+xml;charset=US-ASCII,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%22292.4%22%20height%3D%22292.4%22%3E%3Cpath%20fill%3D%22%2373b5fb%22%20d%3D%22M287%2069.4a17.6%2017.6%200%200%200-13-5.4H18.4c-5%200-9.3%201.8-12.9%205.4A17.6%2017.6%200%200%200%200%2082.2c0%205%201.8%209.3%205.4%2012.9l128%20127.9c3.6%203.6%207.8%205.4%2012.8%205.4s9.2-1.8%2012.8-5.4L287%2095c3.5-3.5%205.4-7.8%205.4-12.8%200-5-1.9-9.2-5.5-12.8z%22%2F%3E%3C%2Fsvg%3E');
			background-repeat: no-repeat, repeat;
			background-position: right .7em top 50%, 0 0;
			background-size: .65em auto, 100%;
		}
		.barcode-read-lcs-mods select::-ms-expand {
			display: none;
		}
		.barcode-read-lcs-mods select:hover, .barcode-read-lcs-mods select:focus {
			border-color: #1a89d0;
			color: #1a89d0;
			background-image: url('data:image/svg+xml;charset=US-ASCII,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20width%3D%22292.4%22%20height%3D%22292.4%22%3E%3Cpath%20fill%3D%22%231a89d0%22%20d%3D%22M287%2069.4a17.6%2017.6%200%200%200-13-5.4H18.4c-5%200-9.3%201.8-12.9%205.4A17.6%2017.6%200%200%200%200%2082.2c0%205%201.8%209.3%205.4%2012.9l128%20127.9c3.6%203.6%207.8%205.4%2012.8%205.4s9.2-1.8%2012.8-5.4L287%2095c3.5-3.5%205.4-7.8%205.4-12.8%200-5-1.9-9.2-5.5-12.8z%22%2F%3E%3C%2Fsvg%3E');
		}
		.barcode-read-lcs-mods select:focus {
			outline: none;
		}
		*[dir="rtl"] .barcode-read-lcs-mods select, :root:lang(ar) .barcode-read-lcs-mods select, :root:lang(iw) .barcode-read-lcs-mods select {
			background-position: left .7em top 50%, 0 0;
			padding: .6em .8em .5em 1.4em;
		}
		.barcode-read-lcs-mods select option {
			font-weight: normal;
			color: #4c4c4c;
		}
        .barcode-read-lcs-mods > * {
            min-width: 150px;
            box-sizing: border-box;
        }
        .barcode-read-lcs-mods input {
            padding: 0.6em .6em;
            border: none;
            border-radius: .5em;
            box-shadow: inset 0 1px rgb(255 255 255 / 15%), 0 1px 1px rgb(0 0 0 / 8%);
            font-family: arial,sans-serif,-apple-system,BlinkMacSystemFont,segoe ui,Roboto,helvetica neue,apple color emoji,segoe ui emoji,segoe ui symbol;
            font-size: 16px;
            font-weight: 700;
            color: #ffffff;
            background-color: #1a89d0;
        }
        .barcode-read-lcs-mods input:hover {
            background-color: #3071a9;
            transition: all .3s ease;
            transition-property: all;
            transition-duration: 0.3s;
            transition-timing-function: ease;
            transition-delay: 0s;
        }
        .barcode-read-lcs-disabled {
            background-color: silver !important;
        }
        .barcode-read-lcs-disclaimer {
            font-size: 12px !important;
        }
        .barcode-read-lcs-result {
            position: fixed;
            top: 0px;
            right: 0px;
            bottom: 0px;
            left: 0px;
            background: rgba(0,0,0,0.8);
            z-index: 9998;
            -webkit-transition: opacity 400ms ease-in;
            -moz-transition: opacity 400ms ease-in;
            transition: opacity 400ms ease-in;
            display: none;
        }
        .barcode-read-lcs-result > div {
            display: inline-block;
            width: 90vw;
            position: relative;
            margin: 10% auto;
            padding: 5px 20px 13px 20px;
            border-radius: 10px;
            background: #ffffff;
            pointer-events: auto;
        }
        .barcode-read-lcs-result header {
            position: relative;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding:  5px 0 10px 0;
            border-bottom: dotted 1px #1a89d0;
        }
        .barcode-read-lcs-result header span {
            font-size: 18px;
            font-weight: 700;
        }
        .barcode-read-lcs-result header i {
            cursor: pointer;
            color: #1a89d0;
            font-size: 24px !important;
        }
        .barcode-read-lcs-result header i:hover {
            color: #3071a9;
        }
        .barcode-read-lcs-result article {
            max-height: 500px;
            overflow: auto;
            margin: 25px 0 15px 0;
            display: flex;
            flex-direction: row;
            justify-content: center;
        }
        .recognitionResult_row {
            margin-left: 20px;
        }
    </style>
    <div class="barcode-read-lcs-controls">
        <div class="barcode-read-lcs-drop" onclick="BarcodeReadLcsUpload(this);" ondragover="event.preventDefault();" ondrop="BarcodeReadLcsDropped(event,this);">
            <input type="file" accept=".jpeg,.jpg,.png,.bmp,.gif" onchange="BarcodeReadLcsFileSelected(this);" />
            <svg class="barcode-read-lcs-drop-preload" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 100 100"><g transform="translate(89,50)"><g transform="rotate(0)"><circle cx="0" cy="0" r="5" fill="#29c26a" fill-opacity="1"><animateTransform attributeName="transform" type="scale" begin="-0.8888888888888888s" values="2 2;1 1" keyTimes="0;1" dur="1s" repeatCount="indefinite"></animateTransform><animate attributeName="fill-opacity" keyTimes="0;1" dur="1s" repeatCount="indefinite" values="1;0" begin="-0.8888888888888888s"></animate></circle></g></g><g transform="translate(79.87573328164014,75.06871677777502)"><g transform="rotate(40)"><circle cx="0" cy="0" r="5" fill="#29c26a" fill-opacity="0.8888888888888888"><animateTransform attributeName="transform" type="scale" begin="-0.7777777777777778s" values="2 2;1 1" keyTimes="0;1" dur="1s" repeatCount="indefinite"></animateTransform><animate attributeName="fill-opacity" keyTimes="0;1" dur="1s" repeatCount="indefinite" values="1;0" begin="-0.7777777777777778s"></animate></circle></g></g><g transform="translate(56.772278929010284,88.40750236747611)"><g transform="rotate(80)"><circle cx="0" cy="0" r="5" fill="#29c26a" fill-opacity="0.7777777777777778"><animateTransform attributeName="transform" type="scale" begin="-0.6666666666666666s" values="2 2;1 1" keyTimes="0;1" dur="1s" repeatCount="indefinite"></animateTransform><animate attributeName="fill-opacity" keyTimes="0;1" dur="1s" repeatCount="indefinite" values="1;0" begin="-0.6666666666666666s"></animate></circle></g></g><g transform="translate(30.500000000000007,83.77499074759311)"><g transform="rotate(119.99999999999999)"><circle cx="0" cy="0" r="5" fill="#29c26a" fill-opacity="0.6666666666666666"><animateTransform attributeName="transform" type="scale" begin="-0.5555555555555556s" values="2 2;1 1" keyTimes="0;1" dur="1s" repeatCount="indefinite"></animateTransform><animate attributeName="fill-opacity" keyTimes="0;1" dur="1s" repeatCount="indefinite" values="1;0" begin="-0.5555555555555556s"></animate></circle></g></g><g transform="translate(13.351987789349579,63.33878558970109)"><g transform="rotate(160)"><circle cx="0" cy="0" r="5" fill="#29c26a" fill-opacity="0.5555555555555556"><animateTransform attributeName="transform" type="scale" begin="-0.4444444444444444s" values="2 2;1 1" keyTimes="0;1" dur="1s" repeatCount="indefinite"></animateTransform><animate attributeName="fill-opacity" keyTimes="0;1" dur="1s" repeatCount="indefinite" values="1;0" begin="-0.4444444444444444s"></animate></circle></g></g><g transform="translate(13.351987789349572,36.661214410298925)"><g transform="rotate(200)"><circle cx="0" cy="0" r="5" fill="#29c26a" fill-opacity="0.4444444444444444"><animateTransform attributeName="transform" type="scale" begin="-0.3333333333333333s" values="2 2;1 1" keyTimes="0;1" dur="1s" repeatCount="indefinite"></animateTransform><animate attributeName="fill-opacity" keyTimes="0;1" dur="1s" repeatCount="indefinite" values="1;0" begin="-0.3333333333333333s"></animate></circle></g></g><g transform="translate(30.499999999999982,16.2250092524069)"><g transform="rotate(239.99999999999997)"><circle cx="0" cy="0" r="5" fill="#29c26a" fill-opacity="0.3333333333333333"><animateTransform attributeName="transform" type="scale" begin="-0.2222222222222222s" values="2 2;1 1" keyTimes="0;1" dur="1s" repeatCount="indefinite"></animateTransform><animate attributeName="fill-opacity" keyTimes="0;1" dur="1s" repeatCount="indefinite" values="1;0" begin="-0.2222222222222222s"></animate></circle></g></g><g transform="translate(56.77227892901027,11.59249763252388)"><g transform="rotate(280)"><circle cx="0" cy="0" r="5" fill="#29c26a" fill-opacity="0.2222222222222222"><animateTransform attributeName="transform" type="scale" begin="-0.1111111111111111s" values="2 2;1 1" keyTimes="0;1" dur="1s" repeatCount="indefinite"></animateTransform><animate attributeName="fill-opacity" keyTimes="0;1" dur="1s" repeatCount="indefinite" values="1;0" begin="-0.1111111111111111s"></animate></circle></g></g><g transform="translate(79.87573328164014,24.931283222224955)"><g transform="rotate(320)"><circle cx="0" cy="0" r="5" fill="#29c26a" fill-opacity="0.1111111111111111"><animateTransform attributeName="transform" type="scale" begin="0s" values="2 2;1 1" keyTimes="0;1" dur="1s" repeatCount="indefinite"></animateTransform><animate attributeName="fill-opacity" keyTimes="0;1" dur="1s" repeatCount="indefinite" values="1;0" begin="0s"></animate></circle></g></g><!-- [ldio] generated by https://loading.io/ --></svg>
            <svg class="barcode-read-lcs-drop-icon" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 0 128 128"><path d="M80,0v32h32L80,0z M72,32V0H28c-6.63,0-12,5.37-12,12v104c0,6.62,5.37,12,12,12h72c6.63,0,12-5.37,12-12V40H80.22    C75.57,40,72,36.42,72,32z M88.03,86.03C87.07,87.43,85.55,88,84,88s-3.07-0.59-4.24-1.76L70,76.47V102c0,3.31-2.69,6-6,6    s-6-2.69-6-6V76.47l-9.76,9.76c-2.34,2.34-6.14,2.34-8.49,0s-2.34-6.14,0-8.49l20-20c2.34-2.34,6.14-2.34,8.49,0l20,20    C90.57,80.1,90.57,83.9,88.03,86.03z"/></svg>
            <span class="barcode-read-lcs-filename">Ready to recognize <span></span></span>
            <span class="barcode-read-lcs-recognizing">Recognizing <span></span></span>
            <span class="barcode-read-lcs-hint">Drop a file here or click to browse *</span>
        </div>
        <div class="barcode-read-lcs-mods">
            <input id="recognize-button" type="button" value="Run code" class="barcode-read-lcs-recognize barcode-read-lcs-disabled" onclick="recognizeBarcodeAsync()" />
        </div>
    </div>
    <p class="barcode-read-lcs-disclaimer">* By uploading your files or using the service you agree with our <a href='https://about.aspose.com/legal/terms-of-use' rel='nofollow noreferrer' target='_blank'>Terms of use</a> and <a href='https://about.aspose.com/legal/privacy-policy' rel='nofollow noreferrer' target='_blank'>Privacy Policy</a>.</p>
<div id="code" class="codeblock"><h3>Code to be executed - Python</h3><pre>
    <code class='py hljs'>
<span class="hljs-keyword">import</span> os
<span class="hljs-keyword">import</span> base64
<span class="hljs-keyword">from</span> asposebarcode <span class="hljs-keyword">import</span> Recognition

<span class="hljs-keyword">class</span> <span class="hljs-title class_">BarcodeReaderExamples</span>():
    <span class="hljs-keyword">def</span> <span class="hljs-title function_">readBarcodeImage</span>(<span class="hljs-params">self</span>):
        image_data_base64 = ta.load_image_base64_from_path(<span class="hljs-string"><span class="barcode-read-lcs-code-filename-placeholder">&lt;file name&gt;</span><span class="barcode-read-lcs-code-filename-actual"></span></span>)
        reader = Recognition.BarcodeReader(image_data_base64, <span class="hljs-literal">None</span>, Recognition.DecodeType.<span class="barcode-read-lcs-type">DataMatrix</span>)
        recognized_results = reader.readBarCodes()
        <span class="hljs-keyword">for</span> x <span class="hljs-keyword">in</span> recognized_results:
            <span class="hljs-built_in">print</span>(x.getCodeText())
            <span class="hljs-built_in">print</span>(x.getCodeTypeName())

    <span class="hljs-keyword">def</span> <span class="hljs-title function_">load_image_base64_from_path</span>(<span class="hljs-params">filePath</span>):
        <span class="hljs-keyword">try</span>:
            image_file = <span class="hljs-built_in">open</span>(filePath, <span class="hljs-string">&quot;rb&quot;</span>)
            image_data_binary = image_file.read()
            <span class="hljs-keyword">return</span> (base64.b64encode(image_data_binary)).decode(<span class="hljs-string">&#x27;ascii&#x27;</span>)
        <span class="hljs-keyword">except</span> Exception <span class="hljs-keyword">as</span> ex:
            <span class="hljs-built_in">print</span>(<span class="hljs-string">&#x27;Failed to save image\\n &#x27;</span> + <span class="hljs-built_in">str</span>(ex))
        
barcodeReaderExamples = BarcodeReaderExamples()
barcodeReaderExamples.readBarcodeImage()
</code>
</pre></div>
    <div class="barcode-read-lcs-result" onclick="BarcodeReadLcsCurtainClick(this)">
        <div>
            <header>
                <span>Recognition result</span>
                <i class="fa fa-times" onclick="BarcodeReadLcsCloseResult(this);"></i>
            </header>
            <article><div><img id="recognitionImage" styles="max-width: 300px;max-height: 300px;"></img></div><div id="recognitionResult"></div></article>
        </div>
    </div>
    <script>
        function BarcodeReadLcsUpload(obj)
        {
            let fileInput = $(obj).children("input[type='file']")[0];
            fileInput.click();
        }
        function BarcodeReadLcsDropped(event, obj)
        {
            let fileInput = $(obj).children("input[type='file']")[0];
            fileInput.files = event.dataTransfer.files;
            BarcodeReadLcsFileSelected(fileInput);
            event.preventDefault();
            return false;
        }
        function selectType(obj)
        {
            $(obj).closest(".barcode-read-lcs").find(".barcode-read-lcs-type").text(obj.value);
        }
        function BarcodeReadLcsFileSelected(obj)
        {
            if(obj.files.length > 0)
            {
                let fileName = obj.value.replace(/.*[\/\\]/, "");
                $(obj).closest(".barcode-read-lcs-controls").find(".barcode-read-lcs-recognize").removeClass("barcode-read-lcs-disabled");
                $(obj).siblings(".barcode-read-lcs-filename").show().children("span").text(fileName);
                $(obj).siblings(".barcode-read-lcs-recognizing").children("span").text(fileName);
                $(obj).closest(".barcode-read-lcs").find(".barcode-read-lcs-code-filename-placeholder").hide();
                $(obj).closest(".barcode-read-lcs").find(".barcode-read-lcs-code-filename-actual").text(fileName).show();
            }
        }
        async function postBarcodeRecognize(postData) {
            let result = await new Promise((resolve, reject) => {
                $.ajax({
                    type: "POST",
                    url: "https://api.products-qa.aspose.app/barcode/recognize/apiRequestRecognize",
                    contentType: false,
                    processData: false,
                    data: postData
                })
                    .done(function(result) {
                        resolve(result);
                    })
                    .fail(function(jqXHR) {
                        reject(new Error(makeErrorMessage(jqXHR)));
                    })
            });
            if (!result.success) {
                throw new Error(result.errorMsg);
            }
            return result.recognizeResultToken;
        };
        function makeErrorMessage(xhr) {
            let message = null;
            if (xhr.status == 0) {
                message = `Connection error: ${xhr.statusText}`;
            } else {
                message = `${xhr.statusText} ${xhr.status}: ${xhr.responseText}`;
            }
            return message;
        }
        AsyncRecognitionStarted = null;
        async function recognizeBarcodeAsync() {
            let button = $("#recognize-button");
            if(button.hasClass("barcode-read-lcs-disabled")) return false;
            if (!window.FormData) {
                console.error('FormData is not supported');
                return;
            }
            let barcodetypeUrl = "DataMatrix";
            if (barcodetypeUrl === "") {
                barcodetypeUrl = button.siblings("select").val();
                barcodetypeUrl = barcodetypeUrl === "DataMatrix" ? "" : barcodetypeUrl;
            }
            let quality = 2;
            let file = button.closest(".barcode-read-lcs-controls").find("input[type='file']")[0].files[0];
            if (!file) {
                console.error('Failed to upload image');
                return;
            }
            if (FileReader && file) {
                var fr = new FileReader();
                fr.onload = async function() {
                    let fileBase64 = fr.result;
                    $("#recognitionImage")[0].src = fileBase64;
                    var test = $("#recognitionImage")[0].src;
                    var data = new FormData();
                    data.append("type", barcodetypeUrl);
                    data.append("quality", quality);
                    data.append("fileBase64", fileBase64);
                    showStateRecognizing();
                    AsyncRecognitionStarted = Date.now();
                    let token = null;
                    try {
                        token = await postBarcodeRecognize(data);
                        let attemptsLeft = 100;
                        while (attemptsLeft > 0 && AsyncRecognitionStarted) {
                            await waitSec(getWaitTimeSec(100 - attemptsLeft));
                            attemptsLeft--;
                            var result;
                            try {
                                result = await tryGetResult(token);
                            } catch (e) {
                                if (e.status === 0) {
                                    // If connection lost
                                    continue;
                                }
                                throw e;
                            }
                            if (result.ready) {
                                if (result.foundBarcodesCount > 0) {
                                    setStateRecognized(result.html);
                                } else {
                                    if (result.errorMsg) {
                                        setStateUnsuccessfulRecognition(result.errorMsg);
                                    } else {
                                        setStateNoBarcodesRecognized(result.html);
                                    }
                                }
                                break;
                            }
                        }
                        if (attemptsLeft === 0) {
                            setStateNoBarcodesRecognized("Timeout");
                        }
                    } catch (e) {
                        console.error(e);
                        if (e.message) {
                            setStateServerError(e.message);
                        }
                    } finally {
                        cancelAsyncRecognitionProcess();
                    }
                }
                fr.readAsDataURL(file);
            }
        }
        function showStateRecognizing() {
            let button = $("#recognize-button");
            let icon = button.closest(".barcode-read-lcs-controls").find(".barcode-read-lcs-drop-icon");
            let preloader = button.closest(".barcode-read-lcs-controls").find(".barcode-read-lcs-drop-preload");
            let recognizingField = button.closest(".barcode-read-lcs-controls").find(".barcode-read-lcs-recognizing");
            let filenameField = button.closest(".barcode-read-lcs-controls").find(".barcode-read-lcs-filename");
            let hint = button.closest(".barcode-read-lcs-controls").find(".barcode-read-lcs-hint");
            preloader.show();
            recognizingField.show();
            icon.hide();
            filenameField.hide();
            hint.hide();
            $("#recognitionResult").html('');
            button.addClass("barcode-read-lcs-disabled");
        }
        async function waitSec(seconds) {
            return new Promise(resolve => setTimeout(resolve, 1000 * seconds));
        };
        function getWaitTimeSec(curAttempt) {
            if (curAttempt === 0) {
                // To prevent too fast laser animation flicker
                return 0.5;
            }
            if (curAttempt < 10) {
                return 0.5;
            }
            return 2;
        };
        async function tryGetResult(token) {
            var test = $("#recognitionImage")[0].src;
            return new Promise((resolve, reject) => {
                $.ajax({
                    type: 'GET',
                    url: "https://api.products-qa.aspose.app/barcode/recognize/recognizeresult/" + token + "?timestamp=" + Date.now(),
                })
                    .done(function(result) {
                        resolve(result);
                    })
                    .fail(function(jqXHR) {
                        const err = new Error(makeErrorMessage(jqXHR));
                        err.status = jqXHR.status;
                        reject(err);
                    });
            });
        }
        function setStateRecognized(htmlSuccessful) {
            let output = htmlSuccessful.replace(/(?:\r\n|\r|\n)/g, "");
            output = output.replace(/<div>.*?<\/div>/g, "");
            output = output.replace(/width.*?%/g, "");
            showRecognitionResult(output);
        }
        function setStateNoBarcodesRecognized(htmlNoBarcodes) {
            showRecognitionResult(htmlNoBarcodes);
        }
        function setStateUnsuccessfulRecognition(htmlUnsuccessful) {
            showRecognitionResult(htmlUnsuccessful);
        }
        function setStateServerError(errorText) {
            showRecognitionResult('Error');
        }
        function showRecognitionResult(html) {
            let button = $("#recognize-button");
            let resultDialog = button.closest(".barcode-read-lcs").find(".barcode-read-lcs-result");
            resultDialog.find("#recognitionResult").html(html);
            resultDialog.slideDown(200);
        }
        function cancelAsyncRecognitionProcess() {
            let button = $("#recognize-button");
            let icon = button.closest(".barcode-read-lcs-controls").find(".barcode-read-lcs-drop-icon");
            let preloader = button.closest(".barcode-read-lcs-controls").find(".barcode-read-lcs-drop-preload");
            let recognizingField = button.closest(".barcode-read-lcs-controls").find(".barcode-read-lcs-recognizing");
            let filenameField = button.closest(".barcode-read-lcs-controls").find(".barcode-read-lcs-filename");
            let hint = button.closest(".barcode-read-lcs-controls").find(".barcode-read-lcs-hint");
            preloader.hide();
            recognizingField.hide();
            icon.show();
            hint.show();
            button.removeClass("barcode-read-lcs-disabled");
            AsyncRecognitionStarted = null;
        }
        function BarcodeReadLcsCurtainClick(obj)
        {
            if($(event.target).is(".barcode-read-lcs-result")) $(obj).hide();
        }
        function BarcodeReadLcsCloseResult(obj)
        {
            $(obj).closest(".barcode-read-lcs-result").slideUp(200);
        }
    </script>
</div>
<!-- END LCS -->
{{< /blocks/products/pf/agp/feature-section2 >}}
{{% blocks/products/pf/agp/feature-section-row title="About Data Matrix code" %}}
<p>
Data Matrix is a two-dimensional (2D) barcode type that is used to encode and store data in a graphical format. Each code is composed of a series of black and white modules arranged in a pattern that can be read by a scanner or other device with an image sensor. The unique pattern on the border serves to identify the location of each cell and decode the information stored in the barcode. Data Matrix is a highly efficient barcode type that is capable of encoding a wide range of data types, including text, numbers, and binary data. It is a versatile barcode type that can be used in a variety of applications, including identification, asset tracking, and supply chain management. One of the key benefits of Data Matrix is its small size and high data density. It can store a large amount of information in a very small space, making it well-suited for use on small or thin products or packaging. Data Matrix barcodes are also resistant to damage, as they can be read even if parts of the barcode are missing or damaged. Specifications for Data Matrix can be found in standards ISO/IEC 16022:2000 and [ISO/IEC 24720:2006].<br>The following information card describes main properties of Data Matrix, its encoding set, structure, size dimensions, capacity, and the error correction mechanism:
</p>
<p>
<a href='https://docs.aspose.com/barcode/info-cards/data-matrix/'>Data Matrix</a>
</p>
{{% /blocks/products/pf/agp/feature-section-row %}}

{{< /blocks/products/pf/agp/feature-section >}}

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="Scan Data Matrix code" sectionDescription="[BarCode Reader App](https://products.aspose.app/barcode/recognize/datamatrix)" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text="No need to download Aspose API" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text="Just insert the source file path" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text="Select Data Matrix code from the dropdown list" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text="Instantly get the Data Matrix code decoded data" >}}

{{% blocks/products/pf/agp/content h2="About Aspose.BarCode for Python via Java API" %}}

Aspose.BarCode is a barcode generator and scanner API. It can easily scan and create linear, 2D, and postal barcodes of various types. Developers can integrate its functionality into any barcode generation and scanning application. Moreover, generated barcodes can be saved in various high-quality image formats. It is a standalone library that does not require installing any additional software.

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Barcode Recognition Symbologies" subTitle="Using Python via Java, One can also read barcode of different symbologies including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/qr/" name="QR" description="QR Code, GS1 QR Code" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/pdf417/" name="PDF417" description="PDF 417, Micro Pdf417, Macro PDF417" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/databar/" name="DATABAR" description="GS1 Databar Expanded, GS1 Databar Expanded Stacked, GS1 DataBar Expanded, GS1 Databar OmniDirectional, GS1 DataBar Stacked, GS1 Databar Stacked OmniDirectional, GS1 DataBar Truncated" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/datamatrix/" name="DATAMATRIX" description="Data Matrix, GS1 Data Matrix" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/ean/" name="EAN" description="EAN-8, EAN-13, EAN-14" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/upc/" name="UPC" description="UPC-A, UPC-E, UPCA GS1 Code 128 Coupon, UPCA GS1 Databar Coupon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/aztec/" name="AZTEC" description="AZTEC" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/codeblock/" name="CODEBLOCK" description="CodablockF, GS1 CodablockF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/code128/" name="CODE128" description="Code 128, GS1-128" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/code16k/" name="CODE16K" description="CODE 16K" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/code32/" name="CODE32" description="ITALIAN PHARMACODE CODE 32" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/code39/" name="CODE39" description="Code 39 Extended, Code 39 Standard" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/code93/" name="CODE93" description="Code 93 Extended, Code 93 Standard" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/onecode/" name="ONECODE" description="USPS ONECODE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/australiapost/" name="AUSTRALIAPOST" description="Australia Post, Australia Poste Parcel" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/deutschepost/" name="DEUTSCHEPOST" description="Deutsche Post Identcode, Deutsche Post Leitcode" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/italianpost25/" name="ITALIANPOST25" description="ITALIAN POST 25" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/rm4scc/" name="RM4SCC" description="ROYALMAIL RM4SCC" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/postnet/" name="POSTNET" description="POSTNET" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/singaporepost/" name="SINGAPOREPOST" description="SINGAPORE POST" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/swisspostparcel/" name="SWISSPOSTPARCEL" description="SWISS POST PARCEL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/dotcode/" name="DOTCODE" description="DOTCODE" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/interleaved2of5/" name="INTERLEAVED2OF5" description="INTERLEAVED 2 OF 5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/datalogic2of5/" name="DATALOGIC2OF5" description="DATALOGIC 2 OF 5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/iata2of5/" name="IATA2OF5" description="IATA 2 OF 5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/matrix2of5/" name="MATRIX2OF5" description="MATRIX 2 OF 5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/standard2of5/" name="STANDARD2OF5" description="STANDARD 2 OF 5" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/isbn/" name="ISBN" description="ISBN" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/ismn/" name="ISMN" description="ISMN" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/issn/" name="ISSN" description="ISSN" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/itf/" name="ITF" description="ITF-6, ITF-14" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/barcode/python-java/recognize/planet/" name="PLANET" description="PLANET" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}

{{< /blocks/products/pf/main-wrap-class >}}
