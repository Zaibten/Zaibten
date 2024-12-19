<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tech Explorer | Muzamil</title>
    <style>
        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        body {
            background-color: #1a1a1a;
            color: white;
            line-height: 1.6;
            padding: 0;
            margin: 0;
        }
        h1, h2, h3 {
            text-align: center;
            margin-bottom: 20px;
        }
        .container {
            width: 80%;
            margin: 0 auto;
        }
        .text-center {
            text-align: center;
        }
        .header {
            background: #000;
            padding: 50px 0;
            text-align: center;
            animation: fadeIn 3s ease;
        }
        h1 span {
            color: #ff6347;
        }

        /* 3D hover effect on images */
        .hover3d-container {
            perspective: 1500px;
            display: flex;
            justify-content: center;
            margin: 20px 0;
        }

        .hover3d-content {
            width: 200px;
            height: 200px;
            position: relative;
            transform-style: preserve-3d;
            transform: rotateY(0deg);
            transition: transform 0.5s ease;
        }

        .hover3d-container:hover .hover3d-content {
            transform: rotateY(180deg);
        }

        .hover3d-content img {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            backface-visibility: hidden;
        }

        /* Loader */
        .loader {
            text-align: center;
            margin-top: 50px;
        }
        .loader img {
            animation: spin 2s infinite linear;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        /* Fade-in and Slide-in effects */
        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        .fade-in {
            animation: fadeIn 2s ease;
        }

        /* Section Styles */
        .section {
            padding: 60px 0;
        }

        .section .section-title {
            font-size: 2rem;
            margin-bottom: 20px;
            color: #ff6347;
        }

        .section p {
            font-size: 1.1rem;
            line-height: 1.8;
            margin-bottom: 20px;
        }

        /* Card and Projects */
        .card {
            background: #222;
            padding: 20px;
            margin: 10px;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }
        .card:hover {
            transform: scale(1.05);
        }

        /* Buttons */
        .btn {
            background: #ff6347;
            color: white;
            padding: 12px 30px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s ease;
        }

        .btn:hover {
            background: #ff4500;
        }

        /* Media Queries for Responsiveness */
        @media screen and (max-width: 768px) {
            .container {
                width: 90%;
            }

            .header h1 {
                font-size: 2rem;
            }

            .section {
                padding: 40px 0;
            }
        }
    </style>
</head>
<body>

    <!-- Loader Section -->
    <div class="loader">
        <img src="https://github.com/user-attachments/assets/02a8a87a-5bd1-4ec6-adb7-55fa1b90a55e" alt="loader" width="100" height="100">
    </div>

    <!-- Header Section -->
    <header class="header fade-in">
        <h1>🚀 <span>Tech Explorer</span>: Pioneering the Future of Technology with Innovation and Expertise 💡</h1>
        <p>"Charting the Path of Progress Through Unmatched Expertise, Creativity, and Cutting-Edge Solutions"</p>
    </header>

    <!-- Vision Section -->
    <div class="section text-center fade-in">
        <h2 class="section-title">🌍 Vision: Shaping Tomorrow’s Digital Landscape Today ✨</h2>
        <p>In the fast-paced world of technology, I believe in exploring the unknown, constantly learning, and pushing the boundaries of what’s possible. My vision as a Tech Explorer is to lead businesses into the future by leveraging cutting-edge technologies to solve tomorrow's problems, today.</p>
    </div>

    <!-- Mission Section -->
    <div class="section fade-in">
        <h2 class="section-title">🎯 Mission: Empowering Businesses to Reach New Heights Through Technology 🚀</h2>
        <p>As a Tech Explorer, my mission is to help businesses navigate the complexities of the digital world, providing them with the tools, strategies, and technology needed to thrive in today’s competitive landscape.</p>
    </div>

    <!-- Tech Stack Section -->
    <div class="section fade-in">
        <h2 class="section-title">🛠️ Tech Explorer’s Toolkit: Expertise That Drives Innovation ⚙️</h2>
        <div class="container">
            <div class="card">
                <h3>Web & Full-Stack Development 🌐</h3>
                <ul>
                    <li>Frontend: ReactJS, WordPress, Shopify, HTML5, CSS3, JavaScript</li>
                    <li>Backend: Node.js, Express.js, Django, .NET MVC</li>
                    <li>Databases: SQL Server, MongoDB, Firebase</li>
                    <li>Version Control: Git, GitHub</li>
                </ul>
            </div>
            <div class="card">
                <h3>AI & Machine Learning 🤖</h3>
                <ul>
                    <li>Machine Learning: Python, TensorFlow, Scikit-learn</li>
                    <li>Deep Learning: Neural Networks, CNNs, RNNs</li>
                    <li>AI Frameworks: PyTorch, Hugging Face</li>
                </ul>
            </div>
        </div>
    </div>

    <!-- Notable Projects Section -->
    <div class="section fade-in">
        <h2 class="section-title">🏆 Notable Projects & Achievements: Crafting the Future of Technology 🌟</h2>
        <div class="container">
            <div class="card">
                <h3>Anatomy-Server-Code-NodeJS-Express-Mongo</h3>
                <p>A dynamic backend architecture for managing anatomy data, empowering medical professionals with real-time updates.</p>
            </div>
            <div class="card">
                <h3>Car-Pooling-Application-Using-Flutter-React</h3>
                <p>A cross-platform app built with Flutter and React, optimizing ride-sharing for urban commuters.</p>
            </div>
        </div>
    </div>

    <!-- Contact Section -->
    <div class="section text-center fade-in">
        <h2 class="section-title">📞 Let’s Explore the Future Together! 🌍</h2>
        <p>Are you ready to take your business to new heights? Let’s discuss how we can embark on this exciting journey together!</p>
        <a href="mailto:muzamilkhanofficials@gmail.com" class="btn">Contact Me</a>
    </div>

</body>
</html>
