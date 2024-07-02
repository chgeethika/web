## PROGRAM:
home.html
```
<!DOCTYPE html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1 {
            color: radium;
            font-size: 55px;
            font-family: cursive;
            position: absolute;
            top: 50%;
        }

        body {
            background-color: rgb(201, 198, 19);
            margin: 0;
        }

        .navbar ul {
            list-style-type: none;
            background-color: rgb(255, 81, 0);

        }
        .navbar a{
         color:black;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:50px;
        top:-95px;
        
        }

        .navbar a:hover {
            background-color: rgb(230, 173, 225);
            size: 60px;
            cursor: pointer;
        }

        .navbar li {
            float: right;
        }

        h2 {
            color: white;
            font-family: noto snans;
            font-size: 70px;
            background-color: rgb(255, 81, 0);
        }

        footer {

            background-color: black;
            height: 30px;
            bottom: 0;
            width: 100%;
            color: white;
            position: absolute;

        }

        header {
            background-color: rgb(255, 81, 0);
            height: 10vh;
            width: 100%;
            color: white;
        }

        header h2 {
            position: absolute;
            color: navy;
            margin-top: 3px;
            margin-left: 10px;
        }

        .first,
        .second,
        .third {
            font-size: 50px;
            margin-left: 2px;
        }

        .second {
            color: rgb(43, 226, 104);
            text-align: center;
        }

        .third {
            text-align: center;
        }
        .first{
            margin-left:5px;
            font-size:36px;
        }
        .search input,
        button {
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color: rgb(192, 192, 192);
        }

        .d {
            position: absolute;
            top: 65%;
            font-size: 30px;
        }

        .search input {
            width: 18%;
            height: 30px;

        }

        .search button,
        .d button {
            color:white;
            background-color: rgb(22, 165, 222);
            padding: 15px;
            text-align: center;
        }

        .d button {

            margin-right: 500px;
            padding: 50px 70px 50px 70px;
            border-radius: 50px;
            border-color: none;
        }

        #joinus:hover {
            cursor: pointer;
            color: rgb(5, 20, 15);
            background-color: rgb(215, 249, 250);
        }

        .login form {
            position: absolute;
            right: 100px;
            top: 30%;
            margin: 20px;
            box-sizing: border-box;
            border-color: rgb(105, 62, 7);
            background-color: rgba(25, 23, 20, 0.6);
            padding: 150px 150px 350px 150px;
        }

        .login form button {
            background-color: rgb(22, 165, 222);
            margin-right: 200px;
            color: white;
            padding: 15px 15px 15px 15px;
            font-size: 25px;
            border-radius: 15%;
            width: 40%;
        }

        .login form h3 {
            color: rgb(13, 12, 12);
            position: absolute;
            top: 0%;
            padding: 10px 35px 10px 35px;
            background-color: rgb(248, 250, 250);
            text-align: center;
            margin-left: 50px;


        }

        .login form input {
            height: 35px;
            border: none;
            border-bottom: 2px solid lightblue;
            font-family: Arial, Helvetica, sans-serif;
            color: white;
            font-size: 25px;
            background: transparent;
        }

        .login ::placeholder {
            color: white;
            opacity: 1;
        }

        .login form h4 {
            position: absolute;
            top: 55%;
            color: white;
            margin-left: 25px;
            font-size: 25px;
        }

        .login form .Signup {
            position: absolute;
            top: 70%;
            color: white;
            margin-left: 35px;
        }

        .login form .Signup b a {
            text-decoration: none;
            color: lightblue;
            margin-left: 50px;
            font-size: 25px;
        }

        .login form h5 {
            position: absolute;
            top: 73%;
            color: white;
            margin-left: 85px;
            font-size: 25px;
        }
        .login form .image {
            position: absolute;
            top: 85%;
            margin-left: 100px;

        }

        .d p {
            font-family: Georgia, 'Times New Roman', Times, serif;
        }
    </style>
</head>

<body>
    <header>
        <h2>NEW INNOVATIONS</h2>
    </header>
    <nav class="navbar">

        <ul>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="product.html">Products</a></li>
            <li><a href="people.html">People</a></li>
            <li><a href="home.html">Home</a></li>
        </ul>
    </nav>
    <div class="search"><input type="text" placeholder="Enter to Search">
        <button>Search</button>
    </div>
    <h1>
        <div class="first">"Stronger together: Building software through community."</div>
        <div class="third">Root your success with Tech Tree.<br> </div>
    </h1>
    <div class="d">
        <p> &nbsp;"Good websites are like crystal clear lakes-they allow users to see straight 
        to the bottom and navigate effortlessly."</p>
        <button id="joinus">Join Us</button>
    </div>
    <div class="login">
        <form>
            <h3>Login Here</h3>
            <input type="text" placeholder="Username or Email"><br><br>
            <input type="password" placeholder="Password"><br><br><br>
            <button>Login</button>
            <h4>Don't have an account</h4><br>
            <div class="Signup"><b><a href="">Sign up</a></b> here</div>
            <h5>Login with</h5>
            <div class="image">
                <img src="1.png" width="25px">
                <img src="2.jpg" width="25px">
                <img src="3.jpg" width="25px">
                
            </div>
        </form>
    </div>
    <footer>
        Designed and Developed by GEETHIKA
    </footer>

</body>

</html>
```
people.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1 {
            color: radium;
            font-size: 55px;
            font-family: cursive;
            position: absolute;
            top: 50%;
        }

        body {
            background-color: rgb(201, 198, 19);
            margin: 0;
        }

        .navbar ul {
            list-style-type: none;
            background-color: rgb(255, 81, 0);

        }
        .navbar a{
         color:black;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:50px;
        top:-95px;
        
        }

        .navbar a:hover {
            background-color: rgb(230, 173, 225);
            size: 60px;
            cursor: pointer;
        }

        .navbar li {
            float: right;
        }

        h2 {
            color: white;
            font-family: noto snans;
            font-size: 70px;
            background-color: rgb(255, 81, 0);
        }

        footer {

            background-color: black;
            height: 30px;
            bottom: 0;
            width: 100%;
            color: white;
            position: absolute;

        }

        header {
            background-color: rgb(255, 81, 0);
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:navy;
        margin-top: 3px;
        margin-left: 10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(22, 165, 222);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:silver;
        }
        .small
        {
           width:200px;
           height:200px;
           margin:10px;
        }
        .border{
        border-width:5px;
        border-color:purple;
        border-style:solid;
        border-radius:5px;
        }
        .cirpic{
            position:absolute;
            top:35%;
            margin-left: 55px;
        }
        .text{
            position:absolute;
            top:57%;
            margin-left: 25px;
            font-size: 20px;
            color: black;
            
        }
        .text2{
            position:absolute;
            top:60%;
            margin-left:60px;
            font-size: 18px;
            
        }
    
    </style>
