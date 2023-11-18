# Ex.06 Book Front Cover Page Design
## Date:
28/10/23

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:

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
            color:rgba(255, 255, 255, 0.562);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(cover\ harry.jpg);
            background-size: cover;
        }
        .insight{
            color: rgba(255, 255, 255, 0.359);

        }
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(255, 255, 255);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'times new roman', times new roman, times new roman;
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
            color: rgb(255, 255, 255);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            color: white;
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
                EXPECTO PATROM
            </div>
            <div class="hrstyle">
                <hr style="color: rgba(255, 255, 255, 0.879);">
            </div>
            <div class="booktitle">
                <h1>HARRY POTTER</h1></div>
            <div class="subtitle">
                Harry Potter is a series of seven fantasy novels written by British author J. K. Rowling. The novels chronicle the lives of a young wizard, Harry Potter, and his friends Hermione Granger and Ron Weasley, all of whom are students at Hogwarts School of Witchcraft and Wizardry
            </div>
            <div class="mypic">
                <img src="MY PHOTO.jpg" width="130" height="155" alt="">
            </div>
            <div class="id">
                <hr style="color: rgba(255, 255, 255, 0.476);">
            </div>
            <div class="author">
               <p><b>VIJAY KUMAR V R</b></p>
            </div>
            <div class="ed">
                <b>FIRST EDITION  SEASON</b>
            </div>
        </div>
    </body>
</html>

```










## OUTPUT:


![cover output](https://github.com/VRVijaykumar123/cover/assets/133218255/a17559d4-ad82-4c06-ba07-7fcd2760d888)









## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
