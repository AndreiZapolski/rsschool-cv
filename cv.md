1.**Name:**
Andrei Zapolski

2.**Contacts:**

* Num: 8029 2839549
* Mail: andreii.zapolskii@gmail.com

3.**About Me:**

For the last year I have been very interested in the topic of programming. I studied HTML and CSS on my own. I tried to master JavaScript. I have an idea about REACT, I watched the course on YouTube.

4.**Skills:** 

HTML and CSS

5.**Example of work:**

*html:*

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie-edge">
    <title>Tesla</title>
    <link href="https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
<div class="bg">
<header class="header">
    <a class="logo" href="#">tesla</a>
</header>
<main class="content">
    <section class="item">
    <header class="item-header">
        <h1 class="item_title">Model S</h1>
       <img src="./images/model-s.png" alt="tesla s">
    </header>
    <ul class="list">
        <li class="list-item">17” capacitive touchscreen</li>
        <li class="list-item">Automatic keyless entry</li>
        <li class="list-item">Traffic-aware cruise control</li>
    </ul>
    <footer class="item-footer">
        <p class="price">$575 /mo</p>
        <button class="button">ORDER</button>

    </footer>
    </section>

    <section class="item item-alt">
        <header class="item-header">
            <h1 class="item_title">Model X</h1>
            <img src="./images/model-x.png" alt="tesla s">
        </header>
        <ul class="list">
            <li class="list-item">Digitally controlled motors</li>
            <li class="list-item">Falcon Wing rear doors</li>
            <li class="list-item">Dual Motor All-Wheel Drive</li>
        </ul>
        <footer class="item-footer">
            <p class="price">early 2016</p>
            <button class="button">RESERVE</button>
    
        </footer>
        </section>

</main>
</div>
</body>
</html>
```
*css:*

```
*{
    padding: 0;
    margin: 0;
    box-sizing:border-box;
}
html{
    display: flex;
    flex-direction: column;
    min-height: 100%;
}
body {
    display: flex;
    flex-direction: column;
    flex-grow: 1;
    font-family: Lato;
    background-image: radial-gradient(circle at 50% 50%, white, #d7dbdf);
}
.bg{
    flex-grow: 1;
    background: url(./images/model-bg.png) center bottom no-repeat;
    background-size: contain;
}
.header{
    margin: 24px 0 17px;
    padding: 0 18px;
    display: flex;
    justify-content: flex-end;
}
.logo{
    background: url('logotesla.png') no-repeat 0 0;
    background-size: contain;
    display: inline-block;
    width: 150px;
    height: 25px;
    text-decoration: none;
    text-indent: -99999px;
}
.content{
    display: flex;
    justify-content: center;
}
.item{
    background: white;
    padding-bottom: 36px;
    width: 290px;
    color: #60697d;
    position: relative;
}
.item:not(.item-alt){
    z-index: 1;
    right: -17px;
}
.item-header{
    text-align: center;
    background-color: #f8f9f9;
    padding: 22px 0 20px;
    margin-bottom: 20px;
}
.item_title{
  display: flex;
  flex-direction: column;
  align-items: center;
  font-family: Lato;
  font-size: 30px;
  margin-bottom: 17px;
}
.item_title::after{
    content: '';
    display: inline-block;
    width: 28px;
    height: 2px;
    opacity: 0.3;
    background-color: #60697d;
    margin-top: 14px;
}
.list{
    list-style: none;
    text-align: center;
    margin-bottom: 23px;
}
.list-item{
    margin-bottom: 13px;
    font-size: 14px;
    
}
.list-item:last-child{
    margin-bottom: 0;
}
.item-footer{
    text-align: center;
}
.item-footer::before{
    content: '';
    display: inline-block;
    width: 28px;
    height: 2px;
    opacity: 0.3;
    background-color: #60697d;
    margin-bottom: 18px;
}
.price{
    font-size: 24px;
    margin-bottom: 23px;
}
.button{
    width: 126px;
    height: 36px;
    border-radius: 18px;
    background-color: #ea525c;
    border: 0;
    font-size: 14px;
    color: white;
}
.item-alt{
    color: white;
    opacity: 0.95;
    background-color: #73787d;
    left: -17px;
    top: 44px;
}
.item-alt .item-header{
    background-color: #656a72;
}
.item-alt .item_title:after{
background: white;
opacity: 0.3;
}
.item-alt .item-footer::before{
    background: white;
    opacity: 0.3; 
}
.item-alt .button{
    background-color: #37406c;
}
```

6.**Work experience:**

I have no experience in this area. I created several pages while watching video tutorials on YouTube. I showed an example of one of the works in the form of the code above.

7.**Education:**

I have no education in this area. I am an economist manager.

8.**English:**

School level.
