---
layout: page
title: Про нас
permalink: /03-about/
---
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column {
  float: left;
  width: 33.3%;
  margin-bottom: 16px;
  padding: 0 8px;
}

@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

.container {
  padding: 0 16px;
}

.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: #555;
}
</style>
</head>
<body>

<div class="row">
  <div class="column">
    <div class="card">
      <img src="/images/about/artem.jpg" alt="Артем" style="width:100%">
      <div class="container">
        <h2>Артем</h2>
        <p class="title">Оператор</p>
        <p>Надання комплексної послуги і максимально якісний сервіс.</p>
        <p>artem@tarko.pp.ua</p>
        <p><button class="button">+38 096-100-10-10</button></p>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="card">
      <img src="/images/about/bohdan.jpg" alt="Богдан" style="width:100%">
      <div class="container">
        <h2>Богдан</h2>
        <p class="title">Оператор</p>
        <p>Надання комплексної послуги і максимально якісний сервіс.</p>
        <p>bohdan@tarko.pp.ua</p>
        <p><button class="button">+38 096-100-10-10</button></p>
      </div>
    </div>
  </div>
  <div class="column">
    <div class="card">
      <img src="/images/about/dmytro.jpg" alt="Дмитро" style="width:100%">
      <div class="container">
        <h2>Дмитро</h2>
        <p class="title">Оператор</p>
        <p>Надання комплексної послуги і максимально якісний сервіс.</p>
        <p>dmytro@tarko.pp.ua</p>
        <p><button class="button">+38 096-100-10-10</button></p>
      </div>
    </div>
  </div>
</div>

</body>
</html>



