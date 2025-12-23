# Ex.05 Book Cover Page Design
## Date:18/12/2025

## AIM:
To design a book back cover page using HTML and CSS.

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
<html>
    <head>
        <title>Cascading Style Sheet</title>
        <link href="style.css" rel="stylesheet">
    </head>
    <body>
        <div class="cover">
            <div class="head">
            <h1>ABOUT THE BOOK</h1>
            <hr>
            </div>
            <div class="text">
                <p>This Book<span>Cryptocurrency is a form of digital currency</span> that operates on decentralized networks using blockchain technology and cryptography to secure transactions, rather than relying on a central authority like a bank or government. </p>
            </div>
            <div class="quotes">
            Bitcoin is a tool for freeing humanity from oligarchs and tyrants, dressed up as a get-rich-quick scheme.
            </div>
            <div class="author-box">
                 <div class="img"></div>

                <div class="author">
                     <div class="author-name">HARSHITH SANJAI S</div>
                     <p>
                        "Harshith Sanjai s is a well known novelist in his college and he wrote about lots of good things for our society." 


                     </p>
                </div>
            </div>
            <div class="footer">
                <div class="footer-left">
                    <strong>SEC Publishers</strong>
                    <br>
                    <div class="printed">printed in India</div>
                </div>
                <div class="price">Price= RS299</div>
            </div>
        </div>
    </body>
</html>


body
{
    background: url('Screenshot 2025-12-18 001136.png') center / contain no-repeat fixed;
    min-height: 100vh;
    display: flex;
    justify-content: center;
}
.cover
{
    padding-left: 700px;
    padding-right: 700px;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

.head
{
    padding-top: 20px;
    font-style: Montserrat;
    color: rgb(55, 41, 67);
    padding-left: 25px;
}
.text
{
    font-size: 16px;
    text-align: center;
    text-align: justify;
    padding-left: 25px;
    font-style:inherit
}
span
{
    background-color: rgb(163, 73, 73);
}
.quotes
{
    margin: 15px 0;
    padding: 15px 15px;
    background: rgb(105, 97, 97);
    border-left: 6px solid rgb(180, 221, 240);
    font-style: italic;
}
.author
{
    display: flex;
    flex-direction: column;
    font-size: 15px;
    
}

.author-box 
{
    display: flex;
    gap: 8px;
    background: rgb(50, 145, 78);
    padding: 8px;
    border-radius: 8px;
    margin-top: 15px;
    text-align: justify;
    align-items: center;
}
.img 
{
    width: 410px;
    height: 110px;
    border-radius: 8px;
    background-image: url('Screenshot 2025-12-18 001404.png');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
}
.author-name 
{
    color: rgb(226, 162, 24);
    font-weight: bold;
    font-size: 15px;
}
.footer 
{
    margin-top: auto;
    background-color:rgb(54, 139, 158);
    color: rgb(38, 37, 36);
    padding: 5px 5px;
    border-radius: 10px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.footer-left 
{
    display: flex;
    flex-direction: column;
}
.printed
{
    font-size: 14px;
}
.price 
{
    font-weight: bold;
    color: rgb(160, 17, 17);
    font-size: 18px;
}


```

## OUTPUT:
![alt text](<Screenshot (23).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
