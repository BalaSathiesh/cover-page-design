# cover-page-design
AIM: To design a static web site for a book cover page.

DESIGN STEPS: Step 1: Clone the github repository and create a django admin interface

Step 2: Write HTML and CSS for designing book cover page and execute them .

Step 3: Validate the HTML and CSS code.

Step 4: Publish the website in the given URL.

## Code:
cover.html:

<!DOCTYPE html>
<html lang="en">
    <head>
        <title> EASY WAY TO LEARN JAPANESE</title>
        <style>
        h1{
           color:red;
        }
         .bookpage{
             width: 400px;
             height: 650px;
             background-color: yellow;
             background-position: center;
             margin-left: auto;
             margin-right: auto ;
             padding: 20px;
             background-image: url("cover.jpg");
             background-size: cover;
             background-repeat: no-repeat;

         }
         .toptext{
             color:purple;
             padding-left: 10px;
             font-size: 14px;
             font-family: Arial, Helvetica, sans-serif;

         }
         .tophr{
             color:#e36f2f;
              width: 180px;
         }
         hr{
             color:#e36f2f;

         }
         .booktitle{
             font-family: Arial, Helvetica, sans-serif;
             padding: 10px 10px 0px 10px;
             display: flex;
            align-items: center;
            justify-content: center;
  margin-right: 10px;
  margin-left: 10px;
  font-size: 20px;
         }
         .author{
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: inline;
             font-size: 24px;
             position:relative;
             line-height: 20px;


         }
         .sub-text {
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: flex;
             line-height: 5px;

  margin-right: 10px;
  margin-left: 10px;

  font-size: 14px;
  }

.footer {
  color:orange;
  padding-top: 180px;
}
.image {
    color:white;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
  margin-right: 20px;
}
.bottomhr {
    color:#e36f2f;
              width: 400px;

}
img {
    width: 90px;
    height: 100px;
    margin-right: 20px;
    vertical-align: bottom;
}
.edition {
    color:#e36f2f;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
 line-height:bottom;

}


        </style>
        </head>
            <body>
                <div class="bookpage">

                    <div class="toptext">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BEGINNER FRIENDLY</div>
                    <div class="tophr"><hr></div>
               <div class="booktitle"><h1>EASY WAY TO LEARN JAPANESE</h1></div>
               <h3 class="sub-text">Learn Japanese in 30 days</h3>
                    <h3 class="sub-text">written by Dr. Balasathiesh</h3>
                    <div class="footer">
                        <h2 class="edition">&nbsp;&nbsp;first
Edition&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <img src="IMG-20221119-WA0000.jpg" alt="Author"></h2>

                        <div class="bottomhr"><hr></div>
                    <div class="author"><h3>&nbsp;&nbsp;Balasathiesh &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</h3></div>

                </div>
                </div>

            </body>


</html>

## Output:
![Screenshot (40)](https://github.com/BalaSathiesh/cover-page-design/assets/128462891/aa587519-5c32-4dda-a97a-8d196a6e630c)
![Screenshot (39)](https://github.com/BalaSathiesh/cover-page-design/assets/128462891/2e22aaa6-fe52-45b3-b820-607603757810)



## Result:
program executed successfully
