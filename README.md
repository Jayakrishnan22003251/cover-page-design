# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Write your own steps here.
### Step 2:
Make changes in settings.py
### Step 3:
Now build a html code and use CSS for colours and effects.
### Step 4:
Then, run the server and take a screenshot of your book cover page.
## Code:
```
"The true sign of intelligence is not knowledge but imagination" 
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:rgb(240, 233, 234);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/image1.png);
            background-size: cover;
        }
            

        .insight{
            color: rgb(17, 255, 0);

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(222, 222, 222);
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
            color:orange;
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
                <hr style="color: rgb(243, 236, 237)">
            </div>
            <div class="booktitle">
                <h2>Applications of Artificial intelligence and Datascience </h2></div>
            <div class="subtitle">
                1.Predictive Analytics
            </div>
            <div class="subtitle">
                2.Recommender Systems
            </div>
            <div class="subtitle">
                3.Natural Language Processing (NLP)
            </div>
            <div class="subtitle">
                4.Image and Video Processing: 
            </div>
            <div class="subtitle">
                5.Cybersecurity
            </div>
            <div class="mypic">
                <img src="/static/images/image2.png" width="145" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: rgb(15, 151, 45);">
            </div>
            <div class="author">
               <p style="color: aqua;">
            <b> JAYAKRISHNAN L B L</b>
            </p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>First Edition</b>
            </div>
        </div>
    </body>
</html>
```

## Output:
![image](https://github.com/Jayakrishnan22003251/cover-page-design/assets/120232371/a5fb94a5-0278-424a-911f-c91a9a277285)

### Server Output:
![Screenshot 2023-05-17 223751](https://github.com/Jayakrishnan22003251/cover-page-design/assets/120232371/a9d3d487-58a3-422a-9006-175d314af9df)

### HTML Validator:
![image](https://github.com/Jayakrishnan22003251/cover-page-design/assets/120232371/30bffce7-5216-41d7-927a-55bdaccc8f1a)


## Result:
Book Cover Page created successfully.
