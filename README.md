<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HL Mechanical - Home</title>
    <link rel="stylesheet" href="css/styles.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #001f3f;
            color: white;
        }

        .navbar {
            background-color: #001233 !important;
        }

        .hero {
            background: url('images/construction-site.jpg') no-repeat center center/cover;
            padding: 100px 0;
            text-align: center;
            color: white;
        }

        .hero img {
            height: 100px;
            width: auto;
        }

        .owner-info {
            font-size: 18px;
            margin-top: 10px;
        }

        .services {
            background: white;
            color: black;
            padding: 20px;
            border-radius: 5px;
        }

        .quote-form {
            background: white;
            color: black;
            padding: 20px;
            border-radius: 5px;
        }

        .btn-primary {
            background-color: #001233;
            border-color: #001233;
        }
    </style>
</head>
<body>

    <!-- Navigation Bar -->
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

    <!-- Hero Section with Logo -->
    <header class="hero">
        <div class="container text-center">
            <img src="images/logo-updated.png" alt="HL Mechanical Logo">
            <p class="owner-info">Harry L. Clark - Owner</p>
            <p>Residential, Commercial & Industrial Services</p>
            <p><strong>Call: 520-909-4674 | Email: harryc@q.com</strong></p>
            <p><strong>Location: Tucson, AZ</strong></p>
        </div>
    </header>

    <!-- Services Section -->
    <section class="container services mt-5">
        <h2 class="text-center">Our Services</h2>
        <ul>
            <li>Custom Homes, Garages, Shops, Office Buildings</li>
            <li>Remodels (Baths & Kitchens)</li>
            <li>Metal Roofing & Shingle Roofing</li>
            <li>AC Sales & Services (Trane, Rheem, York)</li>
        </ul>
    </section>

    <!-- Quote Request Form -->
    <section class="quote-form">
        <div class="container">
            <h2 class="text-center">Request a Quote</h2>
            <form id="quoteForm">
                <div class="mb-3">
                    <label>Name:</label>
                    <input type="text" class="form-control" required>
                </div>
                <div class="mb-3">
                    <label>Email:</label>
                    <input type="email" class="form-control" required>
                </div>
                <div class="mb-3">
                    <label>Service Needed:</label>
                    <textarea class="form-control" rows="3" required></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Get Quote</button>
            </form>
        </div>
    </section>

    <script src="js/script.js"></script>
</body>
</html>
