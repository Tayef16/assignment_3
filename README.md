# assignment_3
#HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    

    <div class="container">
        <div class="header">
            <img src="picture/logo.png" width="200">
            <h1>RANNABARI</h1>
        </div>
        <div class="menu">
            <ul>
                <li><a href="">Home</a></li>
                <li><a href="">Chinese</a></li>
                <li><a href="">Deshi</a></li>
                <li><a href="">Indian</a></li>
                <li><a href="">Thai</a></li>
            </ul>
        </div>
        <div class="content">
            <div class="row">
                <!--Column Start-->>
                <div class="coloumn_3">
                    <div class="single_blog">
                        <img src="picture/image1 (1).jpg" width="250">
                        <h1>Blog Title Goes Here</h1>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Id officia ipsum possimus nisi blanditiis quasi.</p>

                        <div class="row">
                            <div class="co_2">
                                <p>10/12/2024</p>
                            </div>
                            <div class="col_2"></div>
                            <a href="details.html" class="read_more">Read More</a>
                        </div>
                    </div>
                </div>
                <!--Column End-->

                <!--Column Start-->>
                <div class="coloumn_3">
                    <div class="single_blog">
                        <img src="picture/image1 (1).jpg" width="250">
                        <h1>Blog Title Goes Here</h1>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Id officia ipsum possimus nisi blanditiis quasi.</p>

                        <div class="row">
                            <div class="co_2">
                                <p>10/12/2024</p>
                            </div>
                            <div class="col_2"></div>
                            <a href="details.html" class="read_more">Read More</a>
                        </div>
                    </div>
                </div>
                <!--Column End-->>

                <!--Column Start-->>
                <div class="coloumn_3">
                    <div class="single_blog">
                        <img src="picture/image1 (1).jpg" width="250">
                        <h1>Blog Title Goes Here</h1>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Id officia ipsum possimus nisi blanditiis quasi.</p>

                        <div class="row">
                            <div class="co_2">
                                <p>10/12/2024</p>
                            </div>
                            <div class="col_2"></div>
                            <a href="details.html" class="read_more">Read More</a>
                        </div>
                    </div>
                </div>
                <!--Column End-->>

            </div>
            
        </div>
        <div class="footer">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quia modi doloribus sapiente quod ipsum nihil eligendi impedit, 
            perferendis quos sed! Fugiat quisquam reiciendis fuga molestiae ab perferendis repellat, tempore culpa?</p>
        </div>
        

    </div>


</body>
</html>



#CSS


body{
    margin: 0;
    padding: 0;
    font-size: 16px;
}

div {
    overflow: hidden;
    box-sizing: border-box;
}

img{
    max-width: max-content;
}

.container {
    width: 1000px;
    margin-left: auto;
    margin-right: auto;
}

.menu {
    background-color: #0f1e0a;
    padding: 15px;

}

.menu ul {
    list-style: none;
    padding: 0;
    margin: 0;
}

.menu ul li {
    float: left;
}

.menu ul li a {
    display: block;
    padding: 10px 15px;
    text-decoration: none;
    color: #fff;
}

.menu ul li a:hover {
     color: yellow;
     background-color: rgb(0, 142, 19);
     border-radius: 10px;
}

.content{
    padding: 15px 0px;

}

.coloumn_3{
    width: 33.3333333333333333%;
    float: left;
    padding-left: 15px;
    padding-right: 15px;
}

.single_blog{
    padding: 15px;
    border-radius: 15px;
    border: 2px solid #ddd;
}

.footer {
    background-color: #0f1e0a;
    padding: 15px;
    color: white;

}
