---
title: PHP via Java을(를) 통해 GS1 DataBar(Omnidirectional, Stacked Omnidirectional, Expanded, Expanded Stacked, Truncated) 바코드 이미지 스캔
weight: 1510
description: PHP 기반 애플리케이션에서 GS1 DataBar(Omnidirectional, Stacked Omnidirectional, Expanded, Expanded Stacked, Truncated) 바코드을(를) 읽기 위한 PHP 샘플 코드입니다.
lang: ko/
langdirlevel: 2
locales: ar,cs,de,el,es,fr,hi,hu,id,it,ja,ko,nl,pl,pt,ru,sv,th,tr,vi,zh,zh-hant
url: /ko/php-java/databar/recognize/
aliases:
- /ko/php-java/recognize/databar/
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="PHP via Java로 GS1 DataBar 바코드 읽기" h2="PHP via Java API용 서버 측 Aspose.BarCode를 사용하여 PHP에서 GS1 DataBar(Omnidirectional, Stacked Omnidirectional, Expanded, Expanded Stacked, Truncated) 바코드 읽기" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/barcode/headers/aspose_barcode-for-php-java.svg" sourceAdditionalConversionTag="" additionalConversionTag="GS1 DataBar" pfName="Aspose.BarCode" subTitlepfName="for PHP via Java" downloadUrl="" fileiconsmall1="PNG" fileiconsmall2="JPG" fileiconsmall3="BMP" fileiconsmall4="TIFF" fileiconsmall5="SVG" >}}

