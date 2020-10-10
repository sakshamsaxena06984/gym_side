# gym_side

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>saksham_gym</title>
    <style>
        /* style on whole body */
        body {
            color: white;
            margin: 0px;
            padding: 0px;
            
            font-family: 'Rubik', sans-serif;
            
             background: url('img/gym5.jpg')no-repeat center center/cover; 
            
        }

  /* create a NAVIGATION BAR */
        .left {
            display: inline-block;
            /* border: 2px solid rgb(31, 206, 55); */
            position: absolute;
            left: 9px;
            top: 13px;

        }

        .left img {
            width: 110px;
            height: 49px;
            border-radius: 25px;
            /* filter: invert(-98%); */
            filter: invert(-98);
        }

        .mid {
     
            display: block;
            width: 32%;
            margin: -13px auto;
            padding: -10px 24px;
            border: 4px solid rgb(66, 65, 66);
            border-radius: 8px;
        }

        .right {
            position: absolute;
            right: 1px;
            top: 1px;
            /* border: 2px solid rgb(22, 21, 21); */
            border-radius: 6px;

        }

        .navbar {
            display: inline-block
        }

        .navbar li {
            color: powderblue;
            display: inline-block;
            font-size: 22px;
            background-color: rgb(66, 65, 66);
        }

        .navbar li a {
            color: white;
            text-decoration: none;
            padding: 28px 8px;

        }
     /* style on navigation bar ,when we click on */
        .navbar li a:hover,
        .navbar li a.active {
            /* color: white; */
            color: cornsilk;
            text-decoration: underline;
        
        }

        .left div {
            text-align: center;
        }

        .bts {
            margin: 0px 9px;
            background-color: rgb(78, 74, 74);
            color: cornsilk;
            padding: 2px 22px;
            border-radius: 10px;
            cursor: pointer;
            background: url('img/gym5.jpg');
        }

        .bts:hover {
            color: blueviolet;
        }

        .container {
            border: 2px solid #f8f8f8;
            width: 33%;
            margin: 98px 99px;
            padding: 94px 15px;
            border-radius: 16px;
        }

        .fromgroup input {
            text-align: center;
            width: 33%;
            color: whitesmoke;
            margin: 1px 123px;
            padding: 1px 34px;
            border: 1px solid black;
            border-radius: 8px;
            background: url('img/gym5.jpg');
        }

        .container h1 {
            text-align: center;
            font-family: 'Rubik', sans-serif;

            background-color: silver;

        }


  /* styling on button */
        .container button {
            display: block;

            text-align: center;
            width: 47%;
            color: whitesmoke;
            margin: 1px 123px;
            padding: 1px 34px;
            border: 1px solid black;
            border-radius: 8px;
        }
        }
    </style>
</head>

<body>
 
    <header class="header">
        <!-- left part of my gym -->
        <div class="left">
            <img src="img/gym2.jpg" alt="erroe">
            <div>saksham</div>


        </div>
        <!-- mid(NAVIGATION) part of my gym -->
        <div class="mid">

            <ul class="navbar">

                <li><a href="#">home</a></li>
                <li><a href="#">warking</a></li>
                <li><a href="#">gym_center</a></li>
                <li><a href="#">contact</a></li>
            </ul>
        </div>
        <!-- seraching box in right part -->
        <div class="right">

            <button class="bts">cell_us_now</button><button class="bts">email_us_now</button>
        </div>
    </header>
    <div class="container">
        <h1>join best gym in india</h1>
        <form action="noactionphp" class="formin">
            <div class="fromgroup">
                <input type="enter the name" class="text" placeholder="ENTER THE NAME">
            </div>
            <div class="fromgroup">
                <input type="enter the name" class="text" placeholder="ENTER THE P.no">
            </div>
            <div class="fromgroup">
                <input type="enter the name" class="text" placeholder="ENTER THE ADDRESS">
            </div>
            <button class="bts">submit</button>
        </form>
    </div>
</body>

</html>
