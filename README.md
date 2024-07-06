<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ブリーチの説明</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* 画像を横に並べるスタイル */
        .image-gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .image-gallery img {
            width: calc(25% - 10px);
            height: auto;
            object-fit: cover;
        }
        @media (max-width: 768px) {
            .image-gallery img {
                width: calc(50% - 10px);
            }
        }
        @media (max-width: 480px) {
            .image-gallery img {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>ブリーチの説明</h1>
    </header>
    <main>
        <section id="description-section">
            <h2>ブリーチとは</h2>
            <p>ブリーチは、久保帯人によって描かれた日本の漫画作品で、死神代行の物語を描いています。</p>
        </section>
        <section id="image-section">
            <h2>ブリーチのキャラクター</h2>
            <div class="image-gallery">
                <!-- 以下、70枚の画像を追加 -->
                <!-- bleach-character1.jpg から bleach-character70.jpg までの画像を表示 -->
                <!-- 画像のファイル名やパスは実際のものに置き換えてください -->
                <?php
                for ($i = 1; $i <= 70; $i++) {
                    echo '<img src="images/bleach-character' . $i . '.jpg" alt="Bleach Character ' . $i . '">';
                }
                ?>
            </div>
        </section>
    </main>
</body>
</html>
