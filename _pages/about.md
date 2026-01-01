<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bedru Yimam Ahmed - Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f8f9fa;
            color: #333;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        /* NEW: Top header section with name and photo side-by-side */
        .top-header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 20px;
            padding: 20px 0;
            border-bottom: 2px solid #2e8b57;
        }

        .name-section {
            flex: 1;
        }

        .header-photo {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            overflow: hidden;
            border: 5px solid #2e8b57;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
            margin-left: 30px;
        }

        .header-photo img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        h1 {
            font-size: 2.8rem;
            color: #2c3e50;
            margin-bottom: 5px;
        }

        .subtitle {
            font-size: 1.2rem;
            color: #7f8c8d;
            margin-bottom: 10px;
        }

        /* Navigation */
        nav {
            background-color: #2c3e50;
            padding: 15px 0;
            margin-bottom: 40px;
            border-radius: 8px;
        }

        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
            flex-wrap: wrap;
        }

        nav li {
            margin: 0 20px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: 500;
            font-size: 1.1rem;
            padding: 8px 16px;
            border-radius: 4px;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #3498db;
        }

        /* Main content layout */
        .content {
            display: flex;
            flex-wrap: wrap;
            gap: 40px;
            margin-bottom: 40px;
        }

        .main-info {
            flex: 3;
            min-width: 300px;
        }

        .sidebar {
            flex: 2;
            min-width: 250px;
        }

        /* Biography section */
        .biography {
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            margin-bottom: 30px;
        }

        .biography h2 {
            color: #2c3e50;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #3498db;
        }

        .biography p {
            font-size: 1.1rem;
            line-height: 1.8;
            color: #555;
        }

        /* Contact info box */
        .contact-box {
            background-color: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            margin-bottom: 30px;
        }

        .contact-box h3 {
            color: #2c3e50;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid #3498db;
        }

        .contact-item {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
        }

        .contact-icon {
            background-color: #3498db;
            color: white;
            width: 36px;
            height: 36px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 15px;
        }

        /* Buttons */
        .buttons {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 20px;
        }

        .btn {
            display: inline-block;
            padding: 12px 28px;
            background-color: #3498db;
            color: white;
            text-decoration: none;
            border-radius: 6px;
            font-weight: 600;
            transition: all 0.3s ease;
            text-align: center;
            border: none;
            cursor: pointer;
        }

        .btn:hover {
            background-color: #2980b9;
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .btn-cv {
            background-color: #2e8b57;
        }

        .btn-cv:hover {
            background-color: #26734a;
        }

        /* Responsive design */
        @media (max-width: 768px) {
            .top-header {
                flex-direction: column;
                text-align: center;
            }
            
            .header-photo {
                margin-left: 0;
                margin-top: 20px;
                width: 120px;
                height: 120px;
            }
            
            h1 {
                font-size: 2.2rem;
            }
            
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav li {
                margin: 5px 0;
            }
            
            .content {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- NEW: Top header with name and photo -->
        <header class="top-header">
            <div class="name-section">
                <h1>Bedru Yimam Ahmed</h1>
                <p class="subtitle">Lecturer & Researcher in Information Technology</p>
                <div class="contact-item">
                    <div class="contact-icon">
                        <i class="fas fa-university"></i>
                    </div>
                    <span>Wollo University, Dessie, Ethiopia</span>
                </div>
                <div class="contact-item">
                    <div class="contact-icon">
                        <i class="fas fa-envelope"></i>
                    </div>
                    <span>bedruy4@gmail.com</span>
                </div>
            </div>
            <div class="header-photo">
                <!-- Replace with your actual photo path -->
                <img src="https://via.placeholder.com/150" alt="Bedru Yimam Ahmed">
            </div>
        </header>

        <!-- Navigation -->
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Research</a></li>
                <li><a href="#">Publications</a></li>
                <li><a href="#">Teaching</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>

        <div class="content">
            <main class="main-info">
                <!-- Biography -->
                <section class="biography">
                    <h2>Biography</h2>
                    <p>I am a dedicated Information Technology lecturer and researcher at Wollo University in Ethiopia, specializing in Artificial Intelligence, Machine Learning, and Computer Vision. My academic journey is driven by a passion for leveraging technology to address local and regional development challenges while contributing to the advancement of information Technology education in Ethiopia.</p>
                    <p>With a strong commitment to both teaching and research, I strive to bridge the gap between theoretical knowledge and practical applications, preparing the next generation of Ethiopian technologists and researchers to tackle complex problems through innovative solutions.</p>
                </section>
            </main>

            <aside class="sidebar">
                <!-- Download CV and Contact buttons -->
                <div class="contact-box">
                    <h3>Quick Actions</h3>
                    <div class="buttons">
                        <a href="#" class="btn btn-cv">
                            <i class="fas fa-download"></i> Download CV
                        </a>
                        <a href="#" class="btn">
                            <i class="fas fa-envelope"></i> Contact Me
                        </a>
                    </div>
                </div>
            </aside>
        </div>
    </div>

    <!-- Font Awesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

    <script>
        // Add any JavaScript functionality here if needed
        document.addEventListener('DOMContentLoaded', function() {
            console.log('Portfolio page loaded');
        });
    </script>
</body>
</html>
