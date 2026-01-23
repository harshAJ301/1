<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy 18th Birthday! | A New Chapter Begins</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        :root {
            --primary: #ff6b8b;
            --secondary: #6a5af9;
            --accent: #ffd166;
            --light: #fff5f7;
            --dark: #2d3047;
            --transition: all 0.3s ease;
        }
        
        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
            color: var(--dark);
            background-color: var(--light);
            overflow-x: hidden;
        }
        
        h1, h2, h3 {
            font-weight: 600;
            margin-bottom: 1rem;
        }
        
        h1 {
            font-size: 3.5rem;
            font-family: 'Dancing Script', cursive;
            color: var(--primary);
        }
        
        h2 {
            font-size: 2.5rem;
            color: var(--secondary);
            position: relative;
            display: inline-block;
        }
        
        h2:after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 0;
            width: 60%;
            height: 3px;
            background: linear-gradient(to right, var(--primary), var(--secondary));
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        section {
            padding: 80px 0;
        }
        
        /* Hero Section */
        #hero {
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            background: linear-gradient(135deg, rgba(255,107,139,0.1) 0%, rgba(106,90,249,0.1) 100%);
            position: relative;
            overflow: hidden;
        }
        
        .hero-content {
            z-index: 2;
            position: relative;
        }
        
        .hero-content h1 {
            font-size: 4rem;
            margin-bottom: 0.5rem;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
        }
        
        .hero-content p {
            font-size: 1.2rem;
            max-width: 600px;
            margin: 0 auto 2rem;
            color: #555;
        }
        
        .birthday-girl {
            font-weight: 600;
            color: var(--secondary);
            font-size: 1.5rem;
        }
        
        .number-18 {
            font-size: 10rem;
            font-weight: 800;
            color: var(--primary);
            text-shadow: 3px 3px 0 var(--accent);
            margin: 1rem 0;
            line-height: 1;
            animation: float 3s ease-in-out infinite;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }
        
        .heart {
            color: var(--primary);
            animation: heartbeat 1.5s infinite;
        }
        
        @keyframes heartbeat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.1); }
        }
        
        /* Message Section */
        #message {
            background-color: white;
        }
        
        .message-content {
            display: flex;
            flex-direction: column;
            align-items: center;
            max-width: 800px;
            margin: 0 auto;
        }
        
        .message-text {
            background-color: #f9f9ff;
            padding: 2.5rem;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            margin-bottom: 2rem;
            border-left: 5px solid var(--accent);
            font-size: 1.1rem;
        }
        
        .message-text p {
            margin-bottom: 1.5rem;
        }
        
        /* Memories Section */
        #memories {
            background-color: #f9f7ff;
        }
        
        .memories-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .memory-card {
            background-color: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 10px 20px rgba(0,0,0,0.08);
            transition: var(--transition);
        }
        
        .memory-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0,0,0,0.12);
        }
        
        .memory-img {
            height: 200px;
            background-color: #ddd;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #888;
            font-size: 3rem;
        }
        
        .memory-content {
            padding: 1.5rem;
        }
        
        .memory-content h3 {
            color: var(--secondary);
        }
        
        /* Meaning Section */
        .meaning-container {
            display: flex;
            flex-wrap: wrap;
            gap: 40px;
            align-items: center;
            margin-top: 40px;
        }
        
        .meaning-text {
            flex: 1;
            min-width: 300px;
        }
        
        .meaning-visual {
            flex: 1;
            min-width: 300px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        .milestone-list {
            list-style-type: none;
            margin-top: 1.5rem;
        }
        
        .milestone-list li {
            padding: 0.8rem 0;
            border-bottom: 1px dashed #eee;
            position: relative;
            padding-left: 2rem;
        }
        
        .milestone-list li:before {
            content: '✓';
            position: absolute;
            left: 0;
            color: var(--primary);
            font-weight: bold;
        }
        
        .birthday-cake {
            width: 200px;
            height: 200px;
            background-color: var(--accent);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 2rem;
            position: relative;
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
        }
        
        .birthday-cake:before {
            content: '18';
            position: absolute;
            top: -20px;
            font-size: 4rem;
            font-weight: 800;
            color: var(--primary);
        }
        
        .cake {
            width: 120px;
            height: 80px;
            background-color: #ff9eb5;
            border-radius: 50% 50% 0 0;
            position: relative;
        }
        
        .cake:after {
            content: '';
            position: absolute;
            width: 140px;
            height: 20px;
            background-color: #ff9eb5;
            bottom: -10px;
            left: -10px;
            border-radius: 10px;
        }
        
        .candle {
            width: 10px;
            height: 30px;
            background-color: var(--secondary);
            position: absolute;
            top: -40px;
            left: 50%;
            transform: translateX(-50%);
            border-radius: 5px;
        }
        
        .candle:after {
            content: '';
            position: absolute;
            width: 20px;
            height: 20px;
            background-color: #ff9a3c;
            border-radius: 50%;
            top: -10px;
            left: 50%;
            transform: translateX(-50%);
            animation: flicker 0.8s infinite alternate;
        }
        
        @keyframes flicker {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.8; }
        }
        
        /* Wishes Section */
        #wishes {
            text-align: center;
            background: linear-gradient(135deg, rgba(255,107,139,0.1) 0%, rgba(106,90,249,0.1) 100%);
        }
        
        .wishes-container {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .wish-box {
            background-color: white;
            padding: 2.5rem;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            margin-top: 2rem;
            font-size: 1.2rem;
            font-style: italic;
            position: relative;
        }
        
        .wish-box:before, .wish-box:after {
            content: '"';
            font-size: 4rem;
            color: var(--primary);
            opacity: 0.3;
            position: absolute;
        }
        
        .wish-box:before {
            top: 10px;
            left: 20px;
        }
        
        .wish-box:after {
            bottom: -20px;
            right: 20px;
        }
        
        /* Footer */
        footer {
            background-color: var(--dark);
            color: white;
            padding: 3rem 0;
            text-align: center;
        }
        
        .footer-content {
            max-width: 600px;
            margin: 0 auto;
        }
        
        .signature {
            font-family: 'Dancing Script', cursive;
            font-size: 2rem;
            color: var(--accent);
            margin-top: 1rem;
        }
        
        /* Navigation */
        .nav-dots {
            position: fixed;
            right: 20px;
            top: 50%;
            transform: translateY(-50%);
            z-index: 100;
        }
        
        .dot {
            width: 12px;
            height: 12px;
            background-color: rgba(255,107,139,0.5);
            border-radius: 50%;
            margin: 15px 0;
            cursor: pointer;
            transition: var(--transition);
        }
        
        .dot.active {
            background-color: var(--primary);
            transform: scale(1.3);
        }
        
        /* Responsive */
        @media (max-width: 768px) {
            h1 { font-size: 2.8rem; }
            h2 { font-size: 2rem; }
            .number-18 { font-size: 7rem; }
            .hero-content h1 { font-size: 3rem; }
            section { padding: 60px 0; }
            .nav-dots { display: none; }
        }
        
        /* Button */
        .btn {
            display: inline-block;
            background: linear-gradient(to right, var(--primary), var(--secondary));
            color: white;
            padding: 12px 30px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 500;
            margin-top: 1rem;
            border: none;
            cursor: pointer;
            transition: var(--transition);
            box-shadow: 0 5px 15px rgba(255,107,139,0.3);
        }
        
        .btn:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(255,107,139,0.4);
        }
        
        /* Confetti */
        .confetti {
            position: absolute;
            width: 10px;
            height: 10px;
            background-color: var(--primary);
            opacity: 0.8;
            top: 0;
            z-index: 1;
        }
        
        .confetti:nth-child(2n) {
            background-color: var(--secondary);
        }
        
        .confetti:nth-child(3n) {
            background-color: var(--accent);
        }
    </style>
