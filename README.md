<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NP Properties | Flats for Rent & Sale in Wakad & Hinjawadi Pune</title>
    <!-- SEO Meta Tags -->
    <meta name="description" content="Find the perfect flats for rent and sale in Wakad and Hinjawadi, Pune. NP Properties offers reliable 1, 2, 3, & 4 BHK residential properties, fully furnished apartments.">
    <meta name="keywords" content="Property for Rent in Pune, Flats for Sale in Pune, 2 BHK for Rent Pune, 3 BHK for Rent Pune, Real Estate Pune, Flats in Wakad, Flats in Hinjawadi, NP Properties">
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cloudflare.com">
    <style>
        :root {
            --primary: #f26522; /* Orange from logo */
            --dark: #231f20;    /* Dark gray/black from logo */
            --light: #f9f9f9;
            --white: #ffffff;
            --gray: #666666;
            --whatsapp: #25D366;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            scroll-behavior: smooth;
        }

        body {
            background-color: var(--light);
            color: var(--dark);
        }

        /* Navbar */
        header {
            background: var(--white);
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
            padding: 15px 20px;
        }

        .logo-text {
            font-size: 24px;
            font-weight: 700;
            color: var(--dark);
        }

        .logo-text span {
            color: var(--primary);
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 20px;
        }

        nav a {
            text-decoration: none;
            color: var(--dark);
            font-weight: 600;
            transition: 0.3s;
        }

        nav a:hover {
            color: var(--primary);
        }

        .mobile-menu-btn {
            display: none;
            font-size: 24px;
            cursor: pointer;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(rgba(35, 31, 32, 0.8), rgba(35, 31, 32, 0.8)), url('https://unsplash.com') no-repeat center center/cover;
            height: 70vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: var(--white);
            padding: 0 20px;
        }

        .hero h1 {
            font-size: 48px;
            margin-bottom: 15px;
            letter-spacing: 1px;
        }

        .hero p {
            font-size: 20px;
            margin-bottom: 30px;
            font-weight: 300;
        }

        .hero-btns {
            display: flex;
            gap: 15px;
        }

        .btn {
            padding: 12px 30px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: 600;
            transition: 0.3s;
            cursor: pointer;
            border: none;
        }

        .btn-primary {
            background-color: var(--primary);
            color: var(--white);
        }

        .btn-primary:hover {
            background-color: #d44d13;
        }

        .btn-outline {
            border: 2px solid var(--white);
            color: var(--white);
            background: transparent;
        }

        .btn-outline:hover {
            background-color: var(--white);
            color: var(--dark);
        }

        /* Sections General */
        section {
            padding: 80px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .section-title {
            text-align: center;
            font-size: 32px;
            margin-bottom: 40px;
            position: relative;
            padding-bottom: 10px;
        }

        .section-title::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 60px;
            height: 3px;
            background-color: var(--primary);
        }

        /* Filter Tab Buttons */
        .tab-container {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-bottom: 30px;
        }

        .tab-btn {
            padding: 10px 25px;
            background: var(--white);
            border: 1px solid #ddd;
            border-radius: 25px;
            cursor: pointer;
            font-weight: 600;
            transition: 0.3s;
        }

        .tab-btn.active, .tab-btn:hover {
            background: var(--primary);
            color: var(--white);
            border-color: var(--primary);
        }

        /* Property Grid */
        .property-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .property-card {
            background: var(--white);
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            transition: 0.3s;
        }

        .property-card:hover {
            transform: translateY(-5px);
        }

        .property-img {
            position: relative;
            height: 220px;
        }

        .property-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .badge {
            position: absolute;
            top: 15px;
            left: 15px;
            background: var(--primary);
            color: var(--white);
            padding: 5px 12px;
            border-radius: 4px;
            font-size: 12px;
            font-weight: 600;
        }

        .property-content {
            padding: 20px;
        }

        .price {
            font-size: 22px;
            font-weight: 700;
            color: var(--primary);
            margin-bottom: 10px;
        }

        .prop-title {
            font-size: 18px;
            margin-bottom: 10px;
        }

        .location {
            color: var(--gray);
            font-size: 14px;
            margin-bottom: 15px;
        }

        .features {
            display: flex;
            justify-content: space-between;
            border-top: 1px solid #eee;
            border-bottom: 1px solid #eee;
            padding: 10px 0;
            margin-bottom: 15px;
            font-size: 14px;
            color: var(--gray);
        }

        .btn-whatsapp {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 8px;
            background-color: var(--whatsapp);
            color: var(--white);
            width: 100%;
            text-align: center;
            padding: 10px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: 600;
        }

        /* Services */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .service-box {
            background: var(--white);
            padding: 30px;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
        }

        .service-box i {
            font-size: 40px;
            color: var(--primary);
            margin-bottom: 20px;
        }

        .service-box h3 {
            margin-bottom: 10px;
        }

        /* About */
        .about-container {
            display: flex;
            align-items: center;
            gap: 50px;
        }

        .about-text {
            flex: 1;
        }

        .about-text p {
            margin-bottom: 15px;
            line-height: 1.6;
            color: var(--gray);
        }

        .about-img {
            flex: 1;
        }

        .about-img img {
            width: 100%;
            border-radius: 8px;
        }

        /* Contact Section */
        .contact-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
        }

        .contact-info h3 {
            margin-bottom: 20px;
        }

        .contact-buttons {
            display: flex;
            flex-direction: column;
            gap: 15px;
            margin-top: 25px;
        }

        .c-btn {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            padding: 12px;
            border-radius: 5px;
            text-decoration: none;
            color: var(--white);
            font-weight: 600;
        }

        .c-phone { background-color: #007bb5; }
        .c-insta { background: linear-gradient(45deg, #f09433 0%, #e6683c 25%, #dc2743 50%, #cc2366 75%, #bc1888 100%); }

        .contact-form {
            background: var(--white);
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
        }

        .form-group {
            margin-bottom: 15px;
        }

        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: 600;
        }

        .form-group input, .form-group textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }

