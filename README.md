# 水夢杯ホームページ
<html lang="ja" data-loaded="false" data-scrolled="false" data-spmenu="closed">
<head>
<meta charset="UTF-8">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=EmulateIE10" />
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<!--ここから上はお決まりの定型文です-->

<!--ここからが表現の書式などを決めるcssという部分-->
<style type="text/css">
p {
color: #fffafa;
font-size: 1.5em;
}

.red {color:#ff0000;}
.grey {color:#ffffff; background:#999999;}
.snow {color:#fffafa;}
.yellow {color:#ff0000; background:#ffff00;}
.blue {color:#0000ff;}
.white {color:#ffffff; blinking;}
.waku {border:2px dotted #99cc66;
line-height: 200%;
padding: 10px;}

main {
background-color: rgba(255, 255, 255, 0.5);
}

section {
background-color: rgba(0, 225, 0, 0.3);
}

/* 点滅 */
.blinking{
-webkit-animation:blink 1.5s ease-in-out infinite alternate;
-moz-animation:blink 1.5s ease-in-out infinite alternate;
animation:blink 1.5s ease-in-out infinite alternate;
}
@-webkit-keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}
@-moz-keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}
@keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}

#wrap {background:none} /*PC用の背景はオフ*/
/*背景を表示させる部分*/
body::before {
content:"";
display:block;
position:fixed;
top:0;
left:0;
z-index:-1;
width:100%;
height:100vh;
background:url(haikei.JPG) center/cover no-repeat;
-webkit-background-size:cover;/*Android4*/
}

a.p:hover {
position: relative;
text-decoration: none;
}
a.p span {
display: none;
position: relative;
top: -0.5em;
left: 2em;
}
a.p:hover span {
border: none;
display: block;
width: 800px;
}

@media screen and (min-width: 540px),
screen and (orientation: landscape) {
p.note { display: none; }
}

</style>
<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">
</head>
<body>
<p class="note">
モバイル端末をお使いの場合は、画面を横向きにすると
より見やすくご覧頂けます。
</p>

<!--ここ上は、ほぼそのまま使います！-->

<!--QRコードの挿入例-->
<!--
<p align="left"> <img src="QR_2025Apr18.png" alt="アクセス用QRコード" width="100">アクセス用QRコード</p>
-->

<!--流れ文字の挿入例-->
<h1><span class="gray"><marquee behavior="left">!!! 2026/02/**　第二回　水夢杯開催!!!</marquee></span></h1>

<!--ここから下が、本体部分-->
    
<h2><span class="white">第二回　水夢杯　募集要項</span></h2>
<h2><a href="2次要項.pdf" target="_blank">募集要項</a><br>
<a href="2025年_第1回水夢杯ランキング.pdf" target="_blank">第一回大会ランキング</a><br></h2>
<div class="section">
    <p><span class="yellow">以下にPDF,Excel形式の申し込み用紙を用意してあります。</p>
    <p>印刷用紙に記入する方はする方はPDFを、PC等から電子データにて送付の方はExcelをご使用ください</span></p>
    <p><a href="仮申し込み用紙.pdf" target="_blank">【PDF】申込用紙</a>
    <a href="仮申し込み用紙.xlsx" target="_blank">【Excel】申込用紙</a><br>    
    <p>申し込みは以下メールボタンまたは、SmileKawachi＠gmail.com へ送付願います</span></p>
    <h2><a href="mailto:smilekawachi@gmail.com?cc=laevatein2007@yahoo.co.jp&amp;subject=連絡&amp;body=クラブ参加願いです。">メール送信</a></h2>
    
    </div>




<a href="gazou.JPG" target="_blank"><img src="gazou.JPG" alt="サンプル画像" width="600" /></a>   

<br><br><br><br><br><br><br><br><br>





<br><br><br>








<br><br><br><br><br><br><br><br><br>





<br><br>

<br><br><br><br><br><br>

<!--本体はここまで-->


<!--画面に空白地帯を作って、背景が見えるようにしています-->
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>



<!-- フッタ -->
<footer>
<p>Copyright 2025/04/20 R. Yamashita</p>
</footer>

<!--HPにさまざまなJavaScriptを呼び込むための書式-->
<script src="https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js" type="text/javascript"></script>

<script type='text/javascript' src='https://torokoid.github.io/shiba/jquery.js?ver=1.12.4'></script>
<script src="https://torokoid.github.io/shiba/jquery.goup.min.js"></script>
<script src="https://torokoid.github.io/shiba/my.js"></script>
    
    </body>
    
</html>
