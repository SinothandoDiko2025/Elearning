<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Graphic Design Course - Course UI/UX Skeleton</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 15px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        .container {
            display: flex;
            flex-direction: row;
            padding: 20px;
        }
        .sidebar {
            width: 250px;
            background-color: #333;
            color: white;
            padding: 15px;
        }
        .sidebar a {
            color: white;
            display: block;
            padding: 8px;
            text-decoration: none;
        }
        .sidebar a:hover {
            background-color: #575757;
        }
        .main-content {
            flex: 1;
            margin-left: 20px;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        .progress-bar {
            background-color: #e0e0e0;
            border-radius: 5px;
            overflow: hidden;
            height: 10px;
            width: 100%;
        }
        .progress-bar span {
            display: block;
            height: 100%;
            background-color: #4CAF50;
            width: 70%;
        }
        .footer {
            background-color: #333;
            color: white;
            padding: 10px;
            text-align: center;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .button {
            background-color: #4CAF50;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            text-align: center;
            display: inline-block;
            text-decoration: none;
        }
        .button:hover {
            background-color: #45a049;
        }
        .module-section {
            margin-bottom: 20px;
        }
        .module-title {
            font-size: 1.5em;
            margin-bottom: 10px;
        }
        .module-description {
            margin-bottom: 15px;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Pathways to Industry: Exploring Career Opportunities in Graphic Design</h1>
    </header>

    <!-- Main Content Area -->
    <div class="container">
        <!-- Sidebar -->
        <div class="sidebar">
            <h3>Course Navigation</h3>
            <a href="#">Home</a>
            <a href="#">Modules</a>
            <a href="#">Portfolio</a>
            <a href="#">Peer Feedback</a>
            <a href="#">Profile</a>
        </div>

        <!-- Main Content -->
        <div class="main-content">
            <!-- Module 1 -->
            <div class="module-section">
                <div class="module-title">Module 1: Introduction to the Graphic Design Industry</div>
                <div class="module-description">
                    In this module, we’ll explore various career paths in graphic design. You will choose a project based on your interest.
                </div>
                <button class="button">Start Module</button>
            </div>

            <!-- Module Progress Bar -->
            <div class="module-section">
                <div class="module-title">Your Progress:</div>
                <div class="progress-bar">
                    <span></span> <!-- Adjust width in percentage for progress -->
                </div>
            </div>

            <!-- Discussion Section -->
            <div class="module-section">
                <div class="module-title">Discussion</div>
                <div class="module-description">
                    Discuss the challenges and opportunities you see in the graphic design industry with your peers.
                </div>
                <button class="button">Join Discussion</button>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <div class="footer">
        <p>Course Platform - All Rights Reserved &copy; 2025</p>
    </div>

</body>
</html>
