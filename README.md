# chatgpt

<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>予約フォーム</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- CSSはこのstyleタグの中にまとめています -->
  <style>
    /* 全体の基本設定 */
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f6f8;
      margin: 0;
      padding: 0;
    }

    /* フォーム全体を囲む箱 */
    .container {
      max-width: 500px;
      margin: 40px auto;
      background-color: #ffffff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    /* タイトル */
    h1 {
      text-align: center;
      margin-bottom: 20px;
    }

    /* 各入力グループ */
    .form-group {
      margin-bottom: 15px;
    }

    /* ラベル */
    label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }

    /* 入力欄 */
    input {
      width: 100%;
      padding: 10px;
      font-size: 16px;
      border-radius: 5px;
      border: 1px solid #ccc;
      box-sizing: border-box;
    }

    /* 送信ボタン */
    button {
      width: 100%;
      padding: 12px;
      font-size: 16px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #45a049;
    }

    /* スマホ対応（画面が小さいとき） */
    @media screen and (max-width: 480px) {
      .container {
        margin: 20px;
        padding: 15px;
      }
    }
  </style>
</head>

<body>
  <div class="container">
    <h1>予約フォーム</h1>

    <!-- 予約フォーム -->
    <form>
      <div class="form-group">
        <label>お名前</label>
        <input type="text" placeholder="山田 太郎">
      </div>

      <div class="form-group">
        <label>メールアドレス</label>
        <input type="email" placeholder="example@mail.com">
      </div>

      <div class="form-group">
        <label>電話番号</label>
        <input type="tel" placeholder="090-1234-5678">
      </div>

      <div class="form-group">
        <label>希望日</label>
        <input type="date">
      </div>

      <div class="form-group">
        <label>希望時間</label>
        <input type="time">
      </div>

      <button type="submit">予約する</button>
    </form>
  </div>
</body>
</html>
