<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>鈴鹿急行電鉄ホームページ</title>

  <style>
    .wrapper {
      display: flex;
      align-items: center;
      gap: 16px;
    }

    .label {
      display: inline-block;
      background-color: #e53935; /* 赤 */
      color: #fff;               /* 白文字 */
      padding: 8px 14px;
      border-radius: 10px;
      font-weight: 700;
      font-size: 16px;
      line-height: 1;
      text-align: center;
      border: none;
      box-shadow: none;
      user-select: none;
    }

    .map-link {
      color: blue;
      margin-top: 8px; /* 上の行とのすき間 */
      font-size: 14px;
    }

    .map-link a {
      color: blue;
      text-decoration: none;
    }

    .map-link a:hover {
      text-decoration: underline;
    }
  </style>
</head>

<body>

  <h1>鈴鹿急行電鉄ホームページ</h1>

  <!-- 横並びにする wrapper -->
  <div class="wrapper">
    <span class="label">運行情報</span>
    <span>現在、10分以上の遅れはございません</span>
  </div>

  <!-- 下の行（青文字＋リンク） -->
  <div class="map-link">
    地図はこちら
    <a href="https://ku-tetsu.net/438847.html">https://ku-tetsu.net/438847.html</a>
  </div>

</body>
