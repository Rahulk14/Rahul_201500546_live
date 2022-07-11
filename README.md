<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fat to Fit</title>
    <link href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="css/style.css">
    <style>
        body {
            color: black;
            margin-top: 0px;
            padding: 0px;
            background: url('image/img.jpg');
            height: 700px;
        }

        .left {
            display: inline-block;
            border: 2px solid green;
            position: absolute;
            left: 0px;
            top: 0px;
            height: 74px;
            width: 63px;
            background-color: crimson;
            /* color: aliceblue; */
        }

        .left div {
            font-family: 'Baloo Bhai 2', cursives;
            color: white;
            margin: -1px 16px;
            font-size: 40px;
        }


        .mid {
            display: block;
            width: 50%;
            margin: -8px 190px;
            border: 2px solid blueviolet;
        }

        .right {
            position: absolute;
            right: 42px;
            top: 22px;
            display: inline-block;
            border: 2px solid red;
        }

        .navbar {
            display: inline-block;
            position: relative;
        }

        .navbar li {
            display: inline-block;
            font-size: 23px;
        }

        .navbar li a {
            display: inline-block;
            text-decoration: none;
            color: white;
            padding: 27px 35px;
        }



        .btn {
            font-family: 'Baloo Bhai 2', cursives;
            margin: 0px 9px;
            background-color: white;
            /* border-radius: 9px; */
            color: red;
            padding: 0px 21px;
            font-size: 15px;
            cursor: pointer;
        }

        .btn:hover {
            background-color: rgb(226, 218, 232);
        }

        body {
            background-color: white;
        }
    </style>


</head>

<body>
    <header class="header">
        <div class="left">
            <div>R</div>
        </div>

        <div class="mid">
            <ul class="navbar">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Fitness Calculator</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </div>

        <div class="right">
            <button class="btn">Buy Rogan &#8594</button>
        </div>

    </header>

</body>

</html>
