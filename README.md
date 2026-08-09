# Varun-Roy
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Vanya Makeovers | Premium Salon in Faridabad</title>
<meta name="description" content="Vanya Makeovers is a premium beauty salon in Sector 8, Faridabad offering hair styling, bridal makeup, facials and complete makeovers. Rated 4.9★. Book your appointment today.">
<meta name="keywords" content="Salon in Faridabad, Beauty salon in Sector 8 Faridabad, Makeup artist in Faridabad, Vanya Makeovers Faridabad, Bridal makeup Faridabad">

<meta property="og:title" content="Vanya Makeovers | Premium Salon in Faridabad">
<meta property="og:description" content="Where Beauty Meets Elegance. A premium beauty and makeover experience in Sector 8, Faridabad.">
<meta property="og:type" content="website">

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "BeautySalon",
  "name": "Vanya Makeovers",
  "image": "",
  "telephone": "+91-9310956711",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "2416, Near Hanuman Mandir, CISF, Sector 8",
    "addressLocality": "Faridabad",
    "addressRegion": "Haryana",
    "postalCode": "121006",
    "addressCountry": "IN"
  },
  "openingHours": "Mo-Su 10:00-20:00",
  "aggregateRating": {
    "@type": "AggregateRating",
    "ratingValue": "4.9",
    "bestRating": "5"
  }
}
</script>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;0,600;1,500&family=Manrope:wght@400;500;600;700;800&display=swap" rel="stylesheet">

