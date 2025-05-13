# Ex.06 Book Front Cover Page Design
## Date:13.5.25

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:

'''
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>3D Book Cover</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: radial-gradient(circle at center, #1e1f26, hsla(240, 84%, 5%, 0.61));
      font-family: 'Poppins', sans-serif;
    }

    .book-container {
      width: 420px;
      height: 600px;
      background: linear-gradient(145deg, #54c40e, #dd2f94);
      border-radius: 20px;
      padding: 30px;
      color: white;
      box-shadow: 15px 15px 30px #921212, -15px -15px 30px #3b0609;
      position: relative;
      overflow: hidden;
    }

    .title {
      font-size: 26px;
      font-weight: bold;
      text-align: center;
      margin-top: 30px;
      letter-spacing: 1px;
    }

    .subtitle {
      font-size: 18px;
      text-align: center;
      margin-top: 10px;
      color: #b5d7ad;
      font-style: italic;
    }

    .branding {
      text-align: center;
      font-size: 20px;
      color: #8aeaec;
      margin-top: 40px;
    }

    .author {
      position: absolute;
      bottom: 30px;
      left: 30px;
      font-size: 16px;
      color: #b4adb0;
    }

    .publisher {
      position: absolute;
      top: 30px;
      right: 30px;
      font-size: 14px;
      color: #c3f4ff;
    }

    .edition {
      position: absolute;
      bottom: 80px;
      left: 30px;
      font-size: 14px;
      color: #92ce96;
    }

    .image-frame {
      position: absolute;
      bottom: 30px;
      right: 30px;
      width: 110px;
      height: 140px;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 0 10px rgba(255, 255, 255, 0.3);
    }

    .image-frame img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .highlight-line {
      height: 3px;
      width: 60%;
      background: #ff9800;
      margin: 30px auto;
      border-radius: 50px;
      box-shadow: 0 0 8px #774822;
    }
  </style>
</head>
<body>
  <div class="book-container">
    <div class="publisher">DIGI BOOKS</div>
    <div class="branding">TECH VISION</div>
    <div class="title">UNLOCKING KNOWLEDGE</div>
    <div class="subtitle">THE KNOWLEDGE HUB</div>
    <div class="highlight-line"></div>
    <div class="edition">SIXTH EDITION</div>
    <div class="author"><b>Varshinee</b></div>
    <div class="image-frame">
      <img src="C:\Users\admin\cover\proj5\bookapp\static\212224040356.png" alt="Author">
    </div>
  </div>
</body>
</html>

'''
## OUTPUT:
![Screenshot 2025-05-13 213631](https://github.com/user-attachments/assets/fc05d596-eb49-4928-acc4-d39f4d5e2dfb)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
