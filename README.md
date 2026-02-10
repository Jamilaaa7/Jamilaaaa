<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Full Background Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header class="header">
    <!-- Hamburger -->
    <div class="hamburger" id="hamburger">&#9776;</div>

    <!-- Logo + Search -->
    <div class="center-block">
        <a href="index.html" class="logo">
            <img src="images/4.jpg" alt="Logo">
        </a>

        <div class="search-box">
            <input type="text" placeholder="Search...">
            <button>Search</button>
        </div>
    </div>

    <!-- Navigation -->
    <div class="nav-links" id="navLinks">
        <ul>
            <li><a href="#">HOME</a></li>
            <li><a href="#">ABOUT</a></li>
            <li><a href="#">SERVICE</a></li>
            <li><a href="#">REVIEWS</a></li>
            <li><a href="#">CONTACT</a></li>
        </ul>
    </div>
</header>

<!-- HERO SECTION -->
<main>
    <section class="hero">
        <div class="text-box">
            <h1>WHAT WE ARE ACTUALLY</h1>
            <p>
                We provide end-to-end digital services, specializing in graphic design,
                creative campaigns, and custom website development.
            </p>
            <p>
                From eye-catching front-end interfaces to powerful and secure back-end systems,
                we build solutions that elevate your brand and drive results.
            </p>
            <a href="#" class="hero-btn">Explore</a>
        </div>
    </section>
<!-- Service -->
<section class="services">
  <h1>Services We Offer</h1>
  <p>jfuidfiuredhyguesrugyserughauerhf</p>

  <div class="row">
    <div class="services-col">
      <h3>Graphic Design</h3>
      <p>
        We offer Logo design & brand identity, Social media graphics & ad creatives,
        Marketing materials (flyers, brochures, posters), Website & app UI design,
        Presentation & pitch deck design and Custom illustrations & visual assets.
      </p>
    </div>

    <div class="services-col">
      <h3>Website Development</h3>
      <p>
        We provide professional web development services focused on creating fast,
        secure, and user-friendly websites. Responsive layouts, clean code, SEO,
        accessibility, and scalability are our priority.
      </p>
    </div>

    <div class="services-col">
      <h3>Ad Campaigns on Social Platforms</h3>
      <p>
        We set up high-performing ad campaigns with proper targeting, creatives,
        tracking, and optimization to maximize reach and ROI.
      </p>
    </div>
  </div>
</section>
<!-- About -->
<section class="about">
  <h1 class="about-title">About Us</h1>
  <p class="about-text">
    We are a passionate team of designers and developers dedicated to creating
    stunning visuals and powerful digital solutions.
  </p>

  <div class="about-row">

    <div class="about-col">
      <div class="about-img">
        <img src="images/5.jpg" alt="Our Mission">
      </div>
      <h3>Our Mission</h3>
      <p>
        Our mission is to empower businesses and individuals with creative design
        and innovative technology solutions that drive success and growth.
      </p>
    </div>

    <div class="about-col">
      <div class="about-img">
        <img src="images/6.jpg" alt="Our Vision">
      </div>
      <h3>Our Vision</h3>
      <p>
        Our vision is to be a leading design and development agency known for
        delivering exceptional quality, creativity, and customer satisfaction.
      </p>
    </div>

    <div class="about-col">
      <div class="about-img">
        <img src="images/7.jpg" alt="Our Values">
      </div>
      <h3>Our Values</h3>
      <p>
        We value creativity, integrity, collaboration, and excellence in everything
        we do. We are committed to long-term client relationships built on trust.
      </p>
    </div>

  </div>
</section>



  </div>

</section>

     
</main>

<script>
    const hamburger = document.getElementById("hamburger");
    const navLinks = document.getElementById("navLinks");

    hamburger.addEventListener("click", () => {
        navLinks.classList.toggle("active");
    });
</script>

</body>
</html>