</head>
<body>
    <header>
        <h2>NEW INNOVATIONS</h2>
        </header>
        <nav class="navbar">
        
        <ul>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="product.html">Products</a></li>
        <li><a href="people.html">People</a></li>
        <li><a href="home.html">Home</a></li>
        </ul>
        </nav>
        <div class="search"><input type="text" placeholder="Enter to Search">
            <button>Search</button></div>
        <div class="cirpic">
            <img class="small border" src="bhavana.jpg" width="500px">
            <img class="small border" src="geethika.jpg" width="500px">
            <img class="small border" src="sandhya.jpeg" width="500px">
            <img class="small border" src="vamsi.jpeg" width="500px" >
            <img class="small border" src="vasu.jpeg" width="500px">
            <img class="small border" src="vikki.jpeg" width="500px" >
        </div>
        <div class ="text">
            <table cellpadding="74">
                <tr div class="head">
                    <th>Bhavana</th>
                    <th>Geethika</th>
                    <th>sandhya</th>
                    <th>vamsilatha</th>
                    <th>Vasudha</th>
                    <th>Thrivikram</th>
                    
                </tr>
            </table>
        </div>
        <div class="text2">
            <table cellpadding="87">
                <tr>
                    <td>CEO</td>
                    <td>Director</td>
                    <td>Team lead</td>
                    <td>Asst.Director</td>
                    <td>Manager</td>
                    <td>Asst.Manager</td>
                </tr>
            </table>
        </div>
      
            <footer>
                Designed and Developed by Geethika
                </footer>
               
