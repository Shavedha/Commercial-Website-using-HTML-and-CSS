# Commercial-Website-using-HTML-and-CSS
## AIM
To create a Commercial Website using HTML and CSS
## ALGORITHM 
1. Create a html document with an .html extension
2. Create a css document with an .css extension 
3. In the html document include the main sections, navigation, and any interactive elements. 
4. Determine what content you need to include, such as text, images in the hmtl document
5. Use the Css document to determine how the webpage should look, like adding colors,styles,padding,box-sizing the whole document.
6. Save both the documents and visualise the website by launching the same.
## PROGRAM
### foodKa.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Foodka</title>
    <link rel="stylesheet" type="text/css" href="foodka.css">
</head>
<body style="background-color: rgb(244, 243, 239);">
    
    <nav>
        <h2 class="logo">Food<span>ka</span></h2>
        <ul>
            <li><a href = "#">Home</a></li>
            <li><a href = "#">About</a></li>
            <li><a href = "#">catalog</a></li>
            
        </ul>
        <a href="#" class="btn">ORDER NOW</a>   
    </nav>
        <div class="content">
            <img src="hdburg.png" style="float: right;height: 300px;">
            <p><b>Quality food </b><br> <B>Delivered !</B></p>
        </div>
        <abt style="font-family:Arial, Helvetica, sans-serif;font-size: 22px;line-height: 29px;">A hamburger (also burger for short) is a food,typically considered a sandwich,
            <br>consisting of one or more cooked patties of ground meat, usually beef, 
            placed<br> inside a sliced bread roll or bun. The patty may be pan fried, grilled, <br>smoked or flame broiled.</abt>
            <br>
        <br>
        <br>
        <a href="#" class="btn">GET STARTED</a>  
           <br>
            <br>
            <br>
            <br>
       <img src="ds3-removebg-preview.png" style="float: left;height: 300px;border: none;">
    <div class="content">
        <p style="white-space:pre-wrap;text-align: left;"><b> Traditional Vegetarian Food</b></p>
        
    </div>
       <abt style="font-family:Arial, Helvetica, sans-serif;font-size: 22px;line-height: 29px;">Vegetarian food is good for health and that's what we provide<br> here in FoodKa, as we focus on customers health before<br>
    money reaches the table </abt>
<br>
<br>
<br> 
<center>
    <a href="#" class="btn2">Order Veg Food</a></center>
   <div class="service">
        <div class="title">
         <center>   <h4>Our Happy Customers</h4></center>
         <img src="br3.png" style="float: left;">
        </div>
        <div class="box">
            <div class="card">
                
                <h5><b>Andrew Banks</b></h5>
                <div class="pra">
                   <p >"I dont always clop,but when I do,its because of food. Wow what great food has just
                    not let me leave the store until now for this very minute"
                   </p> 
                   <p style="text-align: center;">
                   </p>
                </div>
            </div>
            <div class="card">
                
                <h5>John Morrison</h5>
                <div class="pra">
                   <p >The food here is one of the human to eat but when I do,it's because of food.Wow what 
                    great food has just not let me to leave the store until now for this very minute.
                   </p> 
                   <p style="text-align: center;">
                     
                </p>
                </div>
            </div>
            
        </div>
    </div> 
    </body>
</html>
```
### foodKa.css
```

        span{
            color: gold;
        }
        nav{
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding-top: -2px;
            padding-left: 8%;
            padding-right: 8%;
        }
        .logo{
            color: black;
            font-size: 50px;
            letter-spacing: 1px;
            cursor: pointer;
        }
        nav ul li{
            list-style-type: none;
            display: inline-block;
            padding: 10px 25px;
        }
        nav ul li a{
            color:  black;
            text-decoration: none;
            font-weight: bold;
            text-transform: capitalize;
        }
        nav ul li a:hover{
            color: grey;
            transition: .4s;
        }
        .btn{
            background-color: orange;
            color: white;
            text-decoration: none;
            border: 2px solid transparent;
            font-weight: bold;
            padding: 10px 25px;
            border-radius: 30px;
            transition: transform .4s;
        }
        .btn:hover{
            transform: scale(1.2);
        }
        .btn2{
            background-color: black;
            color: yellow;
            text-decoration: none;
            border: 2px solid transparent;
            font-weight: bold;
            padding: 10px 25px;
            border-radius: 30px;
            transition: transform .4s;
        }
        .about{
            width: 100%;
            padding: 100px 0px;
            background-color: #191919;
        }
        .about img{
            height: 300px;
            float: left;
            
        }
        .about-text{
            width: 550px;
        
        }
        .main{
            width: 1130px;
            max-width: 95%;
            margin: 0 auto;
            display: flex;
            align-items: center;
            justify-content: space-around;
        }
        .about-text h5{
            color: black;
            letter-spacing: 2px;
            font-size:22px;
            margin-bottom: 25px;
            text-transform: capitalize;
        }
        .about-text p{
            color: black;
            letter-spacing: 1px;
            line-height: 29px;
            font-size: 18px;
            margin-bottom: 45px;
        }

        .menu{
            display: flex;
            justify-content: space-around;
            
        }
        a{
            color: black;
            font-size: 20px;
        }
        .content{
            color: black;
            font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-size: 50px;

        }
        .service{
            background: rgb(244, 243, 239);
            width: 100%;
            padding: 100px 10px;
        }
        .title h4{
            color: black;
            font-size: 50px;
            width: 1130px;
            
            text-align: center;
        }
        .box{
            display: flex;
            justify-content: center;
            align-items: center;
            height: 400px;
            
            float: right;
            overflow: hidden;
    background-color: rgb(213, 153, 0);
        
        }
        .card{
            height: 230px;
            width: 335px;
            padding: 20px 35px;
            background: whitesmoke;
            
            margin: 15px;
            position: relative;
            overflow: hidden;
            text-align: center;
        }
        h5{
            color: gold;
            font-size: 25px;
            margin-bottom: 15px;
        }
        .pra p{
            color: burlywood;
            font-size: 16px;
            line-height: 27px;
            margin-bottom: 25px;
         }
         .col h4{
            font-size: 1.2rem;
            color: black;
            position: relative;
            margin-bottom: 25px;
         }
         .col h4::before{
            content: "";
            position: absolute;
            height: 2px;
            width: 50px;
            left: 0;
            bottom: -8px;
            background: var(--main-color);
         }
         .col ul li:not(:last-child){
            margin-bottom:10px;
        }
```

## OUTPUT
![image](https://github.com/Shavedha/Commercial-Website-using-HTML-and-CSS/assets/93427376/0cdf536e-4ac2-4957-a597-d06552fe5ff9)

## RESULT
Thus a commercial website is created using HTML and CSS
