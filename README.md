<!DOCTYPE html>
<html>
<head>
  <title>My Art Portfolio</title>

  <style>
    body {
      background: #111;
      color: white;
      font-family: Arial;
      margin: 0;
    }

    h1 {
      text-align: center;
      padding: 20px;
    }

    .row {
      margin: 20px;
    }

    .row h2 {
      margin-left: 10px;
    }

    .row-posters {
      display: flex;
      overflow-x: auto;
      padding: 10px;
    }

    .row-posters img {
      width: 200px;
      margin-right: 10px;
      border-radius: 5px;
      transition: transform 0.3s;
    }

    .row-posters img:hover {
      transform: scale(1.1);
    }
  </style>

</head>

<body>

  <h1>My Art Portfolio</h1>

  <div class="row">
    <h2>My Artwork</h2>

    <div class="row-posters">
      <img src="1.png">
      <img src="2.png">
      <img src="3.png">
    </div>
  </div>

</body>
</html>