</body>
</html>
```
product.html
```
<!DOCTYPE html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1 {
            color: radium;
            font-size: 5px;
            font-family: cursive;
            position: absolute;
            top: 50%;
        }

        body {
            background-color: rgb(201, 198, 19);
            margin: 0;
        }

        .navbar ul {
            list-style-type: none;
            background-color: rgb(255, 81, 0);

        }
        .navbar a{
         color:black;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:50px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:lightblue;
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:white;
        font-family:notosans;
        font-size:60px;
        background-color:rgb(255, 72, 0);
        }
        footer{
        background-color:black;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
        background-color:rgb(255, 72, 0);
        height:10vh;
        width:100%;
        color:white;
        }
        header h2{
        position:absolute;
        color:navy;
        margin-top:3px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(22, 165, 222);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 30px;
            border-color:silver;
        }
        .contain{
                position: absolute;
                top:20%;
                width:1500px;
                height:850px;
                margin-left: 10px;
                background-color:grey;
                }
                .contain p b{
                    font-size: 40px;
                    padding-left: 50px;
                }
                .contain p{
                    font-size: 25px;
                    padding-left: 15px;
                    padding:5px 20px 0px 15px ;
                }
                .contain img{
                   margin-top: 10px;
                   padding-left: 10px;
                   padding:20px 20px 0px 20px;
                }
    </style>
</head>
<body>
    <header>
        <h2>NEW INNOVATIONS</h2>
        </header>
        <nav class="navbar">
        
        <ul>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="product.html">Products</a></li>
        <li><a href="people.html">People</a></li>
        <li><a href="home.html">Home</a></li>
        </ul>
        </nav>
        <div class="search"><input type="text" placeholder="Enter to Search">
            <button>Search</button></div>
            <div class="contain">
                <table >
                    <tr>
                        <td><img src="web browsers.jpg" height="150px" width="150px">
                            <p><b>Web browsers</b><br>
                                &nbsp;&nbsp;&nbsp;Web Development<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Platform
                        </p></td>
                        <td><img src="programming languages.png" height="150px" width="150px"><br>
                            <p><b>Programming Languages</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;C, Python<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;& Java languages
                        </p></td>
                        <td><img src="cloud services.png" height="150px" width="150px"><br>
                            <p><b>Cloud services</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Iaas, Saas <br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  & Dropbox
                        </p></td>
                        <td><img src="Email clients.png" height="150px" width="150px"><br>
                            <p><b>Email clients</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tools and mails<br>
                                
                        </p></td>
                        <td><img src="Security infrasreucture.jpg" height="150px" width="150px"><br>
                            <p><b>Security Intrastructure</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Firewall<br>
                                
                        </p></td>  
                    </tr>
                    <tr>
                        <td><img src="social media.jpg" height="150px" width="150px">
                            <p><b>Social Media</b><br>
                                &nbsp;&nbsp;&nbsp;   &nbsp;Handle & Create<br>
                                &nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Society
                        </p></td>
                        <td><img src="spread sheets.png" height="150px" width="150px"><br>
                            <p><b>Spreadsheets</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Microsoft Excel<br>
                               
                        </p></td>
                        <td><img src="machinelearning.jpg" height="150px" width="150px"><br>
                            <p><b>Machine learning</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Boston House  <br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Pricing Prediction Project
                        </p></td>
                        <td><img src="health app.png" height="150px" width="150px"><br>
                            <p><b>Health apps</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Headspace<br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; & Landsum
                        </p></td>
                        <td><img src="analytics.jpg" height="150px" width="150px"><br>
                            <p><b>Analytics</b><br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Heap, Amplitude <br>
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;& Adobe Analytics
                        </p></td>  

                    </tr>
                </table>
            </div>
            <footer>
                Designed and Developed by GEETHIKA
                </footer>
               
