<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ブリーチの説明</title>
    <link rel="stylesheet" href="styles.css">
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
            <img src="bleach-character.jpg" alt="ブリーチのキャラクター" />
        </section>
    </main>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem;
    text-align: center;
}

main {
    padding: 2rem;
}

h1, h2 {
    color: #333;
}

#description-section, #image-section {
    margin-bottom: 2rem;
}

img {
    max-width: 100%;
    height: auto;
    display: block;
    margin-top: 1rem;
}

