<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HL Mechanical - Home</title>
    <link rel="stylesheet" href="css/styles.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #001f3f;
            color: white;
        }

        .navbar {
            background-color: #001233 !important;
            padding: 15px 0;
        }

        .navbar-brand {
            font-size: 24px;
            font-weight: bold;
        }

        .navbar-nav .nav-link {
            font-size: 18px;
            padding: 10px 15px;
            transition: 0.3s;
        }

        .navbar-nav .nav-link:hover {
            background: rgba(255, 255, 255, 0.2);
            border-radius: 5px;
        }

        .hero {
            position: relative;
            images/logo-updated.png
            background: url('images/construction-site.jpg') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            align-items: center;
            text-align: center;
            color: white;
        }

        .hero::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.6);
        }

        .hero-content {
            position: relative;
            z-index: 1;
            animation: fadeIn 1.5s ease-in-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .btn-primary {
            background-color: #004080;
            border-color: #004080;
            font-size: 18px;
            padding: 12px 20px;
            transition: 0.3s;
            border-radius: 5px;
        }

        .btn-primary:hover {
            background-color: #003060;
            transform: scale(1.05);
        }

        .footer {
            background: #001233;
            color: white;
            padding: 20px;
            margin-top: 20px;
            text-align: center;
        }

        .social-icons a {
            color: white;
            font-size: 20px;
            margin: 0 10px;
            transition: 0.3s;
        }

        .social-icons a:hover {
            color: #004080;
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark">
        <div class="container">
            <a class="navbar-brand" href="index.html">HL Mechanical</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="about.html">About Us</a></li>
                    <li class="nav-item"><a class="nav-link" href="services.html">Services</a></li>
                    <li class="nav-item"><a class="nav-link" href="portfolio.html">Portfolio</a></li>
                    <li class="nav-item"><a class="nav-link" href="contact.html">Contact</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <header class="hero">
        <div class="container text-center hero-content">
            <img src="images/logo-updated.png" alt="HL Mechanical Logo">
            <h1 class="owner-info">Harry L. Clark - Owner</h1>
            <p>Residential, Commercial & Industrial Services</p>
            <p><strong>Call: 520-909-4674 | Email: harryc@q.com</strong></p>
            <p><strong>Location: Tucson, AZ</strong></p>
            <a href="#quote" class="btn btn-primary mt-3">Request a Quote</a>
        </div>
    </header>

    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 HL Mechanical | All Rights Reserved</p>
            <div class="social-icons">
                <a href="#"><i class="fab fa-facebook"></i></a>
                <a href="#"><i class="fab fa-linkedin"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
            </div>
        </div>
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
