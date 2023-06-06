# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

Step 1:
Clone the github repository and create a django admin interface

Step 2:
Write HTML and CSS for designing book cover page and execute them .

Step 3:
Validate the HTML and CSS code.

Step 4:
Publish the website in the given URL.

## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 700px;
            background-color: #3d3a3a;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 30px;
            font-family: 'Franklin Gothic Heavy', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/pngtree.jpg);
            background-size: cover;
        }
            

        .toptext{
            color:white;

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: white;
            display: inline;
            position: relative;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Franklin Gothic Heavy', monospace;
            font-size: 25px;
            text-align: left;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .edition{
            color:red;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:T'Franklin Gothic Heavy';
            font-size: large;
            position: relative;
            top:40px;
        }
        .photo{
            position: relative;
            top: 175px;
            left: 300px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            <div class="tophr">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>Responsive Web Design With HTML5 and CSS</h1></div>
            <div class="subtitle">
                Develop future-proof responsive websites using the latest HTML5 and CSS Techniques
            </div>
            <div class="photo">
                <img src="static/html/author.jpeg" width="100" height="110" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
               <p><b>RAHUL.B</b></p>
            </div>
            <div class="publisher">
                PACKT
            </div>
            <div class="edition">
                <b>First Edition</b>
            </div>
            
        </div>
    </body>
</html>
```

## Output:

![bookpagecover](https://github.com/RAHUL-22001882/cover-page-design/assets/123528986/abe97bbc-b60c-4fc5-a13a-763880ade2fa)

## Result:

The program for designing book cover page using HTML and CSS is executed successfully

## Result:
Write your result
