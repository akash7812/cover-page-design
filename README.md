# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
First fork the given link and then go inside create a project named myproj and then create a app named myapp.
### Step 2:
And then go to settings.py in myproj and make some changes.
### Step 3:
create a folder under myproj named static and then inside the folder create a file named cover.html and the paste the code and then have the cover image and your photo on the same folder.
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
            height: 600px;
            color:rgb(0, 234, 255);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(https://i.ibb.co/9N4dHRp/Black-Beige-Minimalist-Photography-Portfolio-Cover-Page.png);
            background-size: cover;
        }
            

        .insight{
            color: rgb(42, 165, 65);

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(0, 221, 255);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color: blue;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>Fundamentals of Web Application Development</h1></div>
            <div class="subtitle">
                HTML and CSS Combined with Django Architecture
            </div>
            <div class="mypic">
                <img src="https://i.ibb.co/Gp8DX6N/IMG-20230705-WA0040.jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(208, 255, 0);">
            </div>
            <div class="author">
               <p><b>AKASH KUMAR M.</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Seventh Edition</b>
            </div>
        </div>
    </body>
</html>
```
## Output:

![output](./coveroutput.png)

## Result:
The code is executed and the book cover is created successfully.
