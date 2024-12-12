<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smartwatch Landing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="header">
        <div class="container">
            <h1>SmartTech Watch</h1>
            <p>The perfect combination of style and technology.</p>
            <a href="#features" class="btn-primary">Explore Features</a>
        </div>
    </header>

    <section id="features" class="features">
        <div class="container">
            <h2>Features</h2>
            <div class="features-grid">
                <div class="feature">
                    <h3>Heart Rate Monitor</h3>
                    <p>Keep track of your heart rate 24/7.</p>
                </div>
                <div class="feature">
                    <h3>Customizable Faces</h3>
                    <p>Choose a look that suits your style.</p>
                </div>
                <div class="feature">
                    <h3>Water Resistant</h3>
                    <p>Perfect for swimming and outdoor activities.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="pricing">
        <div class="container">
            <h2>Pricing</h2>
            <p>Get your SmartTech Watch for only $199.</p>
            <a href="#buy" class="btn-primary">Buy Now</a>
        </div>
    </section>

    <footer class="footer">
        <div class="container">
            <p>© 2024 SmartTech. All Rights Reserved.</p>
        </div>
    </footer>
</body>
</html>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    color: #333;
    text-align: center;
}

.container {
    max-width: 1200px;
    margin: auto;
    padding: 1em;
}

.header, .pricing {
    padding: 2em 0;
    color: #981492;
}

.header {
    background: #1e90ff;
}

.btn-primary {
    background: #ff5722;
    color: #fff;
    padding: 0.8em 1.5em;
    text-decoration: none;
    border-radius: 5px;
    display: inline-block;
}

.btn-primary:hover {
    background: #e64a19;
}

.features {
    background: #f9f9f9;
    padding: 2em 0;
}

.features-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1.5em;
}

.feature {
    background: #fff;
    padding: 1.5em;
    border-radius: 8px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.footer {
    background: #333;
    color: #fff;
    padding: 1em 0;
}