</body>
</html>
```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
         h1 {
            color: radium;
            font-size: 55px;
            font-family: cursive;
            position: absolute;
            top: 50%;
        }

        body {
            background-color: rgb(201, 198, 19);
            margin: 0;
        }

        .navbar ul {
            list-style-type: none;
            background-color: rgb(255, 81, 0);

        }
        .navbar a{
         color:black;
        text-decoration:none;
        padding:25px;
        display:flex;
        text-align:left;
        position: relative;
        font-size:50px;
        top:-95px;
        
        }
        .navbar a:hover{
         background-color:lightblue;
        size:60px;
        cursor: pointer;
        }
        .navbar li{
        float:right;
        }
        h2{
        color:white;
        font-family:notosans;
        font-size:60px;
        background-color: rgb(255, 81, 0);;
        }
        footer{

        background-color:black;
        height:30px;
        bottom:0;
        width:100%;
        color:white;
        position:absolute;
        
        }
        header
        {
            background-color: rgb(255, 81, 0);
        height:10vh;
        width:100%;
        color:black;
        }
        header h2{
        position:absolute;
        color:navy;
        margin-top:5px;
        margin-left:10px;
        }
        .search input{
            width:18%;
            height: 30px;

        }
        .search button{
            color:white;
            background-color: rgb(22, 165, 222);
            padding: 5px;
            text-align: center;
        }
        .search input,button{
            position: absolute;
            right: 12px;
            font-size: 18px;
            border-color:silver;
        }
        .line{
            position: absolute;
            top:43%;
        color:  darkblue;
            width:100%;
            size:5px;
        }
        .coform {
            background-color: white;
            top:43%;
        }
        .coform form{
            position: absolute;
            top:45%;
        }
        .coform form h3{
            font-size:50px;
        }
        .coform form input{
            margin-left: 10px;
            width:400px;
            height:45px;
            font-size: 40px;
        }
        .coform form textarea{
            margin-left: 10px;
            font-size: 40px;
           
        }
        .coform form button{
            position: absolute;
            background-color:  rgb(22, 165, 222);
            color:white;
            border-radius: 20%;
            margin-left: 10px;
            font-size: 40px;
        }
        #submit{
            left:0px;
            width:20%;
        }
        .vl{
            position:absolute;
            border-left: 3px solid darkblue;
            height: 450px;
            margin-left: 800px;
            top:44%;
        }
        #ci{
            font-size: 50px;
            margin-left: 30px;
        }
        .info{
            position:absolute;
            top:44.3%;
            font-size: 40px;
            background-color: grey;
            padding:70px 250px 95px 147px ;
            margin-left: 700px;
        }
        .coform form{
            background-color: grey;
            top:44.3%;
            margin-left: 0px;
            padding:0px 282px 50px 0px;
        }
    </style>
    </head>
    <body>
        <header>
            <h2>NEW INNOVATIONS</h2>
            </header>
            <nav class="navbar">
            
            <ul>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="product.html">Products</a></li>
            <li><a href="people.html">People</a></li>
            <li><a href="home.html">Home</a></li>
            </ul>
            </nav>
            <div class="search"><input type="text" placeholder="Enter to Search">
                <button>Search</button></div>
                <div class="line">
                    <hr color="darkblue">
            </div>
            <div class="coform">
            <form>
              <h3>&nbsp;Contact Us</h3>
              <input type="text" placeholder="Your Name"><br><br>
              <input type="text" placeholder="Your Email"><br><br>
              <textarea rows="5" cols="40" >Your Message
              </textarea><br>
              <button id="submit">Submit</button>
            </form>
        </div>
        <div class="info">
            <h3 id="ci" >Contact Information</h3><br>
            <b>Address: </b>Thota street,Atmakur,Nellore Dist.<br><br>
            <b>Email: </b>ch.geethika@gmail.com<br><br>
            <b>Phone: </b>7396736780
        </div>
        <div class="vl"></div>
    </div>
                <footer>
                    Designed and Developed by GEETHIKA
                    </footer>
                   
    </body>
    </html>
```


## OUTPUT:

![Screenshot (442)](https://github.com/chgeethika/web/assets/142209368/c9485535-a6e0-4267-9566-e8c75ec2164e)
![Screenshot (443)](https://github.com/chgeethika/web/assets/142209368/288bc724-16b2-4c58-bb7e-4187fc5f123d)
![Screenshot (444)](https://github.com/chgeethika/web/assets/142209368/57401f99-d7d6-46ff-9772-e00c76178b4b)
![Screenshot (445)](https://github.com/chgeethika/web/assets/142209368/3fdc8882-aa2e-4b92-9c13-ae2265271732)





