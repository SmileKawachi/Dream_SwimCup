# 水夢杯ホームページ
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>水夢杯ホームページ</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">
    <style>
        body {
            background: url('haikei.JPG') center/cover no-repeat fixed;
            color: #fffafa;
            font-size: 1.5em;
            margin: 0;
        }

        .red { color: #ff0000; }
        .grey { color: #ffffff; background: #999999; }
        .yellow { color: #ff0000; background: #ffff00; }
        .blue { color: #0000ff; }
        .waku {
            border: 2px dotted #99cc66;
            line-height: 200%;
            padding: 10px;
        }

        main {
            background-color: rgba(255, 255, 255, 0.5);
            padding: 20px;
        }

        section {
            background-color: rgba(0, 255, 0, 0.3);
            padding: 15px;
        }

        .blinking {
            animation: blink 1.5s ease-in-out infinite alternate;
        }
        
        @keyframes blink {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        a {
            color: red;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        p.note {
            display: none;
        }

        @media screen and (max-width: 540px), screen and (orientation: portrait) {
            p.note { display: block; }
        }
    </style>
</head>
<body>

    <p class="note">モバイル端末をお使いの場合は、画面を横向きにするとより見やすくご覧頂けます。</p>

    <main>
        <h1 class="grey blinking">!!! 2026/02/** 第二回 水夢杯 開催 !!!</h1>
        
        <h2 class="yellow">第二回 水夢杯 募集要項</h2>
        <h2>
            <a href="2次要項.pdf" target="_blank">募集要項</a><br>
            <a href="2025年_第1回水夢杯ランキング.pdf" target="_blank">第一回大会ランキング</a>
        </h2>
        
        <section>
            <p class="yellow">以下にPDF,Excel形式の申し込み用紙を用意してあります。</p>
            <p class="yellow">印刷用紙に記入する方はPDFを、PC等から電子データにて送付の方はExcelをご使用ください</p>
            <p><a href="仮申し込み用紙.pdf" target="_blank">【PDF】申込用紙</a>
               <a href="仮申し込み用紙.xlsx" target="_blank">【Excel】申込用紙</a></p>
            <p>申し込みは以下メールボタンまたは、<strong>SmileKawachi@gmail.com</strong> へ送付願います。</p>
            <h2><a href="mailto:smilekawachi@gmail.com?cc=laevatein2007@yahoo.co.jp&amp;subject=連絡&amp;body=クラブ参加願いです。">メール送信</a></h2>
        </section>

        <a href="gazou.JPG" target="_blank">
            <img src="gazou.JPG" alt="サンプル画像" width="600">
        </a>
    </main>

    <footer>
        <p>Copyright 2025/04/20 R. Yamashita</p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js"></script>
</body>
</html>
