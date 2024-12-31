# About Me Website

This repository contains the main page for an "About Me" website. The page is styled to use Playfair Display for the heading font and Times New Roman for the body font.

## Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: "Times New Roman", Times, serif;
            color: black;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #f4f4f4;
        }

        header {
            background: #ffffff;
            padding: 20px;
            text-align: center;
            border-bottom: 2px solid #ccc;
        }

        header h1 {
            font-family: 'Playfair Display', serif;
            color: lightblue;
            font-size: 2.5em;
            margin: 0;
        }

        .container {
            max-width: 800px;
            margin: 30px auto;
            padding: 20px;
            background: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 5px;
        }

        .container p {
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>About Me</h1>
    </header>
    <div class="container">
        <p>Hello! My name is [Your Name]. Welcome to my personal website. I am passionate about [Your Passion] and enjoy working on projects related to [Your Interest].</p>

        <p>In my free time, I love to [Your Hobby or Activity]. This website is a place for me to share my work, thoughts, and connect with like-minded individuals. Feel free to browse around and learn more about me!</p>

        <p>If you want to get in touch, don't hesitate to reach out through the contact section.</p>
    </div>
</body>
</html>
```
