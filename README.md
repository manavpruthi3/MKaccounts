<!DOCTYPE html>
<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <meta name="description"
          content="M|&|K Accounts provides professional GST, Income Tax, TDS, bookkeeping and accounting services. Currently serving clients across Haryana and looking forward to working with clients PAN India.">

    <meta name="keywords"
          content="M&K Accounts, M K Accounts, accounting services Hisar, accounting services Haryana, GST filing Hisar, GST return filing, income tax consultant Hisar, TDS services, bookkeeping services, part time accounting, remote accounting">

    <meta name="author"
          content="M|&|K Accounts">

    <meta name="theme-color"
          content="#080808">

    <meta property="og:title"
          content="M|&|K Accounts | Accounting & Tax Services">

    <meta property="og:description"
          content="Professional GST, Income Tax, TDS and accounting services. Currently serving Haryana and looking forward to working with clients PAN India.">

    <meta property="og:type"
          content="website">


    <title>
        M|&|K Accounts | GST, Income Tax, TDS & Accounting Services
    </title>


    <!-- =========================================================
         GOOGLE FONTS
    ========================================================== -->

    <link rel="preconnect"
          href="https://fonts.googleapis.com">

    <link rel="preconnect"
          href="https://fonts.gstatic.com"
          crossorigin>

    <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@500;600;700&display=swap"
          rel="stylesheet">


    <!-- =========================================================
         FONT AWESOME
    ========================================================== -->

    <link rel="stylesheet"
          href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">


    <!-- =========================================================
         STRUCTURED DATA
    ========================================================== -->

    <script type="application/ld+json">

    {
        "@context": "https://schema.org",

        "@type": "AccountingService",

        "name": "M|&|K Accounts",

        "description": "Professional GST, Income Tax, TDS, bookkeeping and accounting services.",

        "email": [
            "Info@mkaccounts.in",
            "ta.solution.hisar@gmail.com"
        ],

        "telephone": [
            "+91-9817571705",
            "+91-9992075501"
        ],

        "address": {
            "@type": "PostalAddress",
            "streetAddress": "Street No. 5, Chotu Ram Colony",
            "addressLocality": "Hisar",
            "addressRegion": "Haryana",
            "postalCode": "125001",
            "addressCountry": "IN"
        },

        "areaServed": [
            {
                "@type": "AdministrativeArea",
                "name": "Haryana"
            },
            {
                "@type": "Country",
                "name": "India"
            }
        ],

        "sameAs": [
            "https://maps.app.goo.gl/D4xPndjc2F5G5AT7A"
        ]

    }

    </script>


    <!-- =========================================================
         FAVICON
         Uses logo.jpeg from GitHub
    ========================================================== -->

    <link rel="icon"
          type="image/jpeg"
          href="logo.jpeg">


    <!-- =========================================================
         CSS
    ========================================================== -->

    <style>

        :root {

            --black: #080808;
            --black-soft: #111111;
            --black-light: #181818;

            --white: #ffffff;
            --off-white: #f8f8f6;
            --light: #f1f1ef;

            --grey: #737373;
            --grey-light: #a3a3a3;

            --border: #dddddd;
            --border-dark: #292929;

            --accent: #c9a96e;

            --serif: "Playfair Display", Georgia, serif;
            --sans: "DM Sans", Arial, sans-serif;

            --container: 1180px;

        }


        /* =========================================================
           RESET
        ========================================================== */

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }


        html {
            scroll-behavior: smooth;
        }


        body {

            font-family: var(--sans);

            color: var(--black);

            background: var(--white);

            line-height: 1.6;

            overflow-x: hidden;

        }


        a {

            text-decoration: none;

            color: inherit;

        }


        button {

            font-family: inherit;

        }


        img {

            max-width: 100%;

            display: block;

        }


        .container {

            width: min(
                calc(100% - 40px),
                var(--container)
            );

            margin: auto;

        }


        /* =========================================================
           HEADER
        ========================================================== */

        header {

            position: fixed;

            top: 0;

            left: 0;

            width: 100%;

            z-index: 9999;

            background: rgba(8,8,8,0.93);

            backdrop-filter: blur(16px);

            border-bottom: 1px solid rgba(
                255,
                255,
                255,
                0.08
            );

            transition: .3s ease;

        }


        header.scrolled {

            background: rgba(
                8,
                8,
                8,
                0.98
            );

        }


        .navbar {

            height: 72px;

            display: flex;

            align-items: center;

            justify-content: space-between;

        }


        /* =========================================================
           BRAND
        ========================================================== */

        .brand {

            display: flex;

            align-items: center;

            gap: 12px;

            color: white;

        }


        /*
           ACTUAL LOGO IMAGE
           Loaded from logo.jpeg
        */

        .brand-logo {

            width: 42px;

            height: 42px;

            display: flex;

            align-items: center;

            justify-content: center;

            flex-shrink: 0;

            overflow: hidden;

        }


        .brand-logo img {

            width: 100%;

            height: 100%;

            object-fit: contain;

            display: block;

        }


        .brand-text {

            display: flex;

            flex-direction: column;

            line-height: 1;

        }


        .brand-name {

            font-size: 15px;

            font-weight: 700;

            letter-spacing: 1px;

        }


        .brand-sub {

            margin-top: 5px;

            color: #777;

            font-size: 8px;

            font-weight: 600;

            letter-spacing: 1.5px;

        }


        /* =========================================================
           NAVIGATION
        ========================================================== */

        .nav-links {

            display: flex;

            align-items: center;

            gap: 34px;

            color: #bdbdbd;

            font-size: 14px;

        }


        .nav-links a {

            transition: .25s ease;

        }


        .nav-links a:hover {

            color: white;

        }


        .nav-cta {

            border: 1px solid #777;

            padding: 10px 22px;

            color: white !important;

            transition: .3s ease;

        }


        .nav-cta:hover {

            background: white;

            color: black !important;

            border-color: white;

        }


        .menu-btn {

            display: none;

            border: 0;

            background: transparent;

            color: white;

            font-size: 22px;

            cursor: pointer;

        }


        /* =========================================================
           HERO
        ========================================================== */

        .hero {

            min-height: 100vh;

            background:
                repeating-linear-gradient(
                    45deg,
                    #070707 0px,
                    #070707 2px,
                    #0c0c0c 2px,
                    #0c0c0c 4px
                );

            color: white;

            padding-top: 72px;

            display: flex;

            align-items: center;

        }


        .hero-grid {

            display: grid;

            grid-template-columns:
                1.05fr
                .95fr;

            gap: 70px;

            align-items: center;

            padding:
                80px
                0
                90px;

        }


        .rating-line {

            display: flex;

            align-items: center;

            gap: 11px;

            color: #aaa;

            font-size: 12px;

            margin-bottom: 28px;

        }


        .stars {

            color: white;

            letter-spacing: 2px;

        }


        .hero h1 {

            font-family: var(--serif);

            font-size:
                clamp(
                    52px,
                    6vw,
                    86px
                );

            line-height: .98;

            font-weight: 600;

            letter-spacing: -2px;

        }


        .hero h1 span {

            color: #777;

        }


        .hero-description {

            color: #a7a7a7;

            font-size: 17px;

            line-height: 1.8;

            max-width: 590px;

            margin-top: 30px;

        }


        .hero-buttons {

            display: flex;

            flex-wrap: wrap;

            gap: 14px;

            margin-top: 35px;

        }


        .btn {

            display: inline-flex;

            align-items: center;

            justify-content: center;

            gap: 10px;

            min-height: 50px;

            padding:
                0
                25px;

            border: 1px solid #555;

            font-size: 13px;

            font-weight: 600;

            transition: .3s ease;

            cursor: pointer;

        }


        .btn-primary {

            background: white;

            color: black;

            border-color: white;

        }


        .btn-primary:hover {

            background: transparent;

            color: white;

        }


        .btn-outline {

            color: white;

        }


        .btn-outline:hover {

            background: white;

            color: black;

        }


        .hero-contact {

            display: flex;

            gap: 35px;

            margin-top: 50px;

            flex-wrap: wrap;

        }


        .hero-contact-item {

            border-left:
                1px solid #444;

            padding-left: 15px;

        }


        .hero-contact-label {

            color: #777;

            font-size: 9px;

            letter-spacing: 1.5px;

            margin-bottom: 5px;

        }


        .hero-contact-number {

            color: white;

            font-size: 13px;

        }


        /* =========================================================
           HERO BUSINESS CARD
        ========================================================== */

        .hero-visual {

            position: relative;

            display: flex;

            justify-content: center;

            align-items: center;

            min-height: 520px;

        }


        .floating-logo {

            position: absolute;

            top: 0;

            right: 15%;

            width: 185px;

            height: 185px;

            background: white;

            display: flex;

            align-items: center;

            justify-content: center;

            box-shadow:
                0 25px 70px
                rgba(0,0,0,.35);

            animation:
                floatLogo 5s
                ease-in-out infinite;

            overflow: hidden;

        }


        /*
           ACTUAL LOGO IN FLOATING BOX
        */

        .floating-logo-image {

            width: 145px;

            height: 145px;

            object-fit: contain;

            display: block;

        }


        @keyframes floatLogo {

            0%,100% {

                transform:
                    translateY(0);

            }

            50% {

                transform:
                    translateY(-12px);

            }

        }


        .business-card {

            width: 500px;

            max-width: 100%;

            background:
                #f5f5f2;

            color: black;

            padding:
                22px
                28px
                18px;

            margin-top: 125px;

            box-shadow:
                0 30px 80px
                rgba(0,0,0,.4);

        }


        .card-top {

            display: flex;

            justify-content:
                space-between;

            font-weight: 700;

            font-family:
                Georgia,
                serif;

            font-size: 17px;

        }


        .card-phone {

            display: block;

            font-family:
                var(--sans);

            font-size: 13px;

            margin-top: 3px;

        }


        /*
           ACTUAL LOGO ON BUSINESS CARD
        */

        .card-logo {

            width: 80px;

            height: 80px;

            margin:
                5px auto
                12px;

            display: flex;

            align-items: center;

            justify-content: center;

            overflow: hidden;

        }


        .card-logo img {

            width: 100%;

            height: 100%;

            object-fit: contain;

            display: block;

        }


        .card-title {

            text-align: center;

            font-size: 27px;

            font-weight: 700;

            letter-spacing: 2px;

            margin-bottom: 16px;

        }


        .card-services {

            text-align: center;

            font-size: 14px;

            margin-bottom: 17px;

        }


        .card-services strong {

            display: block;

            margin-bottom: 4px;

        }


        .card-footer {

            border-top:
                1px solid #c5c5c5;

            margin:
                0 -28px
                -18px;

            padding:
                12px 25px;

            display: flex;

            justify-content:
                space-between;

            gap: 15px;

            font-size: 10px;

            background:
                #dddcd7;

        }


        /* =========================================================
           SECTIONS
        ========================================================== */

        section {

            padding: 110px 0;

        }


        .section-kicker {

            color: #8b7655;

            font-size: 10px;

            letter-spacing: 2px;

            font-weight: 700;

            text-transform:
                uppercase;

            margin-bottom: 18px;

        }


        .section-title {

            font-family:
                var(--serif);

            font-size:
                clamp(
                    38px,
                    4.5vw,
                    60px
                );

            line-height: 1.08;

            font-weight: 600;

            letter-spacing: -1.5px;

        }


        .section-intro {

            max-width: 620px;

            color: #6e6e6e;

            margin-top: 22px;

            font-size: 16px;

            line-height: 1.8;

        }


        /* =========================================================
           SERVICES
        ========================================================== */

        .services-section {

            background: white;

        }


        .services-header {

            display: flex;

            justify-content:
                space-between;

            align-items:
                flex-end;

            margin-bottom: 65px;

        }


        .services-grid {

            display: grid;

            grid-template-columns:
                repeat(3,1fr);

            border-top:
                1px solid var(--border);

            border-left:
                1px solid var(--border);

        }


        .service-card {

            padding:
                38px
                32px
                42px;

            min-height: 280px;

            border-right:
                1px solid var(--border);

            border-bottom:
                1px solid var(--border);

            transition: .35s ease;

            position: relative;

            background: white;

        }


        .service-card:hover {

            background: #f5f5f3;

            transform:
                translateY(-4px);

        }


        .service-icon {

            width: 42px;

            height: 42px;

            background: #f0f0ee;

            display: flex;

            align-items: center;

            justify-content: center;

            margin-bottom: 25px;

        }


        .service-number {

            position: absolute;

            right: 25px;

            top: 25px;

            font-size: 11px;

            color: #bbb;

        }


        .service-card h3 {

            font-family:
                var(--serif);

            font-size: 21px;

            margin-bottom: 13px;

        }


        .service-card p {

            color: #737373;

            font-size: 14px;

            line-height: 1.75;

        }


        .service-link {

            display: inline-flex;

            margin-top: 20px;

            font-size: 12px;

            font-weight: 700;

            gap: 8px;

            align-items: center;

        }


        /* =========================================================
           STATS
        ========================================================== */

        .stats-section {

            background: #f5f5f3;

            padding: 75px 0;

        }


        .stats-grid {

            display: grid;

            grid-template-columns:
                repeat(4,1fr);

            gap: 1px;

            background:
                #d8d8d5;

        }


        .stat {

            background:
                #f5f5f3;

            padding:
                25px 30px;

            text-align: center;

        }


        .stat-number {

            font-family:
                var(--serif);

            font-size: 40px;

            font-weight: 600;

        }


        .stat-label {

            color: #777;

            font-size: 10px;

            text-transform:
                uppercase;

            letter-spacing: 1px;

        }


        /* =========================================================
           ABOUT
        ========================================================== */

        .about-section {

            background: #f5f5f3;

        }


        .about-grid {

            display: grid;

            grid-template-columns:
                .9fr 1.1fr;

            gap: 100px;

            align-items: center;

        }


        .about-box {

            background: black;

            color: white;

            padding:
                65px 55px;

            min-height: 450px;

            display: flex;

            flex-direction:
                column;

            justify-content:
                space-between;

            position: relative;

            overflow: hidden;

        }


        .about-box::before {

            content: "MK";

            position: absolute;

            right: -20px;

            bottom: -80px;

            font-family:
                var(--serif);

            font-size: 240px;

            color:
                rgba(
                    255,
                    255,
                    255,
                    .035
                );

            font-weight: 700;

        }


        .about-box small {

            color: #999;

            letter-spacing: 2px;

            font-size: 10px;

        }


        .about-box h3 {

            font-family:
                var(--serif);

            font-size: 45px;

            line-height: 1.1;

            position: relative;

        }


        .about-box p {

            color: #aaa;

            font-size: 14px;

            position: relative;

        }


        .about-content p {

            color: #666;

            font-size: 16px;

            line-height: 1.9;

            margin-top: 25px;

        }


        .benefits {

            margin-top: 35px;

            display: grid;

            grid-template-columns:
                1fr 1fr;

            gap: 22px 30px;

        }


        .benefit {

            display: flex;

            gap: 13px;

            align-items:
                flex-start;

        }


        .benefit-icon {

            width: 30px;

            height: 30px;

            background: black;

            color: white;

            border-radius: 50%;

            display: flex;

            align-items: center;

            justify-content: center;

            font-size: 11px;

            flex-shrink: 0;

        }


        .benefit strong {

            display: block;

            font-size: 14px;

            margin-bottom: 3px;

        }


        .benefit span {

            display: block;

            color: #777;

            font-size: 12px;

        }


        /* =========================================================
           PROCESS
        ========================================================== */

        .process-section {

            background: black;

            color: white;

        }


        .process-section
        .section-kicker {

            color: #a68b60;

        }


        .process-section
        .section-intro {

            color: #888;

        }


        .process-grid {

            margin-top: 65px;

            display: grid;

            grid-template-columns:
                repeat(4,1fr);

            border-top:
                1px solid #292929;

            border-left:
                1px solid #292929;

        }


        .process-card {

            padding:
                35px
                30px
                45px;

            border-right:
                1px solid #292929;

            border-bottom:
                1px solid #292929;

        }


        .process-number {

            font-family:
                var(--serif);

            font-size: 38px;

            color: #555;

            margin-bottom: 35px;

        }


        .process-card h3 {

            font-family:
                var(--serif);

            font-size: 22px;

            margin-bottom: 12px;

        }


        .process-card p {

            color: #888;

            font-size: 13px;

            line-height: 1.75;

        }


        /* =========================================================
           REVIEWS
        ========================================================== */

        .reviews-section {

            background: #f5f5f3;

        }


        .reviews-header {

            display: flex;

            justify-content:
                space-between;

            align-items:
                flex-end;

            margin-bottom: 55px;

        }


        .google-rating {

            border:
                1px solid #d5d5d5;

            background: white;

            padding:
                18px 25px;

            display: flex;

            align-items: center;

            gap: 20px;

            transition: .3s ease;

        }


        .google-rating:hover {

            transform:
                translateY(-3px);

            box-shadow:
                0 10px 30px
                rgba(0,0,0,.06);

        }


        .google-score {

            font-family:
                var(--serif);

            font-size: 32px;

            font-weight: 600;

        }


        .google-stars {

            font-size: 12px;

            letter-spacing: 2px;

        }


        .google-text {

            color: #777;

            font-size: 10px;

        }


        .reviews-grid {

            display: grid;

            grid-template-columns:
                1fr 1fr;

            gap: 20px;

        }


        .review-card {

            background: white;

            border:
                1px solid #ddd;

            padding: 28px;

            transition: .3s ease;

        }


        .review-card:hover {

            transform:
                translateY(-3px);

            box-shadow:
                0 15px 40px
                rgba(0,0,0,.05);

        }


        .review-top {

            display: flex;

            justify-content:
                space-between;

            align-items:
                flex-start;

            margin-bottom: 22px;

        }


        .review-person {

            display: flex;

            align-items: center;

            gap: 13px;

        }


        .review-avatar {

            width: 40px;

            height: 40px;

            border-radius: 50%;

            background: black;

            color: white;

            display: flex;

            align-items: center;

            justify-content: center;

            font-size: 12px;

            font-weight: 600;

        }


        .review-name {

            font-size: 13px;

            font-weight: 700;

        }


        .review-date {

            color: #999;

            font-size: 10px;

        }


        .review-stars {

            font-size: 11px;

            letter-spacing: 1px;

        }


        .review-text {

            color: #666;

            font-size: 13px;

            line-height: 1.8;

        }


        /* =========================================================
           FAQ
        ========================================================== */

        .faq-section {

            background: white;

        }


        .faq-wrapper {

            max-width: 850px;

            margin:
                55px auto 0;

        }


        .faq-item {

            border-top:
                1px solid #ddd;

        }


        .faq-item:last-child {

            border-bottom:
                1px solid #ddd;

        }


        .faq-question {

            width: 100%;

            border: none;

            background: transparent;

            display: flex;

            justify-content:
                space-between;

            align-items: center;

            text-align: left;

            padding: 23px 0;

            font-family:
                var(--serif);

            font-size: 19px;

            cursor: pointer;

        }


        .faq-question i {

            font-family:
                var(--sans);

            font-size: 12px;

            transition: .3s ease;

        }


        .faq-answer {

            max-height: 0;

            overflow: hidden;

            transition:
                max-height .35s ease;

        }


        .faq-answer p {

            color: #777;

            font-size: 14px;

            line-height: 1.8;

            padding-bottom: 25px;

            max-width: 760px;

        }


        .faq-item.active
        .faq-question i {

            transform:
                rotate(45deg);

        }


        /* =========================================================
           CONTACT
        ========================================================== */

        .contact-section {

            background: black;

            color: white;

        }


        .contact-grid {

            display: grid;

            grid-template-columns:
                1fr .9fr;

            gap: 100px;

        }


        .contact-section
        .section-kicker {

            color: #a68b60;

        }


        .contact-section
        .section-intro {

            color: #8d8d8d;

        }


        .contact-details {

            margin-top: 45px;

        }


        .contact-item {

            display: flex;

            gap: 17px;

            padding: 18px 0;

            border-bottom:
                1px solid #272727;

        }


        .contact-item i {

            width: 20px;

            color: #aaa;

            margin-top: 3px;

        }


        .contact-item-label {

            color: #666;

            font-size: 9px;

            letter-spacing: 1.5px;

            text-transform:
                uppercase;

        }


        .contact-item-value {

            margin-top: 3px;

            font-size: 14px;

        }


        .contact-card {

            background:
                #f4f4f1;

            color: black;

            padding: 45px;

            align-self:
                flex-start;

        }


        .contact-card h3 {

            font-family:
                var(--serif);

            font-size: 31px;

            margin-bottom: 10px;

        }


        .contact-card p {

            color: #707070;

            font-size: 13px;

            line-height: 1.7;

            margin-bottom: 25px;

        }


        .contact-buttons {

            display: grid;

            gap: 10px;

        }


        .contact-buttons .btn {

            width: 100%;

        }


        .contact-buttons
        .btn-primary {

            background: black;

            color: white;

            border-color: black;

        }


        .contact-buttons
        .btn-primary:hover {

            background: transparent;

            color: black;

        }


        .contact-buttons
        .btn-outline {

            color: black;

            border-color: #aaa;

        }


        .contact-buttons
        .btn-outline:hover {

            background: black;

            color: white;

        }


        /* =========================================================
           FOOTER
        ========================================================== */

        footer {

            background: #050505;

            color: white;

            border-top:
                1px solid #222;

            padding:
                50px 0 25px;

        }


        .footer-top {

            display: grid;

            grid-template-columns:
                1.3fr 1fr 1fr;

            gap: 50px;

            padding-bottom: 45px;

            border-bottom:
                1px solid #222;

        }


        .footer-brand p {

            color: #777;

            max-width: 380px;

            margin-top: 15px;

            font-size: 12px;

            line-height: 1.8;

        }


        .footer-title {

            font-size: 11px;

            letter-spacing: 1.5px;

            text-transform:
                uppercase;

            color: #888;

            margin-bottom: 17px;

        }


        .footer-links {

            display: grid;

            gap: 9px;

            color: #aaa;

            font-size: 12px;

        }


        .footer-links a:hover {

            color: white;

        }


        .footer-bottom {

            display: flex;

            justify-content:
                space-between;

            gap: 20px;

            padding-top: 22px;

            color: #555;

            font-size: 10px;

        }


        /* =========================================================
           WHATSAPP
        ========================================================== */

        .whatsapp-float {

            position: fixed;

            right: 25px;

            bottom: 25px;

            width: 55px;

            height: 55px;

            background: #25d366;

            color: white;

            border-radius: 50%;

            display: flex;

            align-items: center;

            justify-content: center;

            font-size: 25px;

            z-index: 999;

            box-shadow:
                0 10px 30px
                rgba(0,0,0,.2);

            transition: .3s ease;

        }


        .whatsapp-float:hover {

            transform:
                translateY(-4px)
                scale(1.04);

        }


        /* =========================================================
           BACK TO TOP
        ========================================================== */

        .back-top {

            position: fixed;

            right: 25px;

            bottom: 95px;

            width: 42px;

            height: 42px;

            background: black;

            color: white;

            border:
                1px solid #333;

            display: flex;

            align-items: center;

            justify-content: center;

            cursor: pointer;

            opacity: 0;

            visibility: hidden;

            transition: .3s ease;

            z-index: 999;

        }


        .back-top.show {

            opacity: 1;

            visibility: visible;

        }


        /* =========================================================
           SCROLL ANIMATION
        ========================================================== */

        .reveal {

            opacity: 0;

            transform:
                translateY(30px);

            transition:
                opacity .8s ease,
                transform .8s ease;

        }


        .reveal.visible {

            opacity: 1;

            transform:
                translateY(0);

        }


        /* =========================================================
           MOBILE
        ========================================================== */

        @media(max-width:900px) {


            .nav-links {

                position: absolute;

                top: 72px;

                left: 0;

                width: 100%;

                background: #090909;

                padding: 20px;

                display: none;

                flex-direction:
                    column;

                align-items:
                    stretch;

                gap: 0;

                border-bottom:
                    1px solid #222;

            }


            .nav-links.active {

                display: flex;

            }


            .nav-links a {

                padding: 14px 0;

                border-bottom:
                    1px solid #222;

            }


            .nav-cta {

                text-align: center;

                margin-top: 10px;

            }


            .menu-btn {

                display: block;

            }


            .hero-grid {

                grid-template-columns:
                    1fr;

                gap: 60px;

            }


            .hero-visual {

                min-height: 430px;

            }


            .floating-logo {

                right: 10%;

            }


            .services-grid {

                grid-template-columns:
                    1fr 1fr;

            }


            .about-grid {

                grid-template-columns:
                    1fr;

                gap: 50px;

            }


            .process-grid {

                grid-template-columns:
                    1fr 1fr;

            }


            .contact-grid {

                grid-template-columns:
                    1fr;

                gap: 50px;

            }


            .footer-top {

                grid-template-columns:
                    1fr 1fr;

            }

        }


        @media(max-width:650px) {


            .container {

                width:
                    min(
                        calc(100% - 30px),
                        var(--container)
                    );

            }


            section {

                padding: 80px 0;

            }


            .navbar {

                height: 65px;

            }


            .nav-links {

                top: 65px;

            }


            .brand-name {

                font-size: 13px;

            }


            .brand-logo {

                width: 36px;

                height: 36px;

            }


            .hero {

                padding-top: 65px;

            }


            .hero-grid {

                padding: 65px 0;

            }


            .hero h1 {

                font-size: 51px;

                letter-spacing: -1px;

            }


            .hero-description {

                font-size: 15px;

            }


            .hero-contact {

                gap: 20px;

                flex-wrap: wrap;

            }


            .floating-logo {

                width: 130px;

                height: 130px;

                right: 2%;

            }


            .floating-logo-image {

                width: 95px;

                height: 95px;

            }


            .business-card {

                margin-top: 100px;

                padding:
                    17px
                    18px
                    14px;

            }


            .card-logo {

                width: 65px;

                height: 65px;

            }


            .card-title {

                font-size: 20px;

            }


            .card-top {

                font-size: 13px;

            }


            .card-phone {

                font-size: 10px;

            }


            .card-footer {

                margin-left: -18px;

                margin-right: -18px;

                margin-bottom: -14px;

                padding:
                    10px
                    14px;

                font-size: 8px;

            }


            .services-header,
            .reviews-header {

                display: block;

            }


            .services-grid {

                grid-template-columns:
                    1fr;

            }


            .service-card {

                min-height: auto;

            }


            .benefits {

                grid-template-columns:
                    1fr;

            }


            .process-grid {

                grid-template-columns:
                    1fr;

            }


            .stats-grid {

                grid-template-columns:
                    1fr 1fr;

            }


            .reviews-grid {

                grid-template-columns:
                    1fr;

            }


            .google-rating {

                margin-top: 25px;

                width: fit-content;

            }


            .contact-card {

                padding:
                    30px 25px;

            }


            .footer-top {

                grid-template-columns:
                    1fr;

            }


            .footer-bottom {

                flex-direction:
                    column;

            }


            .whatsapp-float {

                width: 50px;

                height: 50px;

                right: 18px;

                bottom: 18px;

            }


            .back-top {

                right: 18px;

                bottom: 80px;

            }

        }

    </style>