{{< blocks/products/pf/main-container pfName="Aspose.BarCode " subTitlepfName="PHP via Java 용" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/barcode/aspose_barcode-for-php-java.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-barcode/Aspose.BarCode-for-PHP-via-Java" liveDemosLink="https://products.aspose.app/barcode/family" docsLink="https://docs.aspose.com/barcode/phpjava/" installationsDocsLink="https://docs.aspose.com/barcode/php-java/installation" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/barcode/php/" learnAsLink="https://docs.aspose.com/barcode/phpjava/" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-barcode" >}}

{{% blocks/products/pf/agp/content h2="How to Read GS1 DataBar 바코드 Using PHP via Java" %}}
Java 기반 플랫폼을 위한 강력하고 풍부하며 사용자 친화적인 바코드 라이브러리인 Java를 통해 PHP용 Aspose.BarCode를 사용하여 PHP 애플리케이션 내에서 GS1 DataBar 바코드 바코드를 읽습니다. 바코드 API를 사용하려면 [Aspose 릴리스](https://releases.aspose.com/barcode/php/) 포털에서 최신 버전을 다운로드해야 합니다. Packagist에서 [aspose/barcode](https://packagist.org/packages/aspose/barcode) 패키지를 찾은 다음 작성기를 통해 PHP 프로젝트에 통합할 수도 있습니다.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```json
{    
    "require": {        
        "asposebarcode/aspose_barcode_java_for_php": "dev-master"    
    }
}

```

{{% /blocks/products/pf/agp/code-block %}}{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="PHP에서 GS1 DataBar 바코드 스캔 단계" %}}

{{% blocks/products/pf/agp/text %}}

Aspose.BarCode를 통해 개발자는 몇 줄의 코드로 스트림 또는 이미지에서 GS1 DataBar 바코드 바코드를 읽을 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

<ul><li>Aspose.BarCode.BarCodeReader 클래스의 객체 생성</li><li>GS1 DataBar 바코드을 매개변수로 포함하는 소스 이미지 경로 설정</li><li>DecodeType에서 대상 바코드 유형 지정 두 번째 매개변수로</li><li>판독 결과 반복</li><li>CodeText 속성을 사용하여 바코드 텍스트 가져오기</li></ul>

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

Aspose API는 모든 주요 플랫폼 및 운영 체제에서 지원됩니다. 아래 코드 샘플을 실행하기 전에 시스템이 다음 요구 사항을 준수하는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

<ul><li>Microsoft Windows, Linux 또는 PHP 기반 개발 환경과 호환되는 모든 OS</li></ul>

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid features-section bg-gray">
    <div class="row">
        <div class="container">
            <div class="col-lg-12">
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
            width: 100%;
            height: 100%;
            top: 0;
            position: absolute;
            display: none;
            z-index: 9998;
            -webkit-transition: opacity 400ms ease-in;
            -moz-transition: opacity 400ms ease-in;
            transition: opacity 400ms ease-in;
        }
        .barcode-read-lcs-result > div {
            position: relative;
            margin: 0 auto;
            top: 25%;
            padding: 5px 20px 13px 20px;
            border-radius: 10px;
            box-shadow: 20px 20px 7px rgba(88,88,88,0.8);
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
            <span class="barcode-read-lcs-recognizing">인식<span></span></span>
            <span class="barcode-read-lcs-hint">여기에 파일을 놓거나 클릭하여 찾아보기 *</span>
        </div>
        <div class="barcode-read-lcs-mods">
            <input id="recognize-button" type="button" value="Run code" class="barcode-read-lcs-recognize barcode-read-lcs-disabled" onclick="recognizeBarcodeAsync()" />
        </div>
    </div>
    <p class="barcode-read-lcs-disclaimer">* 파일을 업로드하거나 서비스를 사용하면 <a href='https://about.aspose.com/legal/terms-of-use' rel='nofollow noreferrer' target='_blank'>약관에 동의하게 됩니다. 사용</a> 및 <a href='https://about.aspose.com/legal/privacy-policy' rel='nofollow noreferrer' target='_blank'>개인정보 보호정책</a>.</p>
<div id="code" class="codablock"><h3>Code to be executed - PHP</h3><pre>
    <code class='php hljs'>
<span class="hljs-keyword">try</span>
{
    <span class="hljs-variable">$image_bytes</span> = <span class="hljs-title function_ invoke__">file_get_contents</span>(<span class="hljs-string">"<span class="barcode-read-lcs-code-filename-placeholder">&lt;file name&gt;</span><span class="barcode-read-lcs-code-filename-actual"></span>"</span>);
    <span class="hljs-variable">$image</span> = <span class="hljs-title function_ invoke__">base64_encode</span>(<span class="hljs-variable">$image_bytes</span>);
    <span class="hljs-variable">$reader</span> = <span class="hljs-keyword">new</span> <span class="hljs-title class_">BarCodeReader</span>(<span class="hljs-variable">$image</span>, <span class="hljs-literal">null</span>, <span class="hljs-title class_">DecodeType</span>::<span class="barcode-read-lcs-type">Databar</span>);
    <span class="hljs-title function_ invoke__">forEach</span>(<span class="hljs-variable">$reader</span>-&gt;<span class="hljs-title function_ invoke__">readBarCodes</span>() <span class="hljs-keyword">as</span> <span class="hljs-variable">$res</span>)
    {
        <span class="hljs-keyword">print</span>(<span class="hljs-string">&quot;Code Text : &quot;</span>.<span class="hljs-variable">$res</span>-&gt;<span class="hljs-title function_ invoke__">getCodeTypeName</span>().<span class="hljs-string">&quot;\\n&quot;</span>);
        <span class="hljs-keyword">print</span>(<span class="hljs-string">&quot;\\n&quot;</span>);
        <span class="hljs-keyword">print</span>(<span class="hljs-string">&quot;Code Type : &quot;</span>.<span class="hljs-variable">$res</span>-&gt;<span class="hljs-title function_ invoke__">getCodeText</span>().<span class="hljs-string">&quot;\\n&quot;</span>);
    }

}
<span class="hljs-keyword">catch</span> (BarcodeException <span class="hljs-variable">$e</span>)
{
    <span class="hljs-keyword">print</span>(<span class="hljs-variable">$e</span>-&gt;<span class="hljs-title function_ invoke__">getMessage</span>());
}
</code>
</pre></div>
    <div class="barcode-read-lcs-result" onclick="BarcodeReadLcsCurtainClick(this)">
        <div>
            <header>
                <span>인식 결과</span>
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
            let barcodetypeUrl = "Databar";
            if (barcodetypeUrl === "") {
                barcodetypeUrl = button.siblings("select").val();
                barcodetypeUrl = barcodetypeUrl === "Databar" ? "" : barcodetypeUrl;
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
            </div>
        </div>
    </div>
</div>

{{< blocks/products/pf/agp/other-symbologies-section title="Other Supported Barcode Recognition Symbologies" subTitle="Using PHP via Java, One can also read barcode of different symbologies including the following." >}}

<p class="tl d-block" style="margin: 15px 0 7px 0 !important;">2D:</p>
<div class="row other-converters">
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/pdf417/recognize/" name="PDF417" description="PDF417 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/qr/recognize/" name="QR" description="QR 코드, GS1 QR 코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/datamatrix/recognize/" name="Data Matrix" description="Data Matrix 코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/aztec/recognize/" name="Aztec" description="Aztec 코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/swiss-qr/recognize/" name="Swiss QR" description="Swiss QR 청구서" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/dotcode/recognize/" name="DotCode" description="DotCode 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/hibc/recognize/" name="HIBC" description="HIBC (의료 산업 바코드)" >}}
</div>
<p class="tl d-block" style="margin: 15px 0 7px 0 !important;">Linear:</p>
<div class="row other-converters">
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/codablock/recognize/" name="Codablock-F" description="Codablock-F 및 GS1 Codablock-F 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/databar/recognize/" name="GS1 DataBar" description="GS1 DataBar(Omnidirectional, Stacked Omnidirectional, Expanded, Expanded Stacked, Truncated) 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/itf/recognize/" name="ITF" description="인터리브 2-of-5(ITF) 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/ean/recognize/" name="EAN" description="EAN (국제 문서 번호) 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/upc/recognize/" name="UPC" description="UPC(범용 제품 코드) 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/code128/recognize/" name="GS1 Code 128" description="GS1 Code 128 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/code39/recognize/" name="Code 39" description="Code 39 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/code16k/recognize/" name="Code 16K" description="Code 16K 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/code32/recognize/" name="Code 32" description="이탈리아어 Pharmacode(Code 32) 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/code93/recognize/" name="Code 93" description="Code 93 확장 및 Code 93 표준 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/onecode/recognize/" name="USPS OneCode" description="USPS OneCode 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/standard2of5/recognize/" name="Standard 2 of 5" description="Standard 2 of 5 (Industrial 2 of 5) 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/isbn/recognize/" name="ISBN" description="ISBN 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/ismn/recognize/" name="ISMN" description="ISMN 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/issn/recognize/" name="ISSN" description="ISSN 바코드" >}}
</div>
<p class="tl d-block" style="margin: 15px 0 7px 0 !important;">Postal:</p>
<div class="row other-converters">
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/australia-post/recognize/" name="Australia Post" description="Australia Post 바코드 및 Australia Post eParcel" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/deutsche-post/recognize/" name="Deutsche Post" description="Deutsche Post Identcode 및 Deutsche Post Leitcode" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/rm4scc/recognize/" name="RM4SCC" description="Royal Mail 4주 고객 코드(RM4SCC)" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/postnet/recognize/" name="Postnet" description="Postnet 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/royal-mail/recognize/" name="Royal Mail" description="Royal Mail 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/singapore-post/recognize/" name="Singapore Post" description="Singapore Post 바코드" >}}
{{< blocks/products/pf/agp/other-symbologies-section-item href="/barcode/ko/php-java/swiss-post-parcel/recognize/" name="Swiss Post Parcel" description="Swiss Post Parcel" >}}
</div>

{{< /blocks/products/pf/agp/other-symbologies-section >}}
{{< /blocks/products/pf/main-container >}}

{{< /blocks/products/pf/main-wrap-class >}}