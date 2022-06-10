# WebSite3
 <!DOCTYPE html>
<html lang="en">
    <head> <!--header START-->
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" contend="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <title>Nisanur GÜNEŞ</title>
        
        <link rel="stylesheet" href="Site.css">
    </head>

    <body>
        <header id="header">
            <div class="header">
                <div class="container">
                    <div class="header-navbar">
                   <!-- <h2>Blog</h2>-->
                </div>
                <div class="header-menu">
                    <ul>
                        <li><a href="#">Blog</a></li>
                        <li><a href="#">Özgeçmiş</a></li>
                        <li><a href="#">Yetenekler</a></li>
                        <li><a href="#"></a></li>
                    </ul>
                </div>
                <h1><span class="first-letter">B</span></h1>
                <h3>olog</h3>
                
            </div>
            
            </div>
        </header> <!--header BİTİŞ-->
        <section id="about">
            <div class="about">
                <div class="container">
                <div class="about-title">
                   <h2>ABOUT</h2> 
                
                </div>
                <div class="about-content">
                    <div class="about-img">
                        <img src="about1.jpg" al="" width="300" height="250">
                   
                    <div class="about-text">
                        <h4>Blog</h4>
                        <div id="asteriks">
                            <i class="fas fa-asterisk"></i>
                        </div>
                        </div>
                </div>
                
</div>
                
                   <p>Bilgisayarlar; anakart, ekran kartı, işlemci, RAM gibi parçalardan oluşmakta.
                    <br>Ancak bu parçalardan en önemlisi işlemci. Bir bilgisayarın ana parçası işlemcidir.
                    <br> İşlemcilerin çalışma prensibi 1 ve 0 sayılarına dayanır.</p>
                
              
            
        </section>


    
    

    </body>
</html>
////////////////////////////////////////////////
CSS


@import url('https://fonts.googleapis.com/css2?family=Kalam&family=Poppins:ital,wght@1,400;1,500&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Kalam:wght@400;700&family=Poppins:ital,wght@1,400;1,500&display=swap');

*,
*::before,
*::after{
    margin: 0;
    padding:0;
    box-sizing:border-box ;
    border: 0;
}
a,
a:link,
a:visited{
    text-decoration: none;
    outline: none;
    border: none;
}
ul,
li{
    list-style: none;
    margin:0;
    padding: 0;
}
section,
span,
p{
    margin: 0;;
    padding: 0;
    outline: none;
    border: none;

}

.container{
    max-width: 1170px;
    margin: 0 auto;
    padding:0 15px;



}

.header{
    background-image: url(cicek.jpg);
    background-position: center;
    background-size: cover;
    background-attachment: fixed;
    height: 100vh;
    
}
.header-navbar{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 5px 0;
}

ul{
    display: flex;
}
li{
    margin-left: 27px;

}
li:first-child{
    margin-right: 70px;
}
a{
    color:black;
    font-weight: bold;
    font-size: 20px;
}
.header-text{
    position: absolute;
    top:50%;
    left:50%;
    transform: translateX(-50%);
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;

}
h1{
    font-size: 5.3rem;
    font-weight: 45;
    line-height: 0.4;
    letter-spacing: 2px;
    font-family: 'Arial, Helvetica, sans-serif',cursive;
    color: rgb(42, 3, 3);
}
.first-letter{
    font-size: 10.3;
    font-family: 'Arial, Helvetica, sans-serif',cursive;
    color: rgb(42, 3, 3);
}
h3{
    margin-bottom: 25px;
    font-size: 22px;
}
.about{
    margin-bottom: 150px;
}
.about-title{
    margin: 60px 0;

}

.about-title h2{
    width: 100%;
    text-align: center;
    margin: 0 auto;
    color:rgb(42, 3, 3);
    font-size: 30px;
    font-weight: 600;

}
.about-content{
   
    align-items: center;
    justify-content: space-around;
}
.about-img{
    width: 40%;
    display: flex;
}
.about-img img{
    width: 100%;
    height:100%;
    object-fit: cover;
    
}
.about-text{
    width: 40%;

}
h4{
    margin-bottom: 25px;
    text-align: center;
    font-size: 50px;
    color:black;
    font-family: 'Lucida Sans Unicode', cursive;
    letter-spacing: 0.5rem;
    font-weight: 100;
    
}
#asteriks{
    color: red;
    margin-bottom: 50px ;
    text-align: center;
}
.about-text p{
    font-size: 100px;
    text-align: center;
    color:red;
}


