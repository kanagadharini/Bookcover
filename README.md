# Ex.06 Book Front Cover Page Design
## Date:27/09/2025

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
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #f2f2f2;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background: rgb(77, 29, 45);
      border: 2px solid #333;
      padding: 40px 30px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .title {
      font-size: 28px;
      font-weight: bold;
      color: #2e2e2e;
      text-align: center;
      line-height: 1.3;
    }

    .subtitle {
      font-size: 16px;
      margin-top: 10px;
      text-align: center;
      font-style: italic;
    }

    .image {
      flex: 1;
      background: url('_https://www.google.com/url?sa=i&url=https%3A%2F%2Fstock.adobe.com%2Fsearch%3Fk%3Dnature%2Bbackground&psig=AOvVaw3LzzT2K_01LoNF6wz4LgG5&ust=1759048589638000&source=images&cd=vfe&opi=89978449&ved=0CBUQjRxqFwoTCPjUx-TE-I8DFQAAAAAdAAAAABAL') center/contain no-repeat;
      margin: 30px 0;
    }

    .author {
      font-size: 18px;
      text-align: center;
      color: #444;
      margin-top: 20px;
    }

    .line {
      height: 2px;
      background: #333;
      width: 50px;
      margin: 10px auto;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div>
      <div class="title">The Psychology of Simplicity</div>
      <div class="line"></div>
      <div class="subtitle">Understanding the beauty of less</div>
    </div>
    <div class="image">
        <img src="https:/www/.google.com/imgres?q=hollow%20queen&imgurl=https%3A%2F%2Fm.media-amazon.com%2Fimages%2FI%2F81A1mYHUIuL._UF1000%2C1000_QL80_.jpg&imgrefurl=https%3A%2F%2Fwww.amazon.in%2FHollow-Queen-Stolen-Empire-Book-ebook%2Fdp%2FB07TJ1XLC5&docid=phKVZnOLJE9lsM&tbnid=PedAOaUDtCZt-M&vet=12ahUKEwjcwK2SyPiPAxXLa2wGHbSSEE4QM3oECBcQAA..i&w=667&h=1000&hcb=2&itg=1&ved=2ahUKEwjcwK2SyPiPAxXLa2wGHbSSEE4QM3oECBcQAA" length="10%" width="100%">
    </div>
    <div class="author">By Kanagadharini</div>
  </div>
</body>
</html>
```


## OUTPUT:
![alt text](<Screenshot (20).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