<style>
  :root{
    --charcoal:#1b1714;
    --charcoal-2:#221c18;
    --ivory:#faf6ef;
    --ivory-2:#f3ece0;
    --gold:#c6a165;
    --gold-light:#e2c894;
    --gold-dim:#8f7448;
    --beige:#e9dfc9;
    --blush:#e7c9c1;
    --line:rgba(198,161,101,0.28);
  }

  *{box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{
    margin:0;
    background:var(--ivory);
    color:var(--charcoal);
    font-family:'Manrope',sans-serif;
    -webkit-font-smoothing:antialiased;
    overflow-x:hidden;
  }
  h1,h2,h3,h4,.serif{
    font-family:'Cormorant Garamond',serif;
    font-weight:500;
    letter-spacing:0.01em;
    margin:0;
  }
  .eyebrow{
    font-family:'Manrope',sans-serif;
    text-transform:uppercase;
    letter-spacing:0.28em;
    font-size:0.72rem;
    font-weight:700;
    color:var(--gold-dim);
  }
  a{text-decoration:none;color:inherit;}
  img{display:block;max-width:100%;}
  .container{max-width:1200px;margin:0 auto;padding:0 24px;}

  @media(prefers-reduced-motion: reduce){
    *{animation:none !important; transition:none !important; scroll-behavior:auto !important;}
  }

  /* Preloader */
  #preloader{
    position:fixed;inset:0;background:var(--charcoal);z-index:999;
    display:flex;align-items:center;justify-content:center;
    transition:opacity .8s ease, visibility .8s ease;
  }
  #preloader.hide{opacity:0;visibility:hidden;}
  #preloader .mark{
    font-family:'Cormorant Garamond',serif;color:var(--gold-light);
    font-size:1.6rem;letter-spacing:0.3em;text-transform:uppercase;
    opacity:0;animation:markIn 1.6s ease forwards;
  }
  @keyframes markIn{0%{opacity:0;letter-spacing:0.6em;}100%{opacity:1;letter-spacing:0.3em;}}

  /* Signature: gold brush underline that draws on scroll */
  .brush-underline{display:block;width:86px;height:14px;margin-top:14px;}
  .brush-underline path{
    stroke:var(--gold);
    stroke-width:3;
    fill:none;
    stroke-linecap:round;
    stroke-dasharray:140;
    stroke-dashoffset:140;
    transition:stroke-dashoffset 1.1s cubic-bezier(.4,0,.2,1);
  }
  .in-view .brush-underline path{stroke-dashoffset:0;}
  .center-underline{margin-left:auto;margin-right:auto;}

  /* Reveal animations */
  .reveal{opacity:0;transform:translateY(28px);transition:opacity .9s ease, transform .9s ease;}
  .reveal.in-view{opacity:1;transform:translateY(0);}
  .reveal-delay-1.in-view{transition-delay:.12s;}
  .reveal-delay-2.in-view{transition-delay:.24s;}
  .reveal-delay-3.in-view{transition-delay:.36s;}

  /* Navbar */
  header{
    position:fixed;top:0;left:0;right:0;z-index:100;
    padding:22px 0;
    transition:background .5s ease, padding .5s ease, box-shadow .5s ease, backdrop-filter .5s ease;
  }
  header.scrolled{
    background:rgba(27,23,20,0.82);
    backdrop-filter:blur(14px);
    -webkit-backdrop-filter:blur(14px);
    padding:14px 0;
    box-shadow:0 8px 30px rgba(0,0,0,0.25);
  }
  .nav-row{display:flex;align-items:center;justify-content:space-between;}
  .brand{
    font-family:'Cormorant Garamond',serif;
    font-size:1.5rem;color:var(--ivory);letter-spacing:0.04em;
  }
  .brand span{color:var(--gold-light);}
  .nav-links{display:flex;gap:38px;list-style:none;margin:0;padding:0;}
  .nav-links a{
    color:var(--ivory-2);font-size:0.86rem;letter-spacing:0.04em;
    position:relative;padding-bottom:4px;
  }
  .nav-links a::after{
    content:'';position:absolute;left:0;bottom:0;width:0;height:1px;background:var(--gold);
    transition:width .35s ease;
  }
  .nav-links a:hover::after{width:100%;}
  .btn{
    display:inline-flex;align-items:center;justify-content:center;gap:8px;
    padding:13px 28px;font-size:0.82rem;letter-spacing:0.06em;font-weight:700;
    text-transform:uppercase;border-radius:2px;
    transition:transform .35s ease, box-shadow .35s ease, background .35s ease, color .35s ease;
    cursor:pointer;border:1px solid transparent;
  }
  .btn-gold{background:linear-gradient(135deg,var(--gold-light),var(--gold));color:var(--charcoal);}
  .btn-gold:hover{transform:translateY(-2px);box-shadow:0 12px 28px rgba(198,161,101,0.35);}
  .btn-outline{border-color:rgba(250,246,239,0.5);color:var(--ivory);}
  .btn-outline:hover{border-color:var(--gold-light);color:var(--gold-light);transform:translateY(-2px);}
  .btn-outline-dark{border-color:rgba(27,23,20,0.35);color:var(--charcoal);}
  .btn-outline-dark:hover{border-color:var(--gold-dim);color:var(--gold-dim);transform:translateY(-2px);}

  .nav-cta{display:none;}
  @media(min-width:900px){.nav-cta{display:inline-flex;}}
  @media(max-width:899px){.nav-links{display:none;}}

  .burger{display:none;flex-direction:column;gap:5px;cursor:pointer;z-index:120;}
  .burger span{width:26px;height:1.5px;background:var(--ivory);transition:all .35s ease;}
  @media(max-width:899px){.burger{display:flex;}}
  .burger.open span:nth-child(1){transform:translateY(6.5px) rotate(45deg);}
  .burger.open span:nth-child(2){opacity:0;}
  .burger.open span:nth-child(3){transform:translateY(-6.5px) rotate(-45deg);}

  #mobile-menu{
    position:fixed;inset:0;background:var(--charcoal);z-index:110;
    display:flex;flex-direction:column;align-items:center;justify-content:center;gap:30px;
    transform:translateY(-100%);transition:transform .5s cubic-bezier(.4,0,.2,1);
  }
  #mobile-menu.open{transform:translateY(0);}
  #mobile-menu a{font-family:'Cormorant Garamond',serif;font-size:1.8rem;color:var(--ivory);}

  /* Hero */
  .hero{
    position:relative;min-height:100vh;display:flex;align-items:center;
    background:
      linear-gradient(180deg, rgba(20,17,14,0.55), rgba(20,17,14,0.86)),
      url('images/bridal-hairstyle-floral-1.jpg') center 18%/cover no-repeat;
  }
  .hero-inner{position:relative;z-index:2;padding-top:110px;padding-bottom:60px;}
  .hero .eyebrow{color:var(--gold-light);}
  .hero h1{
    color:var(--ivory);
    font-size:clamp(2.6rem,7vw,5rem);
    line-height:1.05;
    margin-top:16px;
    font-style:italic;
  }
  .hero h1 em{font-style:normal;color:var(--gold-light);}
  .hero p.lead{
    color:var(--ivory-2);max-width:520px;margin-top:22px;
    font-size:1.05rem;line-height:1.7;font-weight:400;
  }
  .rating-pill{
    display:inline-flex;align-items:center;gap:8px;
    border:1px solid var(--line);border-radius:40px;padding:8px 18px;
    color:var(--gold-light);font-size:0.85rem;letter-spacing:0.04em;margin-top:26px;
    background:rgba(255,255,255,0.03);
  }
  .hero-ctas{display:flex;gap:16px;margin-top:36px;flex-wrap:wrap;}
  .floaty{position:absolute;border-radius:50%;border:1px solid var(--line);animation:floaty 7s ease-in-out infinite;}
  @keyframes floaty{0%,100%{transform:translateY(0);}50%{transform:translateY(-18px);}}
  .scroll-cue{
    position:absolute;bottom:34px;left:50%;transform:translateX(-50%);
    color:var(--ivory-2);font-size:0.7rem;letter-spacing:0.3em;text-transform:uppercase;
    display:flex;flex-direction:column;align-items:center;gap:10px;z-index:2;
  }
  .scroll-cue .line{width:1px;height:36px;background:linear-gradient(var(--gold-light),transparent);animation:cue 1.8s ease-in-out infinite;}
  @keyframes cue{0%{opacity:0.2;}50%{opacity:1;}100%{opacity:0.2;}}

  section{padding:110px 0;}
  @media(max-width:768px){section{padding:74px 0;}}

  .section-head{max-width:640px;}
  .section-head.center{margin-left:auto;margin-right:auto;text-align:center;}
  .section-head h2{font-size:clamp(2rem,4.2vw,3rem);margin-top:14px;}

  /* About */
  .about-grid{display:grid;grid-template-columns:1fr;gap:60px;align-items:center;}
  @media(min-width:900px){.about-grid{grid-template-columns:0.9fr 1.1fr;gap:80px;}}
  .about-img-wrap{position:relative;}
  .about-img-wrap img{border-radius:2px;width:100%;height:560px;object-fit:cover;}
  .about-img-tag{
    position:absolute;bottom:-28px;right:-28px;background:var(--charcoal);color:var(--ivory);
    padding:26px 30px;max-width:200px;border:1px solid var(--line);
  }
  @media(max-width:600px){.about-img-tag{right:0;bottom:-20px;padding:18px 20px;}}
  .about-img-tag .num{font-family:'Cormorant Garamond',serif;font-size:2.2rem;color:var(--gold-light);}
  .about-img-tag .cap{font-size:0.72rem;letter-spacing:0.06em;color:var(--ivory-2);margin-top:4px;}

  .highlight-grid{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin-top:44px;}
  @media(min-width:600px){.highlight-grid{grid-template-columns:1fr 1fr;}}
  .highlight-card{
    border:1px solid var(--line);padding:22px 20px;background:var(--ivory-2);
    transition:transform .4s ease, box-shadow .4s ease, background .4s ease;
  }
  .highlight-card:hover{transform:translateY(-6px);box-shadow:0 18px 34px rgba(27,23,20,0.09);background:#fff;}
  .highlight-card .hv{font-family:'Cormorant Garamond',serif;font-size:1.6rem;color:var(--gold-dim);}
  .highlight-card .hl{font-size:0.8rem;color:var(--charcoal);margin-top:6px;letter-spacing:0.01em;}

  /* Services */
  .services-section{background:var(--charcoal);color:var(--ivory);}
  .services-section .eyebrow{color:var(--gold-light);}
  .services-grid{display:grid;grid-template-columns:1fr;gap:2px;margin-top:56px;background:rgba(250,246,239,0.08);}
  @media(min-width:640px){.services-grid{grid-template-columns:1fr 1fr;}}
  @media(min-width:1000px){.services-grid{grid-template-columns:1fr 1fr 1fr;}}
  .service-card{
    background:var(--charcoal-2);padding:42px 32px;position:relative;overflow:hidden;
    transition:background .4s ease;
  }
  .service-card:hover{background:#28221d;}
  .service-card .si{
    width:44px;height:44px;border:1px solid var(--gold-dim);border-radius:50%;
    display:flex;align-items:center;justify-content:center;color:var(--gold-light);
    font-family:'Cormorant Garamond',serif;font-size:1.2rem;margin-bottom:26px;
  }
  .service-card h3{font-size:1.5rem;color:var(--ivory);}
  .service-card p{font-size:0.88rem;color:var(--ivory-2);line-height:1.6;margin-top:10px;opacity:0.85;}
  .service-card .sa{
    display:inline-flex;align-items:center;gap:6px;margin-top:22px;font-size:0.76rem;
    letter-spacing:0.08em;text-transform:uppercase;color:var(--gold-light);
    border-bottom:1px solid transparent;transition:border-color .3s ease, gap .3s ease;
  }
  .service-card:hover .sa{border-color:var(--gold-light);gap:10px;}

  /* Featured makeover */
  .feature-wrap{position:relative;}
  .feature-img{
    width:100%;height:640px;object-fit:cover;border-radius:2px;
  }
  @media(max-width:768px){.feature-img{height:460px;}}
  .feature-card{
    position:absolute;left:6%;bottom:-10%;max-width:420px;background:var(--ivory);
    padding:44px 40px;border-top:2px solid var(--gold);
  }
  @media(max-width:768px){.feature-card{position:static;margin-top:-60px;margin-left:5%;margin-right:5%;max-width:none;padding:32px 26px;}}
  .feature-card h2{font-size:clamp(1.8rem,3.4vw,2.6rem);line-height:1.15;font-style:italic;}
  .feature-card p{margin-top:16px;font-size:0.92rem;line-height:1.7;color:#4a433a;}

  /* Gallery */
  .gallery-grid{
    display:grid;grid-template-columns:repeat(2,1fr);gap:14px;margin-top:56px;
  }
  @media(min-width:768px){.gallery-grid{grid-template-columns:repeat(4,1fr);}}
  .gallery-item{position:relative;overflow:hidden;cursor:pointer;border-radius:2px;}
  .gallery-item.tall{grid-row:span 2;}
  .gallery-item img{width:100%;height:100%;object-fit:cover;transition:transform .7s cubic-bezier(.2,.7,.3,1);}
  .gallery-item:hover img{transform:scale(1.08);}
  .gallery-overlay{
    position:absolute;inset:0;background:linear-gradient(0deg,rgba(27,23,20,0.75),transparent 55%);
    opacity:0;transition:opacity .4s ease;
    display:flex;align-items:flex-end;padding:16px;
  }
  .gallery-item:hover .gallery-overlay{opacity:1;}
  .gallery-overlay span{color:var(--ivory);font-size:0.78rem;letter-spacing:0.06em;text-transform:uppercase;}

  #lightbox{
    position:fixed;inset:0;background:rgba(15,12,10,0.94);z-index:200;
    display:flex;align-items:center;justify-content:center;
    opacity:0;visibility:hidden;transition:opacity .4s ease, visibility .4s ease;
    padding:20px;
  }
  #lightbox.open{opacity:1;visibility:visible;}
  #lightbox img{max-height:86vh;max-width:90vw;object-fit:contain;border:1px solid var(--line);}
  #lightbox .close{position:absolute;top:26px;right:32px;color:var(--ivory);font-size:1.8rem;cursor:pointer;}

  /* Why choose us */
  .why-grid{display:grid;grid-template-columns:1fr;gap:1px;margin-top:56px;background:var(--line);}
  @media(min-width:768px){.why-grid{grid-template-columns:repeat(3,1fr);}}
  .why-card{background:var(--ivory);padding:38px 30px;}
  .why-card .wn{font-family:'Cormorant Garamond',serif;font-size:1rem;color:var(--gold);letter-spacing:0.1em;}
  .why-card h3{font-size:1.4rem;margin-top:12px;}
  .why-card p{font-size:0.87rem;color:#5b5346;line-height:1.65;margin-top:10px;}

  /* Ratings/testimonials */
  .rating-section{background:var(--beige);}
  .stars{color:var(--gold);font-size:1.6rem;letter-spacing:4px;}
  .big-rating{font-family:'Cormorant Garamond',serif;font-size:5rem;line-height:1;color:var(--charcoal);}
  .testi-grid{display:grid;grid-template-columns:1fr;gap:22px;margin-top:50px;}
  @media(min-width:768px){.testi-grid{grid-template-columns:repeat(2,1fr);}}
  .testi-card{background:var(--ivory);padding:34px 30px;border:1px solid rgba(0,0,0,0.05);position:relative;}
  .testi-card .quote-mark{font-family:'Cormorant Garamond',serif;font-size:3rem;color:var(--gold-light);line-height:1;}
  .testi-card p.qt{font-size:0.95rem;line-height:1.75;color:#3d372e;margin-top:6px;font-style:italic;}
  .testi-card .who{margin-top:18px;font-size:0.8rem;letter-spacing:0.04em;color:var(--gold-dim);font-weight:700;}
  .testi-card .placeholder-tag{position:absolute;top:16px;right:18px;font-size:0.62rem;color:#a89c86;letter-spacing:0.06em;}

  /* CTA band */
  .cta-band{
    background:
      linear-gradient(180deg, rgba(20,17,14,0.82), rgba(20,17,14,0.9)),
      url('https://images.unsplash.com/photo-1560066984-138dadb4c035?q=80&w=1974&auto=format&fit=crop') center/cover fixed;
    color:var(--ivory);text-align:center;
  }
  @media(max-width:768px){.cta-band{background-attachment:scroll;}}
  .cta-band h2{font-size:clamp(2.1rem,5vw,3.4rem);font-style:italic;}
  .cta-band p{max-width:520px;margin:20px auto 0;color:var(--ivory-2);line-height:1.7;}
  .cta-btns{display:flex;justify-content:center;gap:16px;margin-top:36px;flex-wrap:wrap;}

  /* Contact */
  .contact-grid{display:grid;grid-template-columns:1fr;gap:50px;margin-top:56px;}
  @media(min-width:900px){.contact-grid{grid-template-columns:1fr 1fr;}}
  .contact-row{display:flex;gap:18px;padding:22px 0;border-bottom:1px solid var(--line);}
  .contact-row .ci{
    width:38px;height:38px;border:1px solid var(--gold-dim);border-radius:50%;flex-shrink:0;
    display:flex;align-items:center;justify-content:center;color:var(--gold-dim);font-size:1rem;
  }
  .contact-row .ct h4{font-size:1.05rem;font-family:'Manrope',sans-serif;font-weight:700;}
  .contact-row .ct p{margin:4px 0 0;font-size:0.88rem;color:#5b5346;line-height:1.6;}
  .map-block{
    height:100%;min-height:340px;border:1px solid var(--line);
    background:
      linear-gradient(rgba(27,23,20,0.06),rgba(27,23,20,0.06)),
      repeating-linear-gradient(45deg, rgba(198,161,101,0.06) 0 2px, transparent 2px 22px);
    display:flex;flex-direction:column;align-items:center;justify-content:center;gap:14px;
    text-align:center;padding:30px;
  }
  .map-block .pin{
    width:50px;height:50px;border-radius:50% 50% 50% 0;border:2px solid var(--gold);
    transform:rotate(-45deg);display:flex;align-items:center;justify-content:center;
  }
  .map-block .pin::after{content:'';width:14px;height:14px;border-radius:50%;background:var(--gold);}

  /* Footer */
  footer{background:var(--charcoal);color:var(--ivory-2);padding:70px 0 30px;}
  .footer-grid{display:grid;grid-template-columns:1fr;gap:40px;}
  @media(min-width:768px){.footer-grid{grid-template-columns:1.3fr 1fr 1fr;}}
  footer h4{font-family:'Manrope',sans-serif;color:var(--gold-light);font-size:0.78rem;letter-spacing:0.14em;text-transform:uppercase;margin-bottom:18px;}
  footer .flogo{font-family:'Cormorant Garamond',serif;font-size:1.7rem;color:var(--ivory);}
  footer p.tag{font-style:italic;color:var(--gold-light);margin-top:8px;font-family:'Cormorant Garamond',serif;font-size:1.1rem;}
  footer ul{list-style:none;padding:0;margin:0;display:flex;flex-direction:column;gap:10px;}
  footer ul a{font-size:0.88rem;color:var(--ivory-2);transition:color .3s ease;}
  footer ul a:hover{color:var(--gold-light);}
  .socials{display:flex;gap:12px;margin-top:20px;}
  .socials a{
    width:36px;height:36px;border:1px solid var(--line);border-radius:50%;
    display:flex;align-items:center;justify-content:center;font-size:0.85rem;color:var(--gold-light);
    transition:background .3s ease, transform .3s ease;
  }
  .socials a:hover{background:var(--gold);color:var(--charcoal);transform:translateY(-3px);}
  .foot-bottom{
    border-top:1px solid rgba(250,246,239,0.1);margin-top:54px;padding-top:24px;
    display:flex;flex-wrap:wrap;justify-content:space-between;gap:10px;font-size:0.76rem;color:#a89c86;
  }

  /* Sticky mobile CTA */
  .mobile-cta-bar{
    position:fixed;bottom:0;left:0;right:0;z-index:90;display:none;
    background:var(--charcoal);border-top:1px solid var(--line);
  }
  @media(max-width:899px){.mobile-cta-bar{display:flex;}}
  .mobile-cta-bar a{
    flex:1;text-align:center;padding:15px 8px;font-size:0.78rem;letter-spacing:0.04em;
    color:var(--ivory);border-right:1px solid rgba(250,246,239,0.1);text-transform:uppercase;font-weight:600;
  }
  .mobile-cta-bar a:last-child{border-right:none;background:var(--gold);color:var(--charcoal);}
  @media(max-width:899px){section:last-of-type{padding-bottom:90px;} footer{padding-bottom:110px;}}
</style>
</head>
<body>

<div id="preloader"><div class="mark">Vanya Makeovers</div></div>

<header id="site-header">
  <div class="container nav-row">
    <a href="#home" class="brand">Vanya <span>Makeovers</span></a>
    <ul class="nav-links">
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#gallery">Gallery</a></li>
      <li><a href="#reviews">Reviews</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
    <a href="#contact" class="btn btn-gold nav-cta">Book Appointment</a>
    <div class="burger" id="burger"><span></span><span></span><span></span></div>
  </div>
</header>

<div id="mobile-menu">
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#services">Services</a>
  <a href="#gallery">Gallery</a>
  <a href="#reviews">Reviews</a>
  <a href="#contact">Contact</a>
  <a href="#contact" class="btn btn-gold" style="margin-top:10px;">Book Appointment</a>
</div>

<!-- HERO -->
<section id="home" class="hero" style="padding:0;">
  <div class="floaty" style="width:120px;height:120px;top:22%;right:8%;"></div>
  <div class="floaty" style="width:60px;height:60px;bottom:26%;left:6%;animation-delay:1.4s;"></div>
  <div class="container hero-inner">
    <p class="eyebrow">Vanya Makeovers &mdash; Sector 8, Faridabad</p>
    <h1>Where <em>Beauty</em><br>Meets Elegance</h1>
    <p class="lead">Discover a premium beauty and makeover experience designed to bring out your best &mdash; crafted with care, precision and a passion for detail.</p>
    <div class="rating-pill">★★★★★ &nbsp;4.9 Rated Salon</div>
    <div class="hero-ctas">
      <a href="#contact" class="btn btn-gold">Book an Appointment</a>
      <a href="tel:9310956711" class="btn btn-outline">Call Now</a>
    </div>
  </div>
  <div class="scroll-cue"><span>Scroll</span><span class="line"></span></div>
</section>

<!-- ABOUT -->
<section id="about">
  <div class="container about-grid">
    <div class="about-img-wrap reveal">
      <img src="images/bridal-hairstyle-braid-2.jpg" alt="Bridal hairstyle by Vanya Makeovers" style="object-position:center 15%;">
      <div class="about-img-tag">
        <div class="num">4.9★</div>
        <div class="cap">Customer Rated Salon in Faridabad</div>
      </div>
    </div>
    <div class="reveal reveal-delay-1">
      <p class="eyebrow">About Us</p>
      <h2 class="serif">A refined beauty experience, built around you</h2>
      <svg class="brush-underline" viewBox="0 0 86 14"><path d="M2 8 C 20 2, 40 12, 86 6"/></svg>
      <p style="margin-top:22px;font-size:1rem;line-height:1.8;color:#4a433a;max-width:480px;">
        Vanya Makeovers brings together skilled hands, premium products and an unhurried approach to beauty. Every visit is shaped around attention to detail, genuine care and a finish you'll want to show off &mdash; from everyday grooming to your most important day.
      </p>
      <div class="highlight-grid">
        <div class="highlight-card"><div class="hv">4.9★</div><div class="hl">Customer Rating</div></div>
        <div class="highlight-card"><div class="hv">Premium</div><div class="hl">Beauty Experience</div></div>
        <div class="highlight-card"><div class="hv">Expert</div><div class="hl">Professional Service</div></div>
        <div class="highlight-card"><div class="hv">10&ndash;8</div><div class="hl">Open Daily, 10 AM&ndash;8 PM</div></div>
      </div>
    </div>
  </div>
</section>

<!-- SERVICES -->
<section id="services" class="services-section">
  <div class="container">
    <div class="section-head center reveal">
      <p class="eyebrow">What We Offer</p>
      <h2 class="serif">Our Services</h2>
      <svg class="brush-underline center-underline" viewBox="0 0 86 14"><path d="M2 8 C 20 2, 40 12, 86 6"/></svg>
    </div>
    <div class="services-grid">

      <div class="service-card reveal">
        <div class="si">01</div>
        <h3>Hair Styling</h3>
        <p>Precision cuts and styling tailored to your face, texture and lifestyle.</p>
        <a href="#contact" class="sa">Book Service &rarr;</a>
      </div>

      <div class="service-card reveal reveal-delay-1">
        <div class="si">02</div>
        <h3>Haircut &amp; Hair Care</h3>
        <p>Restorative treatments and expert cuts that keep hair healthy and radiant.</p>
        <a href="#contact" class="sa">Book Service &rarr;</a>
      </div>

      <div class="service-card reveal reveal-delay-2">
        <div class="si">03</div>
        <h3>Hair Spa</h3>
        <p>Deep-nourishing rituals that restore shine, softness and strength.</p>
        <a href="#contact" class="sa">Book Service &rarr;</a>
      </div>

      <div class="service-card reveal">
        <div class="si">04</div>
        <h3>Facial &amp; Skin Care</h3>
        <p>Customised facials designed to refresh, brighten and rejuvenate your skin.</p>
        <a href="#contact" class="sa">Enquire Now &rarr;</a>
      </div>

      <div class="service-card reveal reveal-delay-1">
        <div class="si">05</div>
        <h3>Bridal Makeup</h3>
        <p>Flawless, long-lasting bridal looks crafted for your most special day.</p>
        <a href="#contact" class="sa">Enquire Now &rarr;</a>
      </div>

      <div class="service-card reveal reveal-delay-2">
        <div class="si">06</div>
        <h3>Party Makeup</h3>
        <p>Statement looks for every occasion, from soft glam to bold glamour.</p>
        <a href="#contact" class="sa">Enquire Now &rarr;</a>
      </div>

      <div class="service-card reveal">
        <div class="si">07</div>
        <h3>Beauty Treatments</h3>
        <p>Curated treatments that address your skin and beauty goals with care.</p>
        <a href="#contact" class="sa">Enquire Now &rarr;</a>
      </div>

      <div class="service-card reveal reveal-delay-1">
        <div class="si">08</div>
        <h3>Grooming</h3>
        <p>Complete grooming services for a polished, put-together everyday look.</p>
        <a href="#contact" class="sa">Book Service &rarr;</a>
      </div>

      <div class="service-card reveal reveal-delay-2">
        <div class="si">09</div>
        <h3>Makeover Services</h3>
        <p>A full transformation experience &mdash; hair, skin and makeup, together.</p>
        <a href="#contact" class="sa">Book Service &rarr;</a>
      </div>

    </div>
  </div>
</section>

<!-- FEATURED MAKEOVER -->
<section>
  <div class="container feature-wrap reveal">
    <img class="feature-img" src="images/bridal-makeup-portrait-3.jpg" alt="Featured bridal makeover at Vanya Makeovers" style="object-position:center 20%;">
    <div class="feature-card">
      <h2>Your Look. <br>Your Style. <br>Your Moment.</h2>
      <p>Every makeover at Vanya begins with listening &mdash; to how you want to feel, not just how you want to look. The result is a version of you, only more so.</p>
    </div>
  </div>
</section>

<!-- GALLERY -->
<section id="gallery" style="padding-top:170px;">
  <div class="container">
    <div class="section-head center reveal">
      <p class="eyebrow">Portfolio</p>
      <h2 class="serif">Gallery</h2>
      <svg class="brush-underline center-underline" viewBox="0 0 86 14"><path d="M2 8 C 20 2, 40 12, 86 6"/></svg>
    </div>
    <div class="gallery-grid">
      <div class="gallery-item tall reveal" onclick="openLightbox(this)">
        <img src="images/bridal-makeup-portrait-3.jpg" alt="Bridal makeup look" style="object-position:center 15%;">
        <div class="gallery-overlay"><span>Bridal Makeup</span></div>
      </div>
      <div class="gallery-item reveal reveal-delay-1" onclick="openLightbox(this)">
        <img src="images/bridal-hairstyle-floral-1.jpg" alt="Bridal hairstyle with flowers" style="object-position:center 20%;">
        <div class="gallery-overlay"><span>Bridal Hairstyling</span></div>
      </div>
      <div class="gallery-item reveal reveal-delay-2" onclick="openLightbox(this)">
        <img src="https://images.unsplash.com/photo-1487412947147-5cebf100ffc2?q=80&w=1200&auto=format&fit=crop" alt="Makeup application">
        <div class="gallery-overlay"><span>Makeup</span></div>
      </div>
      <div class="gallery-item tall reveal" onclick="openLightbox(this)">
        <img src="images/bridal-hairstyle-braid-2.jpg" alt="Bridal braid hairstyle with flowers" style="object-position:center 20%;">
        <div class="gallery-overlay"><span>Hair Styling</span></div>
      </div>
      <div class="gallery-item reveal reveal-delay-1" onclick="openLightbox(this)">
        <img src="https://images.unsplash.com/photo-1595476108010-b4d1f102b1b1?q=80&w=1200&auto=format&fit=crop" alt="Facial treatment">
        <div class="gallery-overlay"><span>Facial &amp; Skin Care</span></div>
      </div>
      <div class="gallery-item reveal reveal-delay-2" onclick="openLightbox(this)">
        <img src="https://images.unsplash.com/photo-1595475884562-073c30d45670?q=80&w=1200&auto=format&fit=crop" alt="Party makeup">
        <div class="gallery-overlay"><span>Party Makeup</span></div>
      </div>
    </div>
  </div>
</section>

<div id="lightbox" onclick="closeLightbox(event)">
  <span class="close" onclick="closeLightbox(event)">&times;</span>
  <img id="lightbox-img" src="" alt="Enlarged gallery image">
</div>

<!-- WHY CHOOSE US -->
<section>
  <div class="container">
    <div class="section-head center reveal">
      <p class="eyebrow">The Vanya Difference</p>
      <h2 class="serif">Why Choose Vanya Makeovers?</h2>
      <svg class="brush-underline center-underline" viewBox="0 0 86 14"><path d="M2 8 C 20 2, 40 12, 86 6"/></svg>
    </div>
    <div class="why-grid">
      <div class="why-card reveal"><div class="wn">Experience</div><h3>Premium Salon Experience</h3><p>A calm, elegant space designed for genuine relaxation.</p></div>
      <div class="why-card reveal reveal-delay-1"><div class="wn">Expertise</div><h3>Professional Beauty Services</h3><p>Skilled hands trained across hair, skin and makeup.</p></div>
      <div class="why-card reveal reveal-delay-2"><div class="wn">Precision</div><h3>Attention to Detail</h3><p>Every finish checked, refined and perfected.</p></div>
      <div class="why-card reveal"><div class="wn">Trust</div><h3>Customer Satisfaction</h3><p>Rated 4.9★ by clients who return again and again.</p></div>
      <div class="why-card reveal reveal-delay-1"><div class="wn">Hygiene</div><h3>Elegant &amp; Hygienic Environment</h3><p>Clean, sanitised tools and spaces at every visit.</p></div>
      <div class="why-card reveal reveal-delay-2"><div class="wn">Personal</div><h3>Personalised Makeovers</h3><p>Looks designed around your features and preferences.</p></div>
    </div>
  </div>
</section>

<!-- RATINGS -->
<section id="reviews" class="rating-section">
  <div class="container" style="text-align:center;">
    <p class="eyebrow reveal">Trusted by Our Clients</p>
    <div class="big-rating reveal reveal-delay-1">4.9</div>
    <div class="stars reveal reveal-delay-1">★★★★★</div>
    <p style="margin-top:10px;color:#5b5346;font-size:0.95rem;letter-spacing:0.02em;" class="reveal reveal-delay-1">Highly Rated by Customers</p>

    <div class="testi-grid">
      <div class="testi-card reveal">
        <span class="placeholder-tag">Sample review</span>
        <div class="quote-mark">&ldquo;</div>
        <p class="qt">A genuinely relaxing experience from start to finish &mdash; the team took real care with every detail of my look.</p>
        <div class="who">&mdash; Placeholder Client, Faridabad</div>
      </div>
      <div class="testi-card reveal reveal-delay-1">
        <span class="placeholder-tag">Sample review</span>
        <div class="quote-mark">&ldquo;</div>
        <p class="qt">My bridal makeup lasted the entire day and looked flawless in every photo. Truly a premium experience.</p>
        <div class="who">&mdash; Placeholder Client, Faridabad</div>
      </div>
    </div>
    <p style="margin-top:26px;font-size:0.75rem;color:#8a7f6c;">Reviews shown are placeholders &mdash; replace with real client testimonials.</p>
  </div>
</section>

<!-- CTA BAND -->
<section class="cta-band">
  <div class="container reveal">
    <p class="eyebrow" style="color:var(--gold-light);">Book Now</p>
    <h2>Ready for Your Next Makeover?</h2>
    <p>Book your appointment with Vanya Makeovers and step into a premium beauty experience.</p>
    <div class="cta-btns">
      <a href="tel:9310956711" class="btn btn-gold">Call 93109 56711</a>
      <a href="#contact" class="btn btn-outline">Book Appointment</a>
    </div>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="container">
    <div class="section-head reveal">
      <p class="eyebrow">Visit Us</p>
      <h2 class="serif">Get In Touch</h2>
      <svg class="brush-underline" viewBox="0 0 86 14"><path d="M2 8 C 20 2, 40 12, 86 6"/></svg>
    </div>
    <div class="contact-grid">
      <div class="reveal reveal-delay-1">
        <div class="contact-row">
          <div class="ci">&#128205;</div>
          <div class="ct"><h4>Address</h4><p>2416, Near Hanuman Mandir, CISF, Sector 8, Faridabad, Haryana 121006</p></div>
        </div>
        <div class="contact-row">
          <div class="ci">&#128222;</div>
          <div class="ct"><h4>Phone</h4><p><a href="tel:9310956711" style="color:var(--gold-dim);font-weight:600;">93109 56711</a></p></div>
        </div>
        <div class="contact-row">
          <div class="ci">&#128337;</div>
          <div class="ct"><h4>Hours</h4><p>Open Daily, 10:00 AM &ndash; 8:00 PM</p></div>
        </div>
        <div style="display:flex;gap:14px;margin-top:30px;flex-wrap:wrap;">
          <a href="https://www.google.com/maps/dir/?api=1&destination=2416+Near+Hanuman+Mandir+CISF+Sector+8+Faridabad+Haryana+121006" target="_blank" rel="noopener" class="btn btn-outline-dark">Get Directions</a>
          <a href="https://wa.me/919310956711" target="_blank" rel="noopener" class="btn btn-gold">WhatsApp Us</a>
        </div>
      </div>
      <div class="reveal reveal-delay-2">
        <div class="map-block">
          <div class="pin"></div>
          <div>
            <p style="font-family:'Cormorant Garamond',serif;font-size:1.3rem;color:var(--charcoal);margin:0;">Vanya Makeovers</p>
            <p style="font-size:0.85rem;color:#6b6153;margin-top:6px;">Sector 8, Faridabad, Haryana</p>
          </div>
          <a href="https://www.google.com/maps/dir/?api=1&destination=2416+Near+Hanuman+Mandir+CISF+Sector+8+Faridabad+Haryana+121006" target="_blank" rel="noopener" class="btn btn-outline-dark" style="margin-top:10px;">Open in Google Maps</a>
        </div>
      </div>
    </div>
  </div>
</section>

<footer>
  <div class="container footer-grid">
    <div>
      <div class="flogo">Vanya Makeovers</div>
      <p class="tag">Where Beauty Meets Elegance</p>
      <div class="socials">
        <a href="#" aria-label="Instagram">IG</a>
        <a href="#" aria-label="Facebook">FB</a>
        <a href="https://wa.me/919310956711" aria-label="WhatsApp">WA</a>
      </div>
    </div>
    <div>
      <h4>Quick Links</h4>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#gallery">Gallery</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </div>
    <div>
      <h4>Contact</h4>
      <ul>
        <li>93109 56711</li>
        <li>2416, Near Hanuman Mandir, CISF, Sector 8, Faridabad, Haryana 121006</li>
        <li>10:00 AM &ndash; 8:00 PM, Daily</li>
      </ul>
    </div>
  </div>
  <div class="container foot-bottom">
    <span>&copy; 2026 Vanya Makeovers. All rights reserved.</span>
    <span>Designed with care for a premium beauty experience.</span>
  </div>
</footer>

<div class="mobile-cta-bar">
  <a href="tel:9310956711">Call</a>
  <a href="https://wa.me/919310956711" target="_blank" rel="noopener">WhatsApp</a>
  <a href="#contact">Book Now</a>
</div>

<script>
  // Preloader
  window.addEventListener('load', () => {
    setTimeout(() => { document.getElementById('preloader').classList.add('hide'); }, 900);
  });

  // Navbar scroll state
  const header = document.getElementById('site-header');
  window.addEventListener('scroll', () => {
    if (window.scrollY > 60) header.classList.add('scrolled');
    else header.classList.remove('scrolled');
  });

  // Mobile menu
  const burger = document.getElementById('burger');
  const mobileMenu = document.getElementById('mobile-menu');
  burger.addEventListener('click', () => {
    burger.classList.toggle('open');
    mobileMenu.classList.toggle('open');
  });
  mobileMenu.querySelectorAll('a').forEach(a => a.addEventListener('click', () => {
    burger.classList.remove('open');
    mobileMenu.classList.remove('open');
  }));

  // Scroll reveal
  const revealEls = document.querySelectorAll('.reveal');
  const io = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('in-view');
        io.unobserve(entry.target);
      }
    });
  }, { threshold: 0.15 });
  revealEls.forEach(el => io.observe(el));

  // Lightbox
  function openLightbox(el) {
    const img = el.querySelector('img');
    const lb = document.getElementById('lightbox');
    document.getElementById('lightbox-img').src = img.src;
    lb.classList.add('open');
  }
  function closeLightbox(e) {
    document.getElementById('lightbox').classList.remove('open');
  }
  document.addEventListener('keydown', (e) => {
    if (e.key === 'Escape') closeLightbox();
  });
</script>

</body>
</html>