</head>


<body>


<!-- =========================================================
     HEADER
========================================================== -->

<header id="header">

    <div class="container">

        <nav class="navbar">


            <a href="#home"
               class="brand">


                <!-- ACTUAL GITHUB LOGO -->

                <div class="brand-logo">

                    <img src="logo.jpeg"
                         alt="M|&|K Accounts Logo">

                </div>


                <div class="brand-text">

                    <div class="brand-name">
                        M|&|K ACCOUNTS
                    </div>

                    <div class="brand-sub">
                        REMOTE OPERATIONS
                    </div>

                </div>

            </a>


            <div class="nav-links"
                 id="navLinks">

                <a href="#services">
                    Services
                </a>

                <a href="#about">
                    About
                </a>

                <a href="#reviews">
                    Reviews
                </a>

                <a href="#faq">
                    FAQ
                </a>

                <a href="#contact"
                   class="nav-cta">

                    Get in Touch

                </a>

            </div>


            <button class="menu-btn"
                    id="menuBtn"
                    aria-label="Open Menu">

                <i class="fa-solid fa-bars"></i>

            </button>

        </nav>

    </div>

</header>



<!-- =========================================================
     HERO
========================================================== -->

<main>


<section class="hero"
         id="home">

    <div class="container">

        <div class="hero-grid">


            <div class="hero-content reveal">


                <div class="rating-line">

                    <span class="stars">
                        ★★★★★
                    </span>

                    <strong>
                        5.0
                    </strong>

                    <span>
                        ·
                    </span>

                    <span>
                        6 Reviews on Google
                    </span>

                </div>


                <h1>

                    Trusted

                    <span>
                        Accounting
                    </span>

                    Services

                </h1>


                <p class="hero-description">

                    GST Returns, Income Tax, TDS,
                    bookkeeping and professional
                    accounting support — currently
                    serving clients across Haryana,
                    with a vision to work with clients
                    PAN India.

                </p>


                <div class="hero-buttons">


                    <a href="#contact"
                       class="btn btn-primary">

                        Get a Free Consultation

                        <i class="fa-solid fa-arrow-right"></i>

                    </a>


                    <a href="#services"
                       class="btn btn-outline">

                        Our Services

                    </a>


                </div>


                <div class="hero-contact">


                    <div class="hero-contact-item">

                        <div class="hero-contact-label">
                            MANAV
                        </div>

                        <a href="tel:+919817571705"
                           class="hero-contact-number">

                            98175-71705

                        </a>

                    </div>


                    <div class="hero-contact-item">

                        <div class="hero-contact-label">
                            KRISH
                        </div>

                        <a href="tel:+919992075501"
                           class="hero-contact-number">

                            99920-75501

                        </a>

                    </div>


                    <div class="hero-contact-item">

                        <div class="hero-contact-label">
                            PRIMARY EMAIL
                        </div>

                        <a href="mailto:Info@mkaccounts.in"
                           class="hero-contact-number">

                            Info@mkaccounts.in

                        </a>

                    </div>


                </div>

            </div>



            <!-- =================================================
                 HERO VISUAL
            ================================================== -->

            <div class="hero-visual reveal">


                <!-- ACTUAL GITHUB LOGO -->

                <div class="floating-logo">

                    <img src="logo.jpeg"
                         alt="M|&|K Accounts Logo"
                         class="floating-logo-image">

                </div>


                <div class="business-card">


                    <div class="card-top">


                        <div>

                            MANAV

                            <span class="card-phone">

                                <i class="fa-solid fa-phone"></i>

                                98175-71705

                            </span>

                        </div>


                        <div style="text-align:right">

                            KRISH

                            <span class="card-phone">

                                <i class="fa-solid fa-phone"></i>

                                99920-75501

                            </span>

                        </div>


                    </div>


                    <!-- ACTUAL GITHUB LOGO -->

                    <div class="card-logo">

                        <img src="logo.jpeg"
                             alt="M|&|K Accounts Logo">

                    </div>


                    <div class="card-title">
                        M|&|K ACCOUNTS
                    </div>


                    <div class="card-services">

                        <strong>
                            Services Rendered :
                        </strong>

                        GST Returns, Income Tax Returns,
                        TDS, Part-Time Accounting

                    </div>


                    <div class="card-footer">

                        <span>

                            <i class="fa-regular fa-envelope"></i>

                            Info@mkaccounts.in

                        </span>


                        <span>

                            Haryana | Remote Operations

                        </span>

                    </div>


                </div>

            </div>

        </div>

    </div>