</head>
<body>
    <!-- Navigation Dots -->
    <div class="nav-dots">
        <div class="dot active" data-section="hero"></div>
        <div class="dot" data-section="message"></div>
        <div class="dot" data-section="memories"></div>
        <div class="dot" data-section="meaning"></div>
        <div class="dot" data-section="wishes"></div>
    </div>

    <!-- Hero Section -->
    <section id="hero">
        <div class="hero-content">
            <p class="birthday-girl">For my amazing friend</p>
            <div class="number-18">18</div>
            <h1>Happy Birthday! <span class="heart">❤️</span></h1>
            <p>A new chapter begins today. Wishing you all the happiness, love, and success as you step into adulthood.</p>
            <a href="#message" class="btn">Read My Message</a>
        </div>
    </section>

    <!-- Personal Message Section -->
    <section id="message">
        <div class="container">
            <h2>A Heartfelt Message</h2>
            <div class="message-content">
                <div class="message-text">
                    <p>My dearest friend,</p>
                    <p>Today marks a significant milestone in your life - your 18th birthday! It feels like just yesterday we were laughing over silly things in school, and now you're stepping into adulthood with such grace and strength.</p>
                    <p>I want you to know how incredibly proud I am of the person you've become. Your kindness, intelligence, and vibrant spirit light up every room you enter. As you embark on this new chapter, remember that you have all the tools within you to create the life you dream of.</p>
                    <p>Turning 18 is more than just a number - it's the beginning of endless possibilities, newfound independence, and the freedom to shape your own destiny. Embrace every moment, learn from every experience, and never stop being the wonderful person you are.</p>
                    <p>No matter where life takes us, I'll always be here cheering you on. Here's to you, to 18, and to the incredible journey ahead!</p>
                    <p>With all my love,</p>
                    <p>Your best friend</p>
                </div>
                <a href="#memories" class="btn">Our Memories <i class="fas fa-arrow-down"></i></a>
            </div>
        </div>
    </section>

    <!-- Memories Section -->
    <section id="memories">
        <div class="container">
            <h2>Shared Memories</h2>
            <p>Some moments I'll cherish forever</p>
            <div class="memories-container">
                <div class="memory-card">
                    <div class="memory-img" style="background-color: #ffeff3;">
                        <i class="fas fa-laugh-beam" style="color: #ff6b8b;"></i>
                    </div>
                    <div class="memory-content">
                        <h3>Endless Laughter</h3>
                        <p>Remember those days when we couldn't stop laughing at the silliest things? Your laughter is contagious and has brightened so many of my days.</p>
                    </div>
                </div>
                
                <div class="memory-card">
                    <div class="memory-img" style="background-color: #f0f0ff;">
                        <i class="fas fa-heart" style="color: #6a5af9;"></i>
                    </div>
                    <div class="memory-content">
                        <h3>Support System</h3>
                        <p>Through ups and downs, we've always been there for each other. Your support means more to me than words can express.</p>
                    </div>
                </div>
                
                <div class="memory-card">
                    <div class="memory-img" style="background-color: #fff9e6;">
                        <i class="fas fa-star" style="color: #ffd166;"></i>
                    </div>
                    <div class="memory-content">
                        <h3>Milestones Together</h3>
                        <p>From school achievements to personal growth moments, celebrating your successes has been one of my greatest joys.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Meaning of 18 Section -->
    <section id="meaning">
        <div class="container">
            <h2>The Meaning of 18</h2>
            <p>Welcome to adulthood - a world of new opportunities</p>
            <div class="meaning-container">
                <div class="meaning-text">
                    <p>Turning 18 is a significant rite of passage that symbolizes the transition from childhood to adulthood. It's a moment filled with both excitement and responsibility.</p>
                    <p>At 18, you're gaining legal independence, but more importantly, you're stepping into your own power. This is the time to:</p>
                    <ul class="milestone-list">
                        <li>Discover your passions and pursue them fearlessly</li>
                        <li>Make decisions that shape your future</li>
                        <li>Build meaningful relationships that uplift you</li>
                        <li>Learn from both successes and setbacks</li>
                        <li>Create a life that truly reflects who you are</li>
                    </ul>
                    <p>Remember, adulthood isn't about having everything figured out. It's about having the courage to navigate the unknown and the wisdom to appreciate the journey.</p>
                </div>
                <div class="meaning-visual">
                    <div class="birthday-cake">
                        <div class="cake">
                            <div class="candle"></div>
                        </div>
                    </div>
                    <p>Make a wish and blow out your candles! May all your dreams come true.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Birthday Wishes Section -->
    <section id="wishes">
        <div class="container">
            <h2>My Birthday Wishes For You</h2>
            <div class="wishes-container">
                <div class="wish-box">
                    <p>May your 18th year be filled with adventures that excite you, lessons that strengthen you, and moments that take your breath away. May you find courage in challenges and joy in simple pleasures. May you always stay true to yourself and remember how loved you are. Happy birthday to an incredible soul who deserves the world and more!</p>
                </div>
                <a href="#hero" class="btn">Back to Top <i class="fas fa-arrow-up"></i></a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <p>Created with <i class="fas fa-heart" style="color: #ff6b8b;"></i> for a very special 18th birthday</p>
            <p class="signature">Forever your friend</p>
            <p>© A Digital Birthday Gift</p>
        </div>
    </footer>

    <script>
        // Create confetti effect
        function createConfetti() {
            const heroSection = document.getElementById('hero');
            for (let i = 0; i < 50; i++) {
                const confetti = document.createElement('div');
                confetti.classList.add('confetti');
                confetti.style.left = Math.random() * 100 + 'vw';
                confetti.style.width = Math.random() * 10 + 5 + 'px';
                confetti.style.height = confetti.style.width;
                confetti.style.animationDelay = Math.random() * 5 + 's';
                heroSection.appendChild(confetti);
                
                // Animate confetti falling
                confetti.animate([
                    { top: '0px', transform: 'rotate(0deg)' },
                    { top: '100vh', transform: 'rotate(360deg)' }
                ], {
                    duration: Math.random() * 3000 + 2000,
                    iterations: Infinity
                });
            }
        }
        
        // Navigation dots functionality
        const dots = document.querySelectorAll('.dot');
        const sections = document.querySelectorAll('section');
        
        dots.forEach(dot => {
            dot.addEventListener('click', function() {
                const targetSection = this.getAttribute('data-section');
                document.getElementById(targetSection).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
        
        // Update active dot based on scroll position
        window.addEventListener('scroll', function() {
            let current = '';
            sections.forEach(section => {
                const sectionTop = section.offsetTop;
                const sectionHeight = section.clientHeight;
                if (pageYOffset >= (sectionTop - sectionHeight / 3)) {
                    current = section.getAttribute('id');
                }
            });
            
            dots.forEach(dot => {
                dot.classList.remove('active');
                if (dot.getAttribute('data-section') === current) {
                    dot.classList.add('active');
                }
            });
        });
        
        // Birthday countdown (for fun)
        function updateCountdown() {
            const now = new Date();
            // Set the birthday date - you can customize this
            const birthday = new Date(now.getFullYear(), now.getMonth(), now.getDate() + 1); // Tomorrow as example
            
            const diff = birthday - now;
            
            if (diff > 0) {
                const hours = Math.floor(diff / (1000 * 60 * 60));
                const minutes = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
                const seconds = Math.floor((diff % (1000 * 60)) / 1000);
                
                // You could display this somewhere if you want
                // console.log(`Countdown: ${hours}h ${minutes}m ${seconds}s`);
            }
        }
        
        // Initialize
        document.addEventListener('DOMContentLoaded', function() {
            createConfetti();
            updateCountdown();
            setInterval(updateCountdown, 1000);
            
            // Add click to memory cards
            const memoryCards = document.querySelectorAll('.memory-card');
            memoryCards.forEach(card => {
                card.addEventListener('click', function() {
                    this.style.transform = 'scale(0.98)';
                    setTimeout(() => {
                        this.style.transform = '';
                    }, 200);
                });
            });
            
            // Make the candle interactive
            const candle = document.querySelector('.candle');
            if (candle) {
                candle.addEventListener('click', function() {
                    const flame = this.nextElementSibling;
                    if (flame.style.opacity === '0') {
                        flame.style.opacity = '1';
                        flame.style.animation = 'flicker 0.8s infinite alternate';
                    } else {
                        flame.style.opacity = '0';
                        flame.style.animation = 'none';
                    }
                });
            }
        });
    </script>
</body>
</html>
