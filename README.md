# Demo
Biker Website HTML code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Classic Motorbikes - Showroom</title>
    <link rel="stylesheet" href="styles. css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar">
        <div class="nav-container">
            <div class="logo">🏍️ Classic Motorbikes</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#bikes">Browse Bikes</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-content">
            <h1>Classic Motorbike Showroom</h1>
            <p>Discover Timeless Elegance & Performance</p>
            <a href="#bikes" class="cta-button">Explore Collection</a>
        </div>
    </section>

    <!-- Bikes Gallery -->
    <section class="bikes-section" id="bikes">
        <div class="container">
            <h2>Our Collection</h2>
            <div class="bikes-grid" id="bikesGrid">
                <!-- Bikes will be populated by JavaScript -->
            </div>
        </div>
    </section>

    <!-- Bike Details Modal -->
    <div id="bikeModal" class="modal">
        <div class="modal-content">
            <span class="close">&times;</span>
            <div class="modal-body">
                <div class="modal-image">
                    <img id="modalImage" src="" alt="Bike">
                </div>
                <div class="modal-details">
                    <h2 id="modalName"></h2>
                    <p id="modalDescription"></p>
                    
                    <div class="specs">
                        <div class="spec-item">
                            <span class="spec-label">Engine:</span>
                            <span id="modalEngine"></span>
                        </div>
                        <div class="spec-item">
                            <span class="spec-label">Power:</span>
                            <span id="modalPower"></span>
                        </div>
                        <div class="spec-item">
                            <span class="spec-label">Top Speed:</span>
                            <span id="modalSpeed"></span>
                        </div>
                    </div>

                    <div class="pricing">
                        <h3>Pricing Information</h3>
                        <div class="price-breakdown">
                            <div class="price-item">
                                <span class="price-label">Ex-Showroom Price:</span>
                                <span class="price-value" id="modalExShowroom"></span>
                            </div>
                            <div class="price-item">
                                <span class="price-label">Road Tax (1 Year):</span>
                                <span class="price-value" id="modalRoadTax"></span>
                            </div>
                            <div class="price-item">
                                <span class="price-label">Registration Fee:</span>
                                <span class="price-value" id="modalRegFee"></span>
                            </div>
                            <div class="price-item">
                                <span class="price-label">Insurance (Annual):</span>
                                <span class="price-value" id="modalInsurance"></span>
                            </div>
                            <div class="price-item total">
                                <span class="price-label">On-Road Price:</span>
                                <span class="price-value" id="modalOnRoad"></span>
                            </div>
                        </div>
                    </div>

                    <button class="inquiry-btn">Request Information</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <p>&copy; 2025 Classic Motorbikes Showroom. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