</section>



<!-- =========================================================
     SERVICES
========================================================== -->

<section class="services-section"
         id="services">

    <div class="container">


        <div class="services-header reveal">


            <div>

                <div class="section-kicker">
                    What We Offer
                </div>

                <h2 class="section-title">

                    Comprehensive<br>

                    Financial Services

                </h2>

            </div>


            <p class="section-intro">

                Practical accounting and compliance
                solutions designed for individuals,
                professionals, startups, small businesses
                and growing enterprises.

            </p>


        </div>



        <div class="services-grid">


            <article class="service-card reveal">

                <span class="service-number">
                    01
                </span>

                <div class="service-icon">

                    <i class="fa-regular fa-file-lines"></i>

                </div>

                <h3>
                    GST Returns
                </h3>

                <p>

                    GST registration, GSTR-1,
                    GSTR-3B, annual return support,
                    reconciliation, notices and
                    routine GST compliance.

                </p>

                <a href="#contact"
                   class="service-link">

                    Discuss GST

                    <i class="fa-solid fa-arrow-right"></i>

                </a>

            </article>



            <article class="service-card reveal">

                <span class="service-number">
                    02
                </span>

                <div class="service-icon">

                    <i class="fa-solid fa-calculator"></i>

                </div>

                <h3>
                    Income Tax Returns
                </h3>

                <p>

                    ITR filing support for individuals,
                    HUFs, professionals and businesses,
                    along with income reconciliation
                    and tax planning support.

                </p>

                <a href="#contact"
                   class="service-link">

                    Discuss Income Tax

                    <i class="fa-solid fa-arrow-right"></i>

                </a>

            </article>



            <article class="service-card reveal">

                <span class="service-number">
                    03
                </span>

                <div class="service-icon">

                    <i class="fa-solid fa-chart-line"></i>

                </div>

                <h3>
                    TDS Compliance
                </h3>

                <p>

                    TDS deduction, payment,
                    quarterly return preparation,
                    reconciliation, certificates
                    and compliance support.

                </p>

                <a href="#contact"
                   class="service-link">

                    Discuss TDS

                    <i class="fa-solid fa-arrow-right"></i>

                </a>

            </article>



            <article class="service-card reveal">

                <span class="service-number">
                    04
                </span>

                <div class="service-icon">

                    <i class="fa-solid fa-users"></i>

                </div>

                <h3>
                    Part-Time Accounting
                </h3>

                <p>

                    Remote bookkeeping, ledger
                    maintenance, bank reconciliation,
                    accounts payable, receivables
                    and financial statement preparation.

                </p>

                <a href="#contact"
                   class="service-link">

                    Outsource Accounts

                    <i class="fa-solid fa-arrow-right"></i>

                </a>

            </article>



            <article class="service-card reveal">

                <span class="service-number">
                    05
                </span>

                <div class="service-icon">

                    <i class="fa-solid fa-shield-halved"></i>

                </div>

                <h3>
                    Audit & Assurance
                </h3>

                <p>

                    Accounting and audit support,
                    financial statement preparation,
                    tax audit assistance and
                    internal review engagements,
                    as applicable.

                </p>

                <a href="#contact"
                   class="service-link">

                    Discuss Requirements

                    <i class="fa-solid fa-arrow-right"></i>

                </a>

            </article>



            <article class="service-card reveal">

                <span class="service-number">
                    06
                </span>

                <div class="service-icon">

                    <i class="fa-regular fa-building"></i>

                </div>

                <h3>
                    Business Registration
                </h3>

                <p>

                    Support for Pvt Ltd, LLP,
                    Partnership and Sole Proprietorship
                    setup along with applicable
                    registration and compliance assistance.

                </p>

                <a href="#contact"
                   class="service-link">

                    Start a Business

                    <i class="fa-solid fa-arrow-right"></i>

                </a>

            </article>


        </div>

    </div>

