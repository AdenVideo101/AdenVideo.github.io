# Save the original home page (index.html) file for download.

original_home_page_path = "/mnt/data/index.html"

# Content of the original home page.
original_home_page_content = """
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luxury Car Videography</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #000;
            color: #fff;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            display: flex;\n            justify-content: center;
            background-color: #222;
            padding: 10px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 20px;
            text-align: center;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #000;
            color: #fff;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Luxury Car Videography</h1>
        <p>Capturing the beauty and elegance of high-class vehicles</p>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="about.html">About Us</a>
        <a href="gallery.html">Gallery</a>
        <a href="services.html">Services</a>
        <a href="contact.html">Contact Us</a>
    </nav>

    <main>
        <h2>Welcome to Luxury Car Videography</h2>
        <p>We specialize in creating stunning visuals for luxury cars, exotic cars, and sport bikes. Stay tuned for updates as we build our portfolio!</p>
    </main>

    <footer>
        <p>&copy; 2025 Luxury Car Videography. All Rights Reserved.</p>
    </footer>
</body>
</html>
"""

# Save the file
with open(original_home_page_path, "w") as file:
    file.write(original_home_page_content)

original_home_page_path
