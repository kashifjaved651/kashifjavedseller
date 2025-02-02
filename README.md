<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KJ Amazon Seller | Kashif Javed - Professional Seller</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* Reset and Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        :root {
            --primary-color: #ff9900;
            --secondary-color: #232f3e;
            --accent-color: #146eb4;
            --text-dark: #0f1111;
            --text-light: #ffffff;
        }

        body {
            background-color: #fafafa;
            line-height: 1.6;
        }

        /* Header Styles */
        .main-header {
            background: var(--secondary-color);
            padding: 1rem 2rem;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .nav-container {
            max-width: 1400px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .brand-logo {
            display: flex;
            align-items: center;
            gap: 0.8rem;
            text-decoration: none;
        }

        .kj-logo {
            background: linear-gradient(135deg, var(--primary-color), #ffac31);
            color: var(--text-light);
            padding: 0.8rem 1.2rem;
            border-radius: 50%;
            font-size: 2rem;
            font-weight: 700;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
        }

        .brand-name {
            color: var(--text-light);
            font-size: 1.5rem;
            font-weight: 600;
        }

        .main-nav {
            display: flex;
            gap: 2rem;
        }

        .nav-link {
            color: var(--text-light);
            text-decoration: none;
            padding: 0.5rem 1rem;
            border-radius: 4px;
            transition: all 0.3s ease;
        }

        .nav-link:hover {
            background: var(--primary-color);
        }

        /* Hero Section */
        .hero-section {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)),
                        url('https://images.unsplash.com/photo-1504384308090-c894fdcc538d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80');
            background-size: cover;
            background-position: center;
            color: var(--text-light);
            padding: 6rem 2rem;
            text-align: center;
        }

        .hero-content {
            max-width: 800px;
            margin: 0 auto;
        }

        .hero-title {
            font-size: 3rem;
            margin-bottom: 1.5rem;
        }

        /* Products Section */
        .products-section {
            padding: 4rem 2rem;
            max-width: 1400px;
            margin: 0 auto;
        }

        .section-title {
            text-align: center;
            margin-bottom: 3rem;
            color: var(--secondary-color);
        }

        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
        }

        .product-card {
            background: var(--text-light);
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .product-card:hover {
            transform: translateY(-5px);
        }

        .product-image {
            width: 100%;
            height: 250px;
            object-fit: contain;
            padding: 1rem;
            background: #fff;
        }

        .product-info {
            padding: 1.5rem;
            border-top: 1px solid #eee;
        }

        .product-title {
            color: var(--text-dark);
            margin-bottom: 0.5rem;
            font-size: 1.1rem;
        }

        .product-price {
            color: var(--primary-color);
            font-size: 1.2rem;
            font-weight: 700;
        }

        /* Contact Section */
        .contact-bar {
            background: var(--secondary-color);
            color: var(--text-light);
            padding: 2rem;
            text-align: center;
        }

        .contact-info {
            display: flex;
            justify-content: center;
            gap: 3rem;
            margin-top: 1rem;
        }

        /* Footer Styles */
        .main-footer {
            background: var(--secondary-color);
            color: var(--text-light);
            padding: 4rem 2rem;
        }

        .footer-content {
            max-width: 1400px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }

        .footer-section h4 {
            margin-bottom: 1.5rem;
            color: var(--primary-color);
        }

        .social-links {
            display: flex;
            gap: 1rem;
            margin-top: 1rem;
        }

        .social-link {
            color: var(--text-light);
            font-size: 1.5rem;
            transition: color 0.3s ease;
        }

        .social-link:hover {
            color: var(--primary-color);
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .main-nav {
                display: none;
            }

            .hero-title {
                font-size: 2rem;
            }

            .products-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header class="main-header">
        <nav class="nav-container">
            <a href="#" class="brand-logo">
                <div class="kj-logo">KJ</div>
                <span class="brand-name">Kashif Javed</span>
            </a>
            <nav class="main-nav">
                <a href="#home" class="nav-link">Home</a>
                <a href="#products" class="nav-link">Products</a>
                <a href="#about" class="nav-link">About</a>
                <a href="#contact" class="nav-link">Contact</a>
            </nav>
        </nav>
    </header>

    <section class="hero-section" id="home">
        <div class="hero-content">
            <h1 class="hero-title">Professional Amazon Seller Services</h1>
            <p class="hero-subtitle">Quality Products | Fast Delivery | Best Prices</p>
        </div>
    </section>

    <section class="products-section" id="products">
        <h2 class="section-title">Featured Products</h2>
        <div class="products-grid">
            <!-- Product 1 -->
            <div class="product-card">
                <img src="https://via.placeholder.com/300x300.png?text=Product+1" alt="Product 1" class="product-image">
                <div class="product-info">
                    <h3 class="product-title">Wireless Bluetooth Headphones</h3>
                    <p class="product-price">$49.99</p>
                    <button class="buy-button">Add to Cart</button>
                </div>
            </div>

            <!-- Add more product cards -->
            <!-- Repeat product card structure for other products -->
        </div>
    </section>

    <section class="contact-bar" id="contact">
        <h3>Contact Information</h3>
        <div class="contact-info">
            <p><i class="fas fa-phone"></i> 923039644805</p>
            <p><i class="fas fa-map-marker-alt"></i> Jaranwala 651/2, Pakistan</p>
        </div>
    </section>

    <footer class="main-footer">
        <div class="footer-content">
            <div class="footer-section">
                <h4>About Us</h4>
                <p>Professional Amazon seller with 5+ years of experience in e-commerce.</p>
            </div>
            <div class="footer-section">
                <h4>Quick Links</h4>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#products">Products</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </div>
            <div class="footer-section">
                <h4>Connect With Us</h4>
                <div class="social-links">
                    <a href="#" class="social-link"><i class="fab fa-facebook"></i></a>
                    <a href="#" class="social-link"><i class="fab fa-twitter"></i></a>
                    <a href="#" class="social-link"><i class="fab fa-instagram"></i></a>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Sticky Header
        window.addEventListener('scroll', function() {
            const header = document.querySelector('.main-header');
            if (window.scrollY > 100) {
                header.style.backgroundColor = 'rgba(35, 47, 62, 0.95)';
            } else {
                header.style.backgroundColor = 'var(--secondary-color)';
            }
        });

        // Smooth Scroll
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
