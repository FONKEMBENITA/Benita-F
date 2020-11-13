# Benita-F
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>nav-bar</title>
    <link rel="stylesheet" type="text/css" href="nav-bar.css">
</head>
<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


body {
    width: 100vw;
    min-height: 100vh;
    position: absolute;
    display: block;
    background: #fafafa;
}

html {
    font-family: Arial, Helvetica, sans-serif;
}


.nav-bar{
    position: relative;
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    background-color: teal;
    width: 100%;
    padding: 0 10vw;
    max-height: 65px;
}

ul{
    list-style: none;
    min-width: 70%;
    position: relative;
}

a{
    text-decoration: none;
    font-weight: bold;
}

.logo{
    text-align: center;
    padding: 20px;
    width: 70px;
    background-color: white;
    border: 4px teal;
    /*background: red url("path/to/file") center no-repeat;
    background-size: cover;*/
}

.logo a{
    color: teal;
    font-size: 40px;
    transition: color .4s;
}

.logo a:hover{
    color: orangered;
}

.menu{
    display: flex;
    justify-content: center;
    height: 70px;
}

.menu li{
    width: 100%;
    text-align: center;
    max-height: 67px;
    position: relative;
    display: inline-block;

}


.menu li:hover{
    background-color: orangered;
}

.menu li a, .menu li a:hover, .menu li a:active, .menu li a:focus{
    width: 100% !important;
    height: 63px !important;
    font-size: 20px;
    position: relative;
    display: inline-flex;
    justify-content: center;
    align-items: center;
    color: #f9f9f9;
    font-size: 15px;
    font-variant-caps: small-caps;
    text-align: center;

    transition: all 0.5s ease ;
    
}

.innermenu{
    display: none;
}

.menu > li:hover .innermenu{
    display:flex;
    flex-direction: column;
    background-color: orangered;
    border: 1px solid white;
    border-top: none;
    margin-top: 6px;
   
    padding: 0;
    position: relative;
    width: max-content;
    
}

.innermenu li{
    border-bottom: 1px solid lightsalmon;                                  ;
}

.innermenu li:hover{
    background-color: lightsalmon;
}

.innermenu li:hover a{
    color: teal;
    transition: color .4s;
    align-content: left;
    justify-content: left;
    text-align: left; 
}

.innermenu li:last-of-type{
    border-bottom: none;
}
</style>
<body>
    
    <div class="nav-bar">
       
        <div class="logo">
            <a href="LOGO"></a>
        </div>

        
        
        <ul class="menu">
            <li><a href="">Home</a></li>
            <li><a href="">About</a></li>
            <li><a href="">Services</a>
                <ul class="innermenu">
                    <li><a href="">Programming</a></li>
                    <li><a href="">Web-Development</a></li>
                    <li><a href="">App Development</a></li>
                    <li><a href="">Blogger</a></li>
                </ul>
            </li>
            <li><a href="">Contact</a></li>
        </ul>
    </div>
</body>
</html>












