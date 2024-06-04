<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shriram Database</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #007bff;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #0056b3;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            font-size: 36px;
            margin-bottom: 20px;
        }
        .article {
            border-top: 2px solid #007bff;
            padding-top: 20px;
        }
        .article h2 {
            font-size: 24px;
            margin-bottom: 10px;
        }
        .article p {
            font-size: 16px;
            line-height: 1.6;
            margin-bottom: 20px;
        }
        .social-media {
            text-align: center;
            margin: 20px 0;
        }
        .social-media a {
            text-decoration: none;
            color: #007bff;
            margin: 0 10px;
            font-size: 20px;
        }
        .contact-info {
            margin: 20px 0;
        }
        footer {
            text-align: center;
            margin-top: 50px;
            padding: 20px 0;
            background-color: #007bff;
            color: #fff;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .form-section {
            border-top: 2px solid #007bff;
            padding-top: 20px;
        }
        .form-section h2 {
            font-size: 24px;
            margin-bottom: 10px;
        }
        .form-section form {
            display: flex;
            flex-direction: column;
        }
        .form-section label {
            margin-bottom: 5px;
            font-weight: bold;
        }
        .form-section input, .form-section textarea {
            margin-bottom: 15px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }
        .form-section button {
            padding: 10px 15px;
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 5px;
            font-size: 16px;
            cursor: pointer;
        }
        .form-section button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <header>
        <h1>Shriram Database</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#research">Research</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container" id="home">
        <div class="article">
            <h2>Research Article Title</h2>
            <p>This is where your research article abstract or summary would go. You can provide a brief overview of your research findings, methodology, and significance.</p>
            <p>If you'd like to include more details or provide a link to the full article, you can do so here.</p>
        </div>

        <div class="form-section" id="form">
            <h2>Submit Your Details</h2>
            <form action="mailto:shriram.b@stjohns.in" method="post" enctype="text/plain">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="clg-name">College Name:</label>
                <input type="text" id="clg-name" name="clg-name" required>
                
                <label for="contact-number">Contact Number:</label>
                <input type="text" id="contact-number" name="contact-number" required>
                
                <label for="article-name">Article Name:</label>
                <input type="text" id="article-name" name="article-name" required>
                
                <label for="pi">Principal Investigator (PI):</label>
                <input type="text" id="pi" name="pi" required>
                
                <label for="co-pi">Co-Principal Investigator (Co-PI):</label>
                <input type="text" id="co-pi" name="co-pi" required>
                
                <button type="submit">Submit</button>
            </form>
        </div>

        <div class="contact-info" id="contact">
            <h2>Contact Me</h2>
            <p>Email: <a href="mailto:shriram.b@stjohns.in">shriram.b@stjohns.in</a></p>
            <p>Phone: 9585358547</p>
            <p>Address: 123 Research Lane, Science City, SC 12345</p>
        </div>

        <div class="social-media">
            <a href="https://twitter.com/shriram" target="_blank">Twitter</a>
            <a href="https://linkedin.com/in/shriram" target="_blank">LinkedIn</a>
            <a href="https://github.com/shriram" target="_blank">GitHub</a>
        </div>
    </div>

    <footer>
        &copy; 2024 Shriram | All rights reserved
    </footer>
</body>
</html>