</section>



<!-- =========================================================
     STATS
========================================================== -->

<section class="stats-section">

    <div class="container">


        <div class="stats-grid reveal">


            <div class="stat">

                <div class="stat-number">
                    5.0
                </div>

                <div class="stat-label">
                    Google Rating
                </div>

            </div>


            <div class="stat">

                <div class="stat-number">
                    6+
                </div>

                <div class="stat-label">
                    Google Reviews
                </div>

            </div>


            <div class="stat">

                <div class="stat-number">
                    Haryana
                </div>

                <div class="stat-label">
                    Current Service Area
                </div>

            </div>


            <div class="stat">

                <div class="stat-number">
                    PAN India
                </div>

                <div class="stat-label">
                    Future Client Reach
                </div>

            </div>


        </div>

    </div>

</section>



<!-- =========================================================
     ABOUT
========================================================== -->

<section class="about-section"
         id="about">

    <div class="container">


        <div class="about-grid">


            <div class="about-box reveal">


                <small>
                    M|&|K ACCOUNTS
                </small>


                <h3>

                    Your Accounts.<br>

                    Our Responsibility.

                </h3>


                <p>

                    Reliable accounting support
                    without the overhead of maintaining
                    a full-time accounts department.

                </p>


            </div>



            <div class="about-content reveal">


                <div class="section-kicker">
                    Why Choose Us
                </div>


                <h2 class="section-title">

                    Professional support,
                    without the complexity.

                </h2>


                <p>

                    M|&|K Accounts provides professional
                    accounting, taxation and compliance
                    support to businesses, professionals
                    and individuals. We are currently
                    serving clients across Haryana through
                    remote operations, while looking forward
                    to working with clients PAN India.

                </p>


                <div class="benefits">


                    <div class="benefit">

                        <div class="benefit-icon">

                            <i class="fa-solid fa-check"></i>

                        </div>

                        <div>

                            <strong>
                                Remote Operations
                            </strong>

                            <span>
                                Currently serving clients across Haryana.
                            </span>

                        </div>

                    </div>


                    <div class="benefit">

                        <div class="benefit-icon">

                            <i class="fa-solid fa-check"></i>

                        </div>

                        <div>

                            <strong>
                                Timely Compliance
                            </strong>

                            <span>
                                Stay organised around your filing deadlines.
                            </span>

                        </div>

                    </div>


                    <div class="benefit">

                        <div class="benefit-icon">

                            <i class="fa-solid fa-check"></i>

                        </div>

                        <div>

                            <strong>
                                Clear Communication
                            </strong>

                            <span>
                                Straightforward explanations and support.
                            </span>

                        </div>

                    </div>


                    <div class="benefit">

                        <div class="benefit-icon">

                            <i class="fa-solid fa-check"></i>

                        </div>

                        <div>

                            <strong>
                                Flexible Engagement
                            </strong>

                            <span>
                                Suitable for part-time and outsourced accounts.
                            </span>

                        </div>

                    </div>


                    <div class="benefit">

                        <div class="benefit-icon">

                            <i class="fa-solid fa-earth-asia"></i>

                        </div>

                        <div>

                            <strong>
                                PAN India Expansion
                            </strong>

                            <span>
                                Looking forward to working with clients across India.
                            </span>

                        </div>

                    </div>


                    <div class="benefit">

                        <div class="benefit-icon">

                            <i class="fa-solid fa-location-dot"></i>

                        </div>

                        <div>

                            <strong>
                                Based in Hisar
                            </strong>

                            <span>
                                Serving Haryana through remote operations.
                            </span>

                        </div>

                    </div>


                </div>


            </div>

        </div>

    </div>

