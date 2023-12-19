# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### step 1:
Create different CSS styles for each HTML element.

### step 2:
Attach the CSS codes in the corresponding HTML file.

### step 3:
Publish the URL.

## Code:
### book.html code:
```html
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:rgba(241, 92, 92, 0.803);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Times New Roman',Garamond;
            background-image: url('from the fitzgeralds.jpg');
            background-size: cover;
        }
            

        .insight{
            color: rgb(223, 74, 41);

        }

        
        
        
        .author{
        
            display: inline;
            position: relative;
            color: white ;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'garmond';
            font-size: larger;
            text-align: center;
            position: relative;
            
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:15px;
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
            position: middle;
        }
        .mypic{
            position: relative;
            top: 151px;
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
            MD CREATIONS
            </div>
            
            <div class="booktitle">
                <h1>To the Mom</h1> 
              <h1>Who Made Me</h1>
              <h1>Who I Am</h1>
                </div>
            <div class="subtitle">
         __WITH LOVE MOHAMMAD FAIZAL S.K_
            </div>
            <div class="mypic">
                <img src="DSC_9987 copy.jpg" width="150" height="150" alt="">
            </div>
        </div>
    </body>
</html>
```

## Output:
![book](https://github.com/mohammadfaizal87/cover-page-design/assets/147139206/3ec513da-4fde-42f8-a580-49d66923802a)


## Result:
the program for designing book cover page using html and css is executed successfully.


