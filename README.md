<!DOCTYPE html>
<html lang="en">
<head><link rel="stylesheet" href="styles.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="MBH Express - Professional Trucking and Freight Services">
    <meta property="og:title" content="MBH Express - Reliable Trucking Solutions">
    <meta property="og:description" content="24/7 Transportation Services Across North America">
    <title>MBH Express - Reliable Trucking Solutions</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Favicon -->
    <link rel="icon" type="image/png" href="HBM Express PNG.png">
</head>
<body>
    <header aria-label="Main navigation">
        <nav class="container">
            <div class="logo">
                <img src="HBM Express PNG.png" alt="MBH Express Logo" class="logo-img">
            </div>
            <button class="menu-toggle" aria-expanded="false" aria-label="Mobile menu">
                <span class="hamburger"></span>
            </button>
            <div class="nav-links">
                <a href="#home" class="active">Home</a>
                <a href="#services">Services</a>
                <a href="#join-team">Careers</a>
                <a href="#contact">Contact</a>
            </div>
        </nav>
    </header>

    <!-- Rest of the HTML remains the same -->

    <script>
        // Add logo hover effect
        document.querySelector('.logo-img').addEventListener('mouseover', function() {
            this.style.transform = 'scale(1.05)';
        });
        document.querySelector('.logo-img').addEventListener('mouseout', function() {
            this.style.transform = 'scale(1)';
        });
    </script>
</body>
</html>