</section>



<!-- =========================================================
     PROCESS
========================================================== -->

<section class="process-section">

    <div class="container">


        <div class="section-kicker reveal">
            How We Work
        </div>


        <h2 class="section-title reveal">

            Simple. Structured.<br>

            Reliable.

        </h2>


        <p class="section-intro reveal">

            A straightforward process designed
            to make accounting and compliance
            easier for you.

        </p>


        <div class="process-grid">


            <div class="process-card reveal">

                <div class="process-number">
                    01
                </div>

                <h3>
                    Understand
                </h3>

                <p>

                    We understand your business,
                    transactions, accounting system
                    and compliance requirements.

                </p>

            </div>


            <div class="process-card reveal">

                <div class="process-number">
                    02
                </div>

                <h3>
                    Organise
                </h3>

                <p>

                    Documents, invoices, bank
                    transactions and accounting records
                    are organised systematically.

                </p>

            </div>


            <div class="process-card reveal">

                <div class="process-number">
                    03
                </div>

                <h3>
                    Comply
                </h3>

                <p>

                    Required accounting and tax
                    compliances are prepared and
                    handled according to applicable
                    requirements.

                </p>

            </div>


            <div class="process-card reveal">

                <div class="process-number">
                    04
                </div>

                <h3>
                    Support
                </h3>

                <p>

                    We remain available for queries,
                    reconciliations, reports and
                    ongoing accounting support.

                </p>

            </div>


        </div>

    </div>

