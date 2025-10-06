# Ex.06 Book Front Cover Page Design
# Date:03/10/2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover - Fundamentals of Web Application Development</title>
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background: linear-gradient(135deg, #6a11cb, #2575fc, #ff9a9e);
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      border-radius: 16px;
      border: 3px solid rgba(255, 255, 255, 0.9);
      box-shadow: 0 10px 30px rgba(0,0,0,0.6), 0 0 25px rgba(255,255,255,0.3);
      position: relative;
      padding: 35px 30px;
      text-align: center;
      color: white;
      backdrop-filter: brightness(0.85);
      transition: transform 0.4s ease, box-shadow 0.4s ease;

      /* 🌐 Web-themed background image */
      background-image: 
        url("web-pattern.png"),      /* your web image */
        linear-gradient(135deg, rgba(106,17,203,0.8), rgba(37,117,252,0.8), rgba(255,154,158,0.8));
      background-size: cover;
      background-blend-mode: overlay;
    }

    .book-cover:hover {
      transform: scale(1.03);
      box-shadow: 0 12px 40px rgba(0,0,0,0.7), 0 0 40px rgba(255,255,255,0.5);
    }

    .book-header {
      font-size: 18px;
      letter-spacing: 3px;
      text-transform: uppercase;
      border-bottom: 2px solid white;
      display: inline-block;
      padding-bottom: 5px;
      margin-bottom: 15px;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
    }

    h1 {
      font-size: 26px;
      margin-top: 30px;
      font-weight: 700;
      line-height: 1.5;
      text-shadow: 2px 2px 6px rgba(0,0,0,0.6);
      letter-spacing: 1px;
    }

    .subtitle {
      font-size: 16px;
      margin-top: 15px;
      font-style: italic;
      color: #fff8dc;
      text-shadow: 1px 1px 4px rgba(0,0,0,0.6);
    }

    .tagline {
      font-size: 13px;
      margin-top: 8px;
      background: rgba(255,255,255,0.2);
      padding: 5px 10px;
      border-radius: 10px;
      display: inline-block;
      color: #fffbe7;
      text-transform: uppercase;
      letter-spacing: 1px;
    }

    .author-section {
      position: absolute;
      bottom: 85px;
      left: 0;
      width: 100%;
    }

    .photo {
      width: 100px;
      height: 100px;
      border: 3px solid #fff;
      border-radius: 50%;
      object-fit: cover;
      margin-top: 10px;
      box-shadow: 0 0 10px rgba(255,255,255,0.6);
      transition: transform 0.4s ease;
    }

    .photo:hover {
      transform: rotate(5deg) scale(1.05);
    }

    .special {
      font-size: 15px;
      font-weight: bold;
      margin-top: 12px;
      text-shadow: 1px 1px 5px rgba(0,0,0,0.6);
      color: #ffebc6;
      letter-spacing: 1px;
    }

    .author {
      margin-top: 6px;
      font-weight: bold;
      font-size: 16px;
      color: #fffbd8;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.5);
    }

    .footer {
      position: absolute;
      bottom: 15px;
      width: 100%;
      text-align: center;
      font-weight: bold;
      letter-spacing: 3px;
      text-shadow: 0 0 6px rgba(255,255,255,0.7);
      font-size: 20px;
      color: #ffffff;
      animation: glowText 2s ease-in-out infinite alternate;
    }

    @keyframes glowText {
      from { text-shadow: 0 0 5px #fff, 0 0 10px #ffdf7f; }
      to { text-shadow: 0 0 10px #fff, 0 0 20px #ffd700; }
    }

    .ribbon {
      position: absolute;
      top: 20px;
      right: -40px;
      background: #ff4757;
      color: white;
      padding: 8px 50px;
      transform: rotate(45deg);
      font-weight: bold;
      font-size: 12px;
      box-shadow: 0 0 10px rgba(0,0,0,0.4);
      letter-spacing: 1px;
      text-transform: uppercase;
    }

  </style>
</head>
<body>

  <div class="book-cover">
    <div class="ribbon">New Edition</div>
    <div class="book-header">SEC INSIGHTS</div>
    <h1>FUNDAMENTALS OF<br>WEB APPLICATION<br>DEVELOPMENT</h1>
    <div class="subtitle">Deep Dive into HTML, CSS & JS</div>
    <div class="tagline">Top Seller of 2025</div>

    <div class="author-section">
      <img src="boy.png" alt="Author Photo" class="photo">
      <div class="special">SPECIAL EDITION</div>
      <div class="author">SHYAM (25017615)</div>
    </div>

    <div class="footer">SEC</div>
  </div>

</body>
</html>
```
# OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-10-06 195255" src="https://github.com/user-attachments/assets/8e47d8fb-b019-4aa4-95f4-3b679e02b48f" />

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
