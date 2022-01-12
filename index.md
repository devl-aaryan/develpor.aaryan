<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FITNESS</title>
</head>
<lnik rel="stylesheet" href="css/style.css">
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap" rel="stylesheet">


    <style>
        /* CSS Reset     */
        body {
            color: white;
            margin: 0px;
            padding: 0px;
            background: url('project1/img/bg.jpg');
            font-family: 'Bebas Neue', cursive;
        }

        .left {
            /* border: 2px solid red; */
            display: inline-block;
            position: absolute;
            left: 9px;
            top: 5px;

        }

        .left img {
            width: 125px;
            filter: invert(100%);

        }

        .logotxt {
            text-align: center;
            font-size: 22px;
            /* line-height: 0px; */

        }

        .mid {
            /* border : 2px solid green; */
            display: block;
            width: 33%;
            margin: 12px auto;
        }

        .right {
            /* border: 2px solid yellow; */
            display: inline-block;
            position: absolute;
            right: 9px;
            top: 5px;

        }

        .navbar {
            display: inline-block;
        }

        .navbar li {
            display: inline-block;
        }

        .navbar li a {
            color: white;
            padding: 20px;
            text-decoration: none;
            font-size: 20px;
            box-sizing: border-box;
        }

        .navbar li a:hover,
        .navbar li a.active {
            text-decoration: underline;
            color: grey;
        }

        .btn {
            margin: 12px 15px;
            border: 3px solid rgb(8, 8, 8);
            /* background-color: rgb(151, 219, 112); */
            border-radius: 15px;
            cursor: pointer;
            font-family: 'Bebas Neue', cursive;


        }

        .btn:hover {
            text-decoration: underline;
            font-weight: bolder;
            font-size: 15px;
            background-color: rgb(243, 236, 165);

        }

        .btn2 {
            margin: 10px;
            font-family: 'Bebas Neue', cursive;
            border-radius: 10px;
            margin-left: 50px;
            cursor: pointer;
            background-color: black;
            font-size: 17px;
            width: 85%;
            color: white;
            padding: 8px;
        }

        .btn2:hover {
            background-color: rgb(176, 240, 176);
            font-size: 20px;
            text-decoration: underline;
            color: rgb(85, 71, 62);
            font-weight: bolder;
        }

        #call {
            padding: 13px;
        }

        #mail {
            padding: 13px;
        }

        .container {
            border: 2px solid white;
            margin: 90px 80px;
            padding: 35px 80px;
            width: 50%;
            border-radius: 25px;
        }

        .form-group input {
            text-align: center;
            display: block;
            width: 70%;
            border: 2px solid black;
            margin: 7px auto;
            padding: 5px;
            font-size: 15px;
            font-family: 'Bebas Neue', cursive;
            ;
        }
    </style>

    <body>
        <header class="header">
            <div class="left">
                <img src="project1/img/logo.png" alt="">
                <div class="logotxt">
                    sem~z Fitness
                </div>
            </div>
            <div class="mid">
                <ul class="navbar">
                    <li><a href="#" class="active">Home</a></li>
                    <li><a href="#">About us</a></li>
                    <li><a href="#">Fitness</a></li>
                    <li><a href="#">Contact us</a></li>
                </ul>
            </div>
            <div class="right">
                <button class="btn" id="call"> call us now </button>
                <button class="btn" id="mail"> Email us </button>

            </div>
        </header>
        <div class="container">
            <h1>
                Join the best gym of delhi now
            </h1>
            <form action="noaction.php">
                <div class="form-group">
                    <input type="text" name="" placeholder="Enter your name">
                </div>
                <div class="form-group">
                    <input type="text" name="" placeholder="Enter your age">
                </div>
                <div class="form-group">
                    <input type="text" name="" placeholder="Enter your address">
                </div>
                <div class="form-group">
                    <input type="text" name="" placeholder="Your contact (mail/phone)">
                </div>
                <button class="btn2">
                    submit
                </button>

            </form>

        </div>
    </body>

</html>