</section>



<!-- =========================================================
     REVIEWS
========================================================== -->

<section class="reviews-section"
         id="reviews">

    <div class="container">


        <div class="reviews-header reveal">


            <div>

                <div class="section-kicker">
                    Client Feedback
                </div>

                <h2 class="section-title">
                    What Our Clients Say
                </h2>

            </div>


            <a href="https://maps.app.goo.gl/D4xPndjc2F5G5AT7A"
               target="_blank"
               rel="noopener"
               class="google-rating">


                <div class="google-score">
                    5.0
                </div>


                <div>

                    <div class="google-stars">
                        ★★★★★
                    </div>

                    <div class="google-text">
                        6 reviews · Google Maps
                    </div>

                </div>


            </a>


        </div>



        <div class="reviews-grid">


            <div class="review-card reveal">


                <div class="review-top">


                    <div class="review-person">

                        <div class="review-avatar">
                            MS
                        </div>

                        <div>

                            <div class="review-name">
                                Mohit Singh
                            </div>

                            <div class="review-date">
                                4 months ago
                            </div>

                        </div>

                    </div>


                    <div class="review-stars">
                        ★★★★★
                    </div>


                </div>


                <p class="review-text">

                    I am very impressed with the service.
                    Professional, timely, and extremely
                    helpful throughout the entire tax
                    filing process.

                </p>


            </div>



            <div class="review-card reveal">


                <div class="review-top">


                    <div class="review-person">

                        <div class="review-avatar">
                            DT
                        </div>

                        <div>

                            <div class="review-name">
                                Deepanshu Tomar
                            </div>

                            <div class="review-date">
                                4 months ago
                            </div>

                        </div>

                    </div>


                    <div class="review-stars">
                        ★★★★★
                    </div>


                </div>


                <p class="review-text">

                    Loved it. The team handled all my GST
                    filings seamlessly and explained every
                    step clearly. Highly recommend to any
                    business owner.

                </p>


            </div>



            <div class="review-card reveal">


                <div class="review-top">


                    <div class="review-person">

                        <div class="review-avatar">
                            MS
                        </div>

                        <div>

                            <div class="review-name">
                                Mohit Sharma
                            </div>

                            <div class="review-date">
                                1 month ago
                            </div>

                        </div>

                    </div>


                    <div class="review-stars">
                        ★★★★★
                    </div>


                </div>


                <p class="review-text">

                    Quick turnaround, transparent pricing
                    and thorough documentation. Exactly
                    what I needed for my small business
                    accounts.

                </p>


            </div>



            <div class="review-card reveal">


                <div class="review-top">


                    <div class="review-person">

                        <div class="review-avatar">
                            MP
                        </div>

                        <div>

                            <div class="review-name">
                                Manav Pruthi
                            </div>

                            <div class="review-date">
                                4 months ago
                            </div>

                        </div>

                    </div>


                    <div class="review-stars">
                        ★★★★★
                    </div>


                </div>


                <p class="review-text">

                    Excellent accounting service. Very
                    knowledgeable staff and easy to work
                    with. They saved me both time and money.

                </p>


            </div>


        </div>



        <div style="
            text-align:center;
            margin-top:40px;
        ">


            <a href="https://maps.app.goo.gl/D4xPndjc2F5G5AT7A"
               target="_blank"
               rel="noopener"
               class="btn"
               style="
                    color:#111;
                    border-color:#aaa;
               ">

                <i class="fa-brands fa-google"></i>

                View Google Reviews

            </a>


        </div>


    </div>

</section>



<!-- =========================================================
     FAQ
========================================================== -->

