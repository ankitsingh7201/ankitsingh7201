<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Blog Post</title>
    <style>
        /* Basic CSS for responsiveness */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #ffffff;
        }
        h1 {
            color: #333;
        }
        p {
            line-height: 1.6;
        }
        /* Responsive CSS */
        @media screen and (max-width: 768px) {
            .container {
                padding: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>My Blog Post</h1>
        </header>
        <nav>
            <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/about">About</a></li>
                <li><a href="/contact">Contact</a></li>
            </ul>
        </nav>
        <main>
            <article>
                <h2>Blog Post Title</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed eget est quis nunc commodo iaculis.</p>
            </article>
        </main>
        <footer>
            <p>&copy; 2023 My Blog</p>
        </footer>
    </div>
</body>
</html>
