<!DOCTYPE html>
<html lang="ja">
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
<title>運行情報ラベル</title>
<style>
   .wrapper {
    display: flex;
    align-items: center;   /* 縦位置を中央揃え */
    gap: 16px;             /* ラベルと文字の間のすき間 */
  }

  .label {
    background-color: #e53935; /* 赤 */
    color: #fff;               /* 白文字 */
    padding: 8px 14px;
    border-radius: 10px;
    font-weight: 700;
    font-size: 16px;
  }
.label {
  display: inline-block;
  background-color: #e53935; /* 赤 */
  color: #fff;               /* 白文字 */
  padding: 8px 14px;        /* 上下8px 左右14px */
  border-radius: 10px;      /* 角丸 */
  border: none;             /* 枠線なし */
  font-weight: 700;         /* 太字 */
  font-size: 16px;
  line-height: 1;
  text-align: center;
  box-shadow: none;         /* 影を付けたければ指定 */
  user-select: none;
}
</style>
</head>
<body>
  <h1>鈴鹿急行電鉄ホームページ</h1>
  <span class="label">運行情報</span>
   <span>あいうえおかきくけこさしすせそ</span>
</body>
</html>
