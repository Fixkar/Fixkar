<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FixKar | Fast Mechanic Help in Pakistan</title>
    <meta name="description" content="Car broken down? Find the nearest mechanic in Pakistan within minutes. FixKar connects drivers with verified mechanics instantly.">
    
    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;800&display=swap" rel="stylesheet">
    
    <!-- Styles -->
    <link rel="stylesheet" href="style.css">
    
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>

    <!-- Header -->
    <nav class="navbar">
        <div class="container">
            <a href="#" class="logo">FIX<span>KAR</span></a>
            <div class="nav-links">
                <a href="#driver-form" class="btn-secondary">Find Mechanic</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
        <div class="container">
            <span class="badge">Reliable Help in Pakistan</span>
            <h1>Car Problem? Get a Mechanic Near You <span class="text-yellow">in Minutes.</span></h1>
            <p>Stuck on the road? FixKar connects you with verified local mechanics instantly. Fast, reliable, and affordable.</p>
            <div class="hero-btns">
                <a href="#driver-form" class="btn-primary">Find Mechanic Now</a>
                <a href="#mechanic-reg" class="btn-outline">Join as Mechanic</a>
            </div>
        </div>
    </section>

    <!-- Problem/Stats Section -->
    <section class="stats">
        <div class="container grid-3">
            <div class="stat-card">
                <i class="fas fa-clock"></i>
                <h3>15 Mins</h3>
                <p>Average response time</p>
            </div>
            <div class="stat-card">
                <i class="fas fa-tools"></i>
                <h3>500+</h3>
                <p>Verified Mechanics</p>
            </div>
            <div class="stat-card">
                <i class="fas fa-check-circle"></i>
                <h3>24/7</h3>
                <p>Emergency Support</p>
            </div>
        </div>
    </section>

    <!-- Driver Form Section -->
    <section id="driver-form" class="section bg-light">
        <div class="container">
            <div class="form-container">
                <div class="form-header">
                    <h2>Get Emergency Help</h2>
                    <p>Fill the form and a mechanic will call you back immediately.</p>
                </div>
                <!-- Replace 'your-id' with Formspree ID -->
                <form id="requestForm" action="https://formspree.io/f/your-id" method="POST">
                    <div class="form-group">
                        <label>Your Name</label>
                        <input type="text" name="name" placeholder="Enter full name" required>
                    </div>
                    <div class="form-group">
                        <label>Phone Number</label>
                        <input type="tel" name="phone" placeholder="03xx xxxxxxx" required>
                    </div>
                    <div class="form-group">
                        <label>Your Location</label>
                        <input type="text" name="location" placeholder="Current city or area" required>
                    </div>
                    <div class="form-group">
                        <label>Car Issue</label>
                        <textarea name="issue" placeholder="Briefly describe the problem (e.g. Engine heat, Tyre puncture)" required></textarea>
                    </div>
                    <button type="submit" class="btn-primary btn-block">Send Request</button>
                    <p id="formStatus" class="status-msg"></p>
                </form>
            </div>
        </div>
    </section>

    <!-- How it Works -->
    <section class="section">
        <div class="container">
            <h2 class="text-center">How It Works</h2>
            <div class="grid-3 mt-4">
                <div class="step">
                    <div class="step-num">1</div>
                    <h4>Submit Request</h4>
                    <p>Tell us your car issue and location via our simple form.</p>
                </div>
                <div class="step">
                    <div class="step-num">2</div>
                    <h4>Get Matched</h4>
                    <p>Nearby verified mechanics receive your request instantly.</p>
                </div>
                <div class="step">
                    <div class="step-num">3</div>
                    <h4>Fixed!</h4>
                    <p>Mechanic arrives, fixes your car, and you're back on the road.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Mechanic Registration -->
    <section id="mechanic-reg" class="section bg-dark text-white">
        <div class="container">
            <div class="grid-2">
                <div>
                    <h2>Are you a Mechanic?</h2>
                    <p>Register with FixKar to get more customers and grow your business in Pakistan.</p>
                    <ul class="benefit-list">
                        <li><i class="fas fa-check text-yellow"></i> More daily leads</li>
                        <li><i class="fas fa-check text-yellow"></i> Be your own boss</li>
                        <li><i class="fas fa-check text-yellow"></i> Zero registration fee</li>
                    </ul>
                </div>
                <div class="form-container dark-form">
                    <form id="mechanicForm" action="https://formspree.io/f/your-id" method="POST">
                        <div class="form-group">
                            <label>Shop/Mechanic Name</label>
                            <input type="text" name="mech_name" required>
                        </div>
                        <div class="form-group">
                            <label>Phone Number</label>
                            <input type="tel" name="mech_phone" required>
                        </div>
                        <div class="form-group">
                            <label>Specialization</label>
                            <input type="text" name="specialty" placeholder="e.g. Engine, Electrician, AC">
                        </div>
                        <button type="submit" class="btn-yellow btn-block">Join as Partner</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="container text-center">
            <p>&copy; 2024 FixKar Pakistan. All Rights Reserved.</p>
        </div>
    </footer>

    <!-- Floating WhatsApp Button -->
    <a href="https://wa.me/923001234567?text=I%20need%20car%20repair%20help" class="whatsapp-float" target="_blank">
        <i class="fab fa-whatsapp"></i>
        <span>Chat with us</span>
    </a>

    <script src="script.js"></script>
</body>
</html>
