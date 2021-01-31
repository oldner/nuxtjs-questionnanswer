<template>
  <div>
    <div class="wrapper">
      <div class="navbar">
        <div class="navbar-logo">Sorunum Var!</div>
        <div class="navbar-menu">
          <ul>
            <li><a href="#">ANASAYFA</a></li>
            <li><a href="#">SORUNLAR</a></li>
            <li><a href="#">İSTATİSTİKLER</a></li>
            <li><a href="#">BAĞIŞ</a></li>
            <li><a href="#">HAKKIMIZDA</a></li>
            <li><a href="#">İLETİŞİM</a></li>
          </ul>
        </div>
      </div>
      <div class="jumbotron">
        <div class="jumbo-left">
          <h1>Sorunum Var!</h1>
          <p>
            topluluğu, el ele vererek insanların yaşadağı sorunlara çözüm
            oluşturmak için kuruldu. Biz, sadece insanları derin uykularından
            (bkz: derin uyku) uyandırmak istiyoruz. Eğer senin de bir sorunun
            varsa veya bir değişime önayak olmak istiyorsan ücretsiz olarak
            hemen bize katıl!
          </p>
        </div>
        <div class="jumbo-right">
          <img src="@/assets/jumbo.png" alt="" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Raleway:wght@300;400;500;600&display=swap");

HTML,
body {
  width: 100%;
  margin: 0;
  padding: 0;
}

.wrapper {
  background-color: #f5f5f5;
}

.navbar {
  display: flex;
  justify-content: space-between;
  width: 95%;
  margin: 0px auto;
  padding: 20px 0;
  font-family: "Raleway";
  background-color: #f5f5f5;
}

.navbar-menu ul {
  list-style: none;
}

.navbar-menu ul li {
  display: inline-block;
  margin-left: 10px;
}

.navbar-menu ul li a {
  text-decoration: none;
  color: black;
  font-size: 14pt;
  font-weight: 600;
}

.jumbotron {
  display: flex;
  justify-content: space-evenly;
  width: 85%;
  height: 520px;
  margin: 0px auto;
  padding: 20px 0;
  background-color: #f5f5f5;
  font-family: "Raleway";
  background-image: radial-gradient(
    circle at 10px -15px,
    transparent 20px,
    f5f5f5 21px
  );
}

.jumbo-left {
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: center;
}

.jumbo-left h1 {
  color: #f07a7a;
  font-size: 30pt;
}

.jumbo-left p {
  margin-top: 25px;
  font-weight: 600;
  font-size: 16pt;
}
</style>