<section class="faq-section"
         id="faq">

    <div class="container">


        <div class="section-kicker">
            Frequently Asked Questions
        </div>


        <h2 class="section-title">
            Questions, answered.
        </h2>


        <div class="faq-wrapper">


            <div class="faq-item">

                <button class="faq-question">

                    What areas do you currently serve?

                    <i class="fa-solid fa-plus"></i>

                </button>


                <div class="faq-answer">

                    <p>

                        M|&|K Accounts is currently serving
                        clients across Haryana through remote
                        operations. We are also looking forward
                        to expanding our client base and working
                        with clients PAN India.

                    </p>

                </div>

            </div>



            <div class="faq-item">

                <button class="faq-question">

                    Do you provide remote accounting services?

                    <i class="fa-solid fa-plus"></i>

                </button>


                <div class="faq-answer">

                    <p>

                        Yes. Our accounting operations are
                        primarily handled remotely, allowing
                        clients to share documents, accounting
                        data and requirements digitally.

                    </p>

                </div>

            </div>



            <div class="faq-item">

                <button class="faq-question">

                    What accounting services do you provide?

                    <i class="fa-solid fa-plus"></i>

                </button>


                <div class="faq-answer">

                    <p>

                        Our accounting services include
                        bookkeeping, ledger maintenance,
                        bank reconciliation, accounts payable
                        and receivable, accounting entries and
                        financial statement preparation.

                    </p>

                </div>

            </div>



            <div class="faq-item">

                <button class="faq-question">

                    Do you handle GST returns?

                    <i class="fa-solid fa-plus"></i>

                </button>


                <div class="faq-answer">

                    <p>

                        We provide GST registration and return
                        filing support, including GSTR-1 and
                        GSTR-3B, along with reconciliation and
                        other applicable GST compliance assistance.

                    </p>

                </div>

            </div>



            <div class="faq-item">

                <button class="faq-question">

                    Do you provide Income Tax return filing?

                    <i class="fa-solid fa-plus"></i>

                </button>


                <div class="faq-answer">

                    <p>

                        Yes. We provide Income Tax return
                        preparation and filing support for
                        eligible individuals, professionals,
                        HUFs and businesses.

                    </p>

                </div>

            </div>



            <div class="faq-item">

                <button class="faq-question">

                    How can I get a quotation?

                    <i class="fa-solid fa-plus"></i>

                </button>


                <div class="faq-answer">

                    <p>

                        Contact us through WhatsApp, phone or
                        email with your basic requirements.
                        We can understand your work volume and
                        compliance requirements and discuss the
                        appropriate engagement.

                    </p>

                </div>

            </div>



        </div>

    </div>

</section>



<!-- =========================================================
     CONTACT
========================================================== -->

<section class="contact-section"
         id="contact">

    <div class="container">


        <div class="contact-grid">


            <div class="reveal">


                <div class="section-kicker">
                    Get In Touch
                </div>


                <h2 class="section-title">

                    Let's take care
                    of your accounts.

                </h2>


                <p class="section-intro">

                    M|&|K Accounts is currently serving
                    clients across Haryana through remote
                    operations. We are looking forward
                    to working with businesses and individuals
                    from across India as we expand our services
                    PAN India.

                </p>


                <div class="contact-details">


                    <!-- MANAV -->

                    <div class="contact-item">

                        <i class="fa-solid fa-phone"></i>

                        <div>

                            <div class="contact-item-label">
                                Manav
                            </div>

                            <a href="tel:+919817571705"
                               class="contact-item-value">

                                +91 98175 71705

                            </a>

                        </div>

                    </div>


                    <!-- KRISH -->

                    <div class="contact-item">

                        <i class="fa-solid fa-phone"></i>

                        <div>

                            <div class="contact-item-label">
                                Krish
                            </div>

                            <a href="tel:+919992075501"
                               class="contact-item-value">

                                +91 99920 75501

                            </a>

                        </div>

                    </div>


                    <!-- PRIMARY EMAIL -->

                    <div class="contact-item">

                        <i class="fa-regular fa-envelope"></i>

                        <div>

                            <div class="contact-item-label">
                                Primary Email
                            </div>

                            <a href="mailto:Info@mkaccounts.in"
                               class="contact-item-value">

                                Info@mkaccounts.in

                            </a>

                        </div>

                    </div>


                    <!-- SECONDARY EMAIL -->

                    <div class="contact-item">

                        <i class="fa-regular fa-envelope"></i>

                        <div>

                            <div class="contact-item-label">
                                Secondary Email
                            </div>

                            <a href="mailto:ta.solution.hisar@gmail.com"
                               class="contact-item-value">

                                ta.solution.hisar@gmail.com

                            </a>

                        </div>

                    </div>


                    <!-- CURRENT SERVICE AREA -->

                    <div class="contact-item">

                        <i class="fa-solid fa-location-dot"></i>

                        <div>

                            <div class="contact-item-label">
                                Current Service Area / Work Location
                            </div>

                            <div class="contact-item-value">

                                Haryana

                            </div>

                        </div>

                    </div>


                    <!-- PAN INDIA -->

                    <div class="contact-item">

                        <i class="fa-solid fa-earth-asia"></i>

                        <div>

                            <div class="contact-item-label">
                                Looking Forward To
                            </div>

                            <div class="contact-item-value">

                                Working with clients PAN India

                            </div>

                        </div>

                    </div>


                    <!-- ADDRESS -->

                    <div class="contact-item">

                        <i class="fa-solid fa-map-pin"></i>

                        <div>

                            <div class="contact-item-label">
                                Address
                            </div>

                            <div class="contact-item-value">

                                Street No. 5,
                                Chotu Ram Colony,<br>

                                Hisar, Haryana -
                                125001

                            </div>

                        </div>

                    </div>


                </div>


            </div>



            <!-- =================================================
                 CONTACT CARD
            ================================================== -->

            <div class="contact-card reveal">


                <h3>
                    Start a conversation.
                </h3>


                <p>

                    Tell us about your accounting,
                    taxation or compliance requirement.
                    Send us a message and we will get
                    back to you.

                </p>


                <div class="contact-buttons">


                    <!-- PRIMARY EMAIL -->

                    <a href="mailto:Info@mkaccounts.in"
                       class="btn btn-primary">

                        <i class="fa-regular fa-envelope"></i>

                        Email Us

                    </a>


                    <!-- SECONDARY EMAIL -->

                    <a href="mailto:ta.solution.hisar@gmail.com"
                       class="btn btn-outline">

                        <i class="fa-regular fa-envelope"></i>

                        Secondary Email

                    </a>


                    <!-- WHATSAPP MANAV -->

                    <a href="https://wa.me/919817571705"
                       target="_blank"
                       rel="noopener"
                       class="btn btn-outline">

                        <i class="fa-brands fa-whatsapp"></i>

                        WhatsApp Manav

                    </a>


                    <!-- WHATSAPP KRISH -->

                    <a href="https://wa.me/919992075501"
                       target="_blank"
                       rel="noopener"
                       class="btn btn-outline">

                        <i class="fa-brands fa-whatsapp"></i>

                        WhatsApp Krish

                    </a>


                    <!-- CALL -->

                    <a href="tel:+919817571705"
                       class="btn btn-outline">

                        <i class="fa-solid fa-phone"></i>

                        Call Us

                    </a>


                    <!-- GOOGLE MAPS -->

                    <a href="https://maps.app.goo.gl/D4xPndjc2F5G5AT7A"
                       target="_blank"
                       rel="noopener"
                       class="btn btn-outline">

                        <i class="fa-solid fa-map-location-dot"></i>

                        Google Maps

                    </a>


                </div>


            </div>


        </div>

    </div>

