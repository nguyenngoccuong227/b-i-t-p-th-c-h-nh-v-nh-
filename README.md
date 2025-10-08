<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=5.0">
  <title>Bố cục hình chữ nhật</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: white;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .container {
      display: flex;
      gap: 1px; /* khoảng cách giữa các cột */
      align-items: center; /* các hình chữ nhật lấy trọng tâm cân   */
    }

    .box {
      width: 100px;
      background-color: #666;
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: 25px;
    }

    .h20 { height: 20vh; }
    .h30 { height: 30vh; }
    .h15 { height: 15vh; }
    .h35 { height: 35vh; }
    .h50 { height: 50vh; }
  </style>
</head>
<body>
  <div class="container">
    <div class="box h20">20vh</div>
    <div class="box h30">30vh</div>
    <div class="box h15">15vh</div>
    <div class="box h35">35vh</div>
    <div class="box h50">50vh</div>
    <div class="box h20">20vh</div>
  </div>
</body>
</html>

