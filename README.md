//# javascript
// it's my javascript tutorial 
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
 <style>
 .logo{
    float: left;
    padding: 22px 20px;
    font-size: 24px;
    transition: 0.3s;
    
}
nav.black .logo {
    color: #fff;
}
 nav ul li {
    text-decoration: none;
    display: inline-block;
    padding: 20px;
    text-align: center;
    margin: 10px 10px ;
    transition: 0.3px;
     
    
}
nav ul li a{
    padding: 15px 22px;
}
nav ul {
    list-style: none;
    float: right;
    padding: 0;
    margin: 0;
    display: flex;
    font-size: 14px;
    
}

nav{
    position: ;
    margin: 0px;
    padding: 0px;
    width: 100%;
    height: 80px;
    box-sizing: border-box;
    transition: 0.5s;
    color: aliceblue;
    font-family: Gill Sans, sans-serif;
    font-weight: 700;
    background: rgba(0,0,0,0.5)
}
nav.black{
    background: rgba(0,0,0,0.8);
    height: 100px;
    padding: 10px 100px;
}

body{
     font-family: Gill Sans, sans-serif;
    text-transform: uppercase;
    height: 900px;
    background: url(art-creative-creativity-5836.jpg) center ;
    background-size: cover;
    background-repeat: no-repeat;
}

nav.black ul li {
    color:#fff;
}
nav ul li a.active {
    background: rgba(0,0,0,0.6);
    color: #fff;
    border-radius: 6px;
    text-decoration: none;
}   


.center{
    text-align: center;
    height: 1000px;
    margin:0px;
    color: #ffffff;
    background: rgba(0,0,0,0.2)
    
}

h1{
    font-size: 100px;
    font-weight: 900;
    margin-top: 0px; 
    }
 </style>
    <script type="text/javascript">
    $(widow).on('scroll', function()){
            if($(window).scrollTop()) {
                    $('nav').addClass('black');
    }
            else{
                $('nav').removeClass('black');
            }
                }
    </script>
</head>
<body>
    <div class="wrapper">
        <nav>
            <div class="logo">LOGO</div>
            <ul>
                <li><a href="#"></a>home</li>
                <li><a href="#"></a>about</li>
                <li><a href="#"></a>blog</li>
                <li><a href="#"></a>contact</li>
                <li><a class="active" href="#">Log in</a></li>
            </ul>
        </nav>
        
    </div>
    <div class="center">
        <br><br><br><br><br><br><br><br><br><br>
        <h1>PEXELS</h1>
        <h2>SUBTITLE</h2>
        </div>
</body>    
</html>
