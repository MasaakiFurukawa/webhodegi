<!DOCTYPE html>
<lang="ja">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="robots" content="noindex">
        <title itemprop="name">Webhodegi_compare_products_page</title>
        <link rel="stylesheet" href="product_stylesheet.css">
      </head>
    
  <body>

<?php //スプレッドシートIDの指定と必要なJSONデータの取得
$data = "https://spreadsheets.google.com/feeds/list/1Lt_0qvHSj-PK2da_AnjU-Xm70W5nvT8OhzUGNy3uuc0/6/public/values?alt=json";
$json = file_get_contents($data);
$json_decode = json_decode($json);
$posts = $json_decode->feed->entry;

//データを配列で取得・格納
$genre = [];
$company_name = [];
$price = [];
$description = [];

foreach ($posts as $post) {
    $genre[] = $post->{'gsx$genre'}->{'$t'};
    $company_name[] = $post->{'gsx$company_name'}->{'$t'};
    $price[] = $post->{'gsx$price'}->{'$t'};
    $description[] = $post->{'gsx$description'}->{'$t'};
}

//取得したJSONデータをソースコードに出力する
for ($i=0; $i<count($genre); $i++) {
    if (!$company_name[$i]) {
        echo '<h3 id="' . $price[$i] . '">' . $genre[$i] . '</h3>';
        continue;
    }
    echo '<h4>' . $company_name[$i] . '</h4>';
    echo '<div class="price"><span>' . $price[$i] . '</span></div>';
    echo '<p>' . $description[$i] . '</p>';
} ?>
</body>
</html>