</section>


</main>



<!-- =========================================================
     FOOTER
========================================================== -->

<footer>


    <div class="container">


        <div class="footer-top">


            <!-- BRAND -->

            <div class="footer-brand">


                <a href="#home"
                   class="brand">


                    <!-- ACTUAL GITHUB LOGO -->

                    <div class="brand-logo">

                        <img src="logo.jpeg"
                             alt="M|&|K Accounts Logo">

                    </div>


                    <div class="brand-text">


                        <div class="brand-name">
                            M|&|K ACCOUNTS
                        </div>


                        <div class="brand-sub">
                            REMOTE OPERATIONS
                        </div>


                    </div>


                </a>


                <p>

                    Professional GST, Income Tax,
                    TDS, bookkeeping and accounting
                    support. Currently serving clients
                    across Haryana and looking forward
                    to working with clients PAN India.

                </p>


            </div>



            <!-- SERVICES -->

            <div>


                <div class="footer-title">
                    Services
                </div>


                <div class="footer-links">


                    <a href="#services">
                        GST Returns
                    </a>


                    <a href="#services">
                        Income Tax
                    </a>


                    <a href="#services">
                        TDS Compliance
                    </a>


                    <a href="#services">
                        Part-Time Accounting
                    </a>


                    <a href="#services">
                        Audit & Assurance
                    </a>


                    <a href="#services">
                        Business Registration
                    </a>


                </div>


            </div>



            <!-- CONTACT -->

            <div>


                <div class="footer-title">
                    Contact
                </div>


                <div class="footer-links">


                    <a href="tel:+919817571705">
                        +91 98175 71705
                    </a>


                    <a href="tel:+919992075501">
                        +91 99920 75501
                    </a>


                    <a href="mailto:Info@mkaccounts.in">
                        Info@mkaccounts.in
                    </a>


                    <a href="mailto:ta.solution.hisar@gmail.com">
                        ta.solution.hisar@gmail.com
                    </a>


                    <a href="https://maps.app.goo.gl/D4xPndjc2F5G5AT7A"
                       target="_blank"
                       rel="noopener">

                        Google Maps

                    </a>


                </div>


            </div>


        </div>



        <div class="footer-bottom">


            <span>

                ©
                <span id="year"></span>
                M|&|K Accounts.
                All Rights Reserved.

            </span>


            <span>

                Haryana · Remote Operations ·
                PAN India Expansion

            </span>


        </div>


    </div>


</footer>



<!-- =========================================================
     FLOATING WHATSAPP
========================================================== -->

<a href="https://wa.me/919817571705"
   class="whatsapp-float"
   target="_blank"
   rel="noopener"
   aria-label="WhatsApp">

    <i class="fa-brands fa-whatsapp"></i>

</a>



<!-- =========================================================
     BACK TO TOP
========================================================== -->

<button class="back-top"
        id="backTop"
        aria-label="Back to top">

    <i class="fa-solid fa-arrow-up"></i>

</button>



<!-- =========================================================
     JAVASCRIPT
========================================================== -->

<script>


/* =========================================================
   MOBILE MENU
========================================================== */

const menuBtn =
    document.getElementById("menuBtn");

const navLinks =
    document.getElementById("navLinks");


menuBtn.addEventListener(
    "click",
    () => {

        navLinks.classList.toggle(
            "active"
        );


        const icon =
            menuBtn.querySelector("i");


        if (
            navLinks.classList.contains(
                "active"
            )
        ) {

            icon.classList.remove(
                "fa-bars"
            );

            icon.classList.add(
                "fa-xmark"
            );

        } else {

            icon.classList.remove(
                "fa-xmark"
            );

            icon.classList.add(
                "fa-bars"
            );

        }

    }
);



/* =========================================================
   CLOSE MOBILE MENU
========================================================== */

document
    .querySelectorAll(
        ".nav-links a"
    )
    .forEach(link => {

        link.addEventListener(
            "click",
            () => {

                navLinks.classList.remove(
                    "active"
                );


                const icon =
                    menuBtn.querySelector(
                        "i"
                    );


                icon.classList.remove(
                    "fa-xmark"
                );

                icon.classList.add(
                    "fa-bars"
                );

            }
        );

    });



/* =========================================================
   HEADER SCROLL
========================================================== */

const header =
    document.getElementById(
        "header"
    );


window.addEventListener(
    "scroll",
    () => {

        if (
            window.scrollY > 50
        ) {

            header.classList.add(
                "scrolled"
            );

        } else {

            header.classList.remove(
                "scrolled"
            );

        }

    }
);



/* =========================================================
   BACK TO TOP
========================================================== */

const backTop =
    document.getElementById(
        "backTop"
    );


window.addEventListener(
    "scroll",
    () => {

        if (
            window.scrollY > 500
        ) {

            backTop.classList.add(
                "show"
            );

        } else {

            backTop.classList.remove(
                "show"
            );

        }

    }
);


backTop.addEventListener(
    "click",
    () => {

        window.scrollTo({

            top: 0,

            behavior: "smooth"

        });

    }
);



/* =========================================================
   FAQ ACCORDION
========================================================== */

const faqItems =
    document.querySelectorAll(
        ".faq-item"
    );


faqItems.forEach(
    item => {

        const question =
            item.querySelector(
                ".faq-question"
            );

        const answer =
            item.querySelector(
                ".faq-answer"
            );


        question.addEventListener(
            "click",
            () => {

                const isActive =
                    item.classList.contains(
                        "active"
                    );


                faqItems.forEach(
                    other => {

                        other.classList.remove(
                            "active"
                        );

                        other.querySelector(
                            ".faq-answer"
                        ).style.maxHeight =
                            null;

                    }
                );


                if (!isActive) {

                    item.classList.add(
                        "active"
                    );

                    answer.style.maxHeight =
                        answer.scrollHeight +
                        "px";

                }

            }
        );

    }
);



/* =========================================================
   SCROLL REVEAL
========================================================== */

const revealElements =
    document.querySelectorAll(
        ".reveal"
    );


const observer =
    new IntersectionObserver(

        (entries, observer) => {

            entries.forEach(
                entry => {

                    if (
                        entry.isIntersecting
                    ) {

                        entry.target.classList.add(
                            "visible"
                        );

                        observer.unobserve(
                            entry.target
                        );

                    }

                }
            );

        },

        {
            threshold: 0.12
        }

    );


revealElements.forEach(
    element => {

        observer.observe(
            element
        );

    }
);



/* =========================================================
   CURRENT YEAR
========================================================== */

document.getElementById(
    "year"
).textContent =
    new Date().getFullYear();



/* =========================================================
   SMOOTH ANCHOR SCROLL
========================================================== */

document
    .querySelectorAll(
        'a[href^="#"]'
    )
    .forEach(anchor => {

        anchor.addEventListener(
            "click",
            function(e) {

                const target =
                    document.querySelector(
                        this.getAttribute(
                            "href"
                        )
                    );


                if (!target)
                    return;


                e.preventDefault();


                const headerHeight =
                    document.querySelector(
                        "header"
                    ).offsetHeight;


                const position =
                    target.getBoundingClientRect()
                        .top +
                    window.pageYOffset -
                    headerHeight;


                window.scrollTo({

                    top: position,

                    behavior: "smooth"

                });

            }
        );

    });


</script>


</body>

</html>
