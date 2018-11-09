#Murtada Arkan
##html

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>FikraCamps</title>
    <link href="https://fonts.googleapis.com/css?family=Playfair+Display|Source+Sans+Pro" rel="stylesheet">
    <link rel="stylesheet" href="assets/index.css">
    
    </head>

<body>
<div id="container">
    <header><img src="assets/pepsi.png" alt="logo">
    </header>
        <section id="content">
            <div id="recent_links">
                    <h4>Recent Links</h4>
                <article> 
                    
                    <div>
                        <img src="https://unsplash.it/150/150" alt="picture">
                    </div>
                    <div>
                        <h3>title</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis rerum quia atque odio aut iste laborum adipisci nemo, praesentium nisi odit alias sequi sed voluptates illo fugiat itaque numquam ducimus?</p>
                        <time datetime="2018-07-07">july 7th 2018</time>
                        </div>

   
                    </article>
                <article> 
                    <div>
                    <img src="https://unsplash.it/150/150" alt="picture">
                    </div>
                    <div>
                    <h3>title</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis rerum quia atque odio aut iste laborum adipisci nemo, praesentium nisi odit alias sequi sed voluptates illo fugiat itaque numquam ducimus?</p>
                    <time datetime="2018-07-07">july 7th 2018</time>
                    </div>
 
    
            </article>
            <article> 
                <div>
                <img src="https://unsplash.it/150/150" alt="picture">
                </div>
                <div>
                <h3>title</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis rerum quia atque odio aut iste laborum adipisci nemo, praesentium nisi odit alias sequi sed voluptates illo fugiat itaque numquam ducimus?</p>
                <time datetime="2018-07-07">july 7th 2018</time>
                </div>
 
    
                </article>
            </div>
            <div id="most_viewed">
                <h4>Most Viewed</h4>
                <div>
                    <img src="https://unsplash.it/300/300" alt="picture">
                </div>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Qui maiores voluptate, veritatis, temporibus cumque deleniti nemo atque cupiditate error iste consectetur officiis sunt magni. Voluptates molestias dolore laboriosam error provident!
                </p>
                
                
                <div>
                    <img src="https://unsplash.it/300/300" alt="picture">
                </div>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Qui maiores voluptate, veritatis, temporibus cumque deleniti nemo atque cupiditate error iste consectetur officiis sunt magni. Voluptates molestias dolore laboriosam error provident!
                    </p>
                <div>
                    <img src="https://unsplash.it/300/300" alt="picture">
                </div>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Qui maiores voluptate, veritatis, temporibus cumque deleniti nemo atque cupiditate error iste consectetur officiis sunt magni. Voluptates molestias dolore laboriosam error provident!
                    </p>
            </div>
    </section>
</div>
    

<script src="index.js"></script>   
</body>
</html>
```
##css

```
*{
    padding: 0px;
    margin: 0px;
}
#container{
    width: 80%;
    margin: auto;
}

#content{
    display: flex;
}
#content #recent_links article{
    display: flex;
    flex-grow: 2;
    
}

article > div{
    padding: 0px 0px 0px 10px;
position: relative;
}

article{
    margin-bottom: 15px;
}

article h3{
    font-family: 'Playfair Display', serif;
    text-transform: capitalize;
}
article p{
    font-family: 'Source Sans Pro', sans-serif;
}

article time{
color: blue;
font-family: 'Source Sans Pro', sans-serif;
position: absolute;
bottom: 0px;
left: 10px;
}

#content #most_viewed{
    flex-grow: 1;
    flex-basis: 600px
}
#recent_links h4{
     margin-left: 10px;
 }

 #most_viewed div{
    position: absolute;
    margin-bottom: 50px;
    }
#most_viewed p{
    position: relative;
    
}
```

##result
![](screenshot (8).png)
