# matoshree-mobile-repairing-and-accessories-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Matoshree Mobile | Repairing & Accessories</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:Arial, Helvetica, sans-serif;
  scroll-behavior:smooth;
}

body{
  background:#f8f7f4;
  color:#171717;
}

/* HEADER */
header{
  position:sticky;
  top:0;
  z-index:999;
  background:#111111;
  padding:13px 6%;
  display:flex;
  align-items:center;
  justify-content:space-between;
  box-shadow:0 3px 18px rgba(0,0,0,.25);
}

.logo{
  display:flex;
  align-items:center;
  gap:10px;
  color:white;
}

.logo-icon{
  width:44px;
  height:44px;
  border:2px solid #d4af37;
  border-radius:12px;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:23px;
  background:#1b1b1b;
}

.logo-text{
  font-size:19px;
  font-weight:bold;
}

.logo-text span{
  color:#d4af37;
}

nav a{
  text-decoration:none;
  color:#fff;
  margin-left:20px;
  font-size:14px;
  transition:.3s;
}

nav a:hover{
  color:#d4af37;
}

/* HERO */
.hero{
  min-height:88vh;
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
  padding:50px 6%;
  background:
    linear-gradient(rgba(0,0,0,.72),rgba(0,0,0,.78)),
    linear-gradient(135deg,#242424,#0b0b0b);
  color:white;
}

.hero-content{
  max-width:850px;
}

.hero-logo{
  width:105px;
  height:105px;
  margin:0 auto 25px;
  border-radius:28px;
  border:2px solid #d4af37;
  background:#171717;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:55px;
  box-shadow:0 10px 35px rgba(212,175,55,.18);
}

.hero h1{
  font-size:50px;
  letter-spacing:.5px;
  margin-bottom:12px;
}

.hero h1 span{
  color:#d4af37;
}

.hero h2{
  color:#e8e8e8;
  font-size:23px;
  font-weight:normal;
  margin-bottom:18px;
}

.hero p{
  color:#cfcfcf;
  line-height:1.8;
  font-size:17px;
  max-width:680px;
  margin:auto;
}

.buttons{
  margin-top:30px;
}

.btn{
  display:inline-block;
  text-decoration:none;
  padding:14px 27px;
  margin:6px;
  border-radius:30px;
  background:#d4af37;
  color:#111;
  font-weight:bold;
  transition:.3s;
}

.btn:hover{
  transform:translateY(-3px);
  background:#fff;
}

.btn-dark{
  background:transparent;
  border:1px solid #d4af37;
  color:#fff;
}

/* COMMON SECTION */
section{
  padding:75px 6%;
}

.section-title{
  text-align:center;
  margin-bottom:45px;
}

.section-title h2{
  font-size:34px;
  margin-bottom:10px;
}

.section-title h2 span{
  color:#b08a16;
}

.section-title p{
  color:#6b6b6b;
}

/* SERVICES */
.services{
  background:#f8f7f4;
}

.cards{
  max-width:1100px;
  margin:auto;
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:23px;
}

.card{
  background:#fff;
  border-radius:18px;
  padding:32px 22px;
  text-align:center;
  border:1px solid #eee;
  box-shadow:0 8px 25px rgba(0,0,0,.07);
  transition:.3s;
}

.card:hover{
  transform:translateY(-7px);
  box-shadow:0 14px 30px rgba(0,0,0,.12);
}

.card-icon{
  width:65px;
  height:65px;
  margin:0 auto 18px;
  border-radius:18px;
  background:#111;
  color:#d4af37;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:31px;
}

.card h3{
  font-size:20px;
  margin-bottom:10px;
}

.card p{
  color:#707070;
  line-height:1.6;
  font-size:14px;
}

/* ABOUT */
.about{
  background:#111;
  color:white;
}

.about .section-title p{
  color:#aaa;
}

.about-box{
  max-width:850px;
  margin:auto;
  text-align:center;
  line-height:1.9;
  color:#d2d2d2;
  font-size:16px;
}

/* FEATURES */
.features{
  background:#eeeae0;
}

.feature-grid{
  max-width:950px;
  margin:auto;
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:18px;
}

.feature{
  background:white;
  padding:22px;
  border-radius:15px;
  display:flex;
  align-items:center;
  gap:13px;
  box-shadow:0 5px 18px rgba(0,0,0,.06);
  font-weight:bold;
}

.feature-icon{
  color:#b08a16;
  font-size:23px;
}

/* CONTACT */
.contact{
  background:#f8f7f4;
}

.contact-box{
  max-width:800px;
  margin:auto;
  text-align:center;
  background:#111;
  color:white;
  border-radius:22px;
  padding:45px 25px;
  box-shadow:0 12px 35px rgba(0,0,0,.15);
}

.contact-box h2{
  font-size:30px;
  margin-bottom:14px;
}

.contact-box p{
  color:#cfcfcf;
  margin:10px;
}

.phone{
  color:#d4af37;
  font-size:25px;
  font-weight:bold;
  margin:20px 0;
}

/* FOOTER */
footer{
  background:#080808;
  color:#999;
  text-align:center;
  padding:25px 15px;
  font-size:13px;
}

footer strong{
  color:#d4af37;
}

/* MOBILE */
@media(max-width:768px){

  header{
    padding:12px 5%;
  }

  nav{
    display:none;
  }

  .logo-text{
    font-size:17px;
  }

  .hero{
    min-height:85vh;
    padding:40px 5%;
  }

  .hero h1{
    font-size:36px;
  }

  .hero h2{
    font-size:19px;
  }

  .hero p{
    font-size:15px;
  }

  .hero-logo{
    width:85px;
    height:85px;
    font-size:43px;
  }

  section{
    padding:60px 5%;
  }

  .section-title h2{
    font-size:29px;
  }

  .cards{
    grid-template-columns:1fr;
  }

  .feature-grid{
    grid-template-columns:1fr;
  }

}
</style>
</head>

<body>

<!-- HEADER -->
<header>

  <div class="logo">

    <div class="logo-icon">
      📱
    </div>

    <div class="logo-text">
      MATOSHREE <span>MOBILE</span>
    </div>

  </div>

  <nav>
    <a href="#home">Home</a>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

</header>


<!-- HERO -->
<section class="hero" id="home">

  <div class="hero-content">

    <div class="hero-logo">
      📱
    </div>

    <h1>
      Matoshree <span>Mobile</span>
    </h1>

    <h2>
      Repairing & Accessories
    </h2>

    <p>
      Your trusted destination for professional mobile
      repairing services and quality smartphone accessories.
    </p>

    <div class="buttons">

      <a href="#services" class="btn">
        Explore Services
      </a>

      <a href="tel:1234567890" class="btn btn-dark">
        📞 Call Now
      </a>

    </div>

  </div>

</section>


<!-- SERVICES -->
<section class="services" id="services">

  <div class="section-title">

    <h2>
      Our <span>Services</span>
    </h2>

    <p>
      Complete solutions for your mobile needs
    </p>

  </div>


  <div class="cards">

    <div class="card">

      <div class="card-icon">
        🛠️
      </div>

      <h3>Mobile Repairing</h3>

      <p>
        Professional mobile repair and service solutions
        for common smartphone problems.
      </p>

    </div>


    <div class="card">

      <div class="card-icon">
        🔋
      </div>

      <h3>Battery Replacement</h3>

      <p>
        Battery replacement and related smartphone
        service solutions.
      </p>

    </div>


    <div class="card">

      <div class="card-icon">
        🛡️
      </div>

      <h3>Screen Protection</h3>

      <p>
        Screen protection and useful accessories
        for everyday smartphone safety.
      </p>

    </div>


    <div class="card">

      <div class="card-icon">
        🔌
      </div>

      <h3>Chargers & Cables</h3>

      <p>
        Chargers, charging cables and other mobile
        essentials.
      </p>

    </div>


    <div class="card">

      <div class="card-icon">
        🎧
      </div>

      <h3>Audio Accessories</h3>

      <p>
        Earphones and other useful audio accessories
        for your smartphone.
      </p>

    </div>


    <div class="card">

      <div class="card-icon">
        📱
      </div>

      <h3>Mobile Accessories</h3>

      <p>
        A range of useful smartphone accessories
        for everyday use.
      </p>

    </div>

  </div>

</section>


<!-- ABOUT -->
<section class="about" id="about">

  <div class="section-title">

    <h2>
      About <span>Matoshree Mobile</span>
    </h2>

    <p>
      Mobile Repairing & Accessories
    </p>

  </div>


  <div class="about-box">

    <p>
      Matoshree Mobile is a local mobile repairing and
      accessories store providing convenient solutions
      for smartphone users.
    </p>

    <br>

    <p>
      From mobile repairs and battery services to chargers,
      cables, earphones and other accessories, customers
      can find useful mobile solutions under one roof.
    </p>

  </div>

</section>


<!-- FEATURES -->
<section class="features">

  <div class="section-title">

    <h2>
      Why <span>Choose Us?</span>
    </h2>

    <p>
      Service you can rely on
    </p>

  </div>


  <div class="feature-grid">

    <div class="feature">
      <div class="feature-icon">✓</div>
      Professional Mobile Services
    </div>

    <div class="feature">
      <div class="feature-icon">✓</div>
      Quality Accessories
    </div>

    <div class="feature">
      <div class="feature-icon">✓</div>
      Convenient Local Service
    </div>

    <div class="feature">
      <div class="feature-icon">✓</div>
      Customer-Friendly Service
    </div>

  </div>

</section>


<!-- CONTACT -->
<section class="contact" id="contact">

  <div class="contact-box">

    <h2>
      Visit Matoshree Mobile
    </h2>

    <p>
      📍 Shop Location
    </p>

    <p>
      Location details will be added
    </p>

    <div class="phone">
      📞 1234567890
    </div>

    <p>
      Call us for mobile repairing & accessories
    </p>

    <a href="tel:1234567890" class="btn">
      Call Now
    </a>

  </div>

</section>


<!-- FOOTER -->
<footer>

  <p>
    © 2026 <strong>Matoshree Mobile</strong>
  </p>

  <p>
    Repairing & Accessories
  </p>

</footer>

</body>
</html>
