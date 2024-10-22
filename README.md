<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chúc mừng sinh nhật Phương!!!</title>
</head>

<body>
    <!-- Cool Programming Projects -->
    <div class="fog_1"></div>
    <div class="fog_2"></div>
    <div class="fog_3"></div>
    <style>
        .fog_1 {
            position: fixed;
            width: 50vw;
            height: 10vw;
            top: 5vw;
            left: 5vw;
            border-radius: 50%;
            background-color: rgb(155, 195, 244);
            filter: blur(70px);
        }

        .fog_2 {
            position: fixed;
            width: 40vw;
            height: 5vw;
            top: 15vw;
            left: 25vw;
            border-radius: 50%;
            background-color: white;
            filter: blur(30px);
        }

        .fog_3 {
            position: fixed;
            width: 40vw;
            height: 10vw;
            top: 7vw;
            right: 5vw;
            border-radius: 50%;
            background-color: rgb(255, 252, 208);
            filter: blur(40px);
        }
    </style>
    <div class="container_main">
        <div class="container boy">
            <div class="head"></div>
            <div class="body"></div>
            <div class="right-hand"></div>
            <div class="left-hand"></div>
            <div class="right-leg"></div>
            <div class="left-leg"></div>
        </div>
        <div class="container girl">
            <div class="head"></div>
            <div class="body">
                <div class="first"></div>
                <div class="second"></div>
                <div class="third"></div>
            </div>
            <div class="right-hand"></div>
            <div class="left-hand"></div>
            <div class="right-leg"></div>
            <div class="left-leg"></div>
        </div>
        <div class=" msg-box box1">
            <P><strong>Quỳnh Anh:</strong> Em yêu, anh có chuyện muốn nói :))</P>
        </div>
        <div class=" msg-box box2">
            <P><strong>Phương:</strong> Hả?</P>
        </div>
        <div class=" msg-box box3">
            <P><strong>Quỳnh Anh:</strong> Humm...</P>
        </div>
        <div class=" msg-box box4">
            <P><strong>Quỳnh Anh:</strong> Hôm nay là ngày sinh nhật của em - sinh nhật đầu tiên của em có sự xuất
                hiện
                của anh. Chúc cô gái của anh luôn luôn xinh đẹp, luôn luôn xinh tươi giàu năng lượng, luôn luôn hạnh
                phúc nha... Sinh nhật năm nay, năm sau và nhiều năm về nữa, chúng ta sẽ ở bên nhau thật vui vẻ và
                hạnh
                phúc
                em nhé... Yêu em nhiều 💖💖💖️</P>
        </div>
    </div>
    <div class="road"></div>

    <div class="pyro">
        <div class="before"></div>
        <div class="after"></div>
    </div>
    <style>
        @import url('https://fonts.googleapis.com/css?family=Poppins:400,500,600,700,800,900');

        * {
            padding: 0;
            margin: 0;
        }


        body {
            width: 100%;
            height: 100vh;
            background: linear-gradient(rgb(247, 242, 143), white);
            overflow: hidden;

        }

        .pyro {
            opacity: 1;
            animation: body-background 10s;
        }


        .container_main {
            width: 360px;
            height: 600px;
            bottom: 0px;
            left: calc(50% - 180px);
            position: absolute;
        }

        body::before {
            content: "";
            position: absolute;
            width: 100%;
            height: 100%;
            animation: before-background 35s linear 14s infinite;

        }

        .road {
            height: 100px;
            width: 100%;
            background: linear-gradient(rgb(64, 51, 51), rgb(32, 32, 32));
            position: absolute;
            bottom: 0px;
            z-index: 1;

        }

        .container {
            width: 140px;
            height: 240px;
            position: absolute;
            bottom: 90px;

        }

        .boy {
            left: 50px;
        }

        .girl {
            right: 50px;
        }


        .boy .head,
        .girl .head {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            left: 24px;
            position: absolute;
        }

        .boy .head {
            border: 5px solid rgb(0, 0, 0);
        }

        .girl .head {
            border: 5px solid rgb(0, 0, 0);
        }

        .boy .body,
        .boy .left-hand,
        .boy .right-hand,
        .boy .left-leg,
        .boy .right-leg {
            width: 5px;
            height: 80px;
            background-color: black;
            position: absolute;
            border-radius: 40%;

        }

        .girl .left-hand,
        .girl .right-hand,
        .girl .left-leg,
        .girl .right-leg {
            width: 5px;
            height: 80px;
            background-color: rgb(0, 0, 0);
            position: absolute;
            border-radius: 40%;

        }

        .boy .body {
            left: 65px;
            top: 85px;

        }


        .girl .body {
            width: 40px;
            height: 80px;
        }

        .girl .body div {
            width: 5px;
            height: 75px;
            background-color: rgb(0, 0, 0);
            position: absolute;
            border-radius: 40%;
        }

        .girl .body .first {
            left: 63px;
            top: 92px;
            transform: rotate(11deg);
            transform-origin: top;
        }

        .girl .body .second {
            left: 63px;
            top: 92px;
            transform: rotate(-11deg);
            transform-origin: top;
        }

        .girl .body .third {
            height: 36px;
            left: 63px;
            top: 147px;
            transform: rotate(90deg);
        }


        .boy .left-hand,
        .girl .left-hand {
            left: 64px;
            top: 90px;
            transform: rotate(26deg);
            transform-origin: top;

        }

        .boy .right-hand,
        .girl .right-hand {
            left: 64px;
            top: 90px;
            transform: rotate(-26deg);
            transform-origin: top;

        }

        .boy .left-leg,
        .girl .left-leg {
            left: 64px;
            top: 163px;
            transform: rotate(23deg);
            transform-origin: top;

        }

        .boy .right-leg,
        .girl .right-leg {
            left: 64px;
            top: 163px;
            transform: rotate(-23deg);
            transform-origin: top;
        }


        @keyframes before-background {
            0% {

                background: linear-gradient(rgb(255, 0, 242), white);
            }

            20% {
                background: linear-gradient(rgb(0, 195, 255), white);

            }

            40% {
                background: linear-gradient(rgb(38, 255, 0), white);

            }

            60% {
                background: linear-gradient(rgb(0, 4, 255), white);

            }

            80% {
                background: linear-gradient(rgb(229, 255, 0), white);

            }

            100% {
                background: linear-gradient(rgb(255, 0, 0), white);

            }

        }

        @keyframes before-opacity {
            0% {
                opacity: 0;
            }

            1% {
                opacity: 1;
            }

            100% {
                opacity: 1;
            }

        }

        @keyframes body-background {
            0% {
                opacity: 1;
            }

            1% {
                opacity: 0;
            }

            100% {
                opacity: 0;
            }

        }

        .msg-box {
            width: 250px;
            height: 100px;
            border: 3px solid black;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 10px;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
            font-size: 20px;
            font-weight: 500;

            border-radius: 15px;
        }

        .msg-box p {
            text-align: center;
        }

        .box1 {
            position: absolute;
            left: -150px;
            top: 150px;
            opacity: 0;
            animation: box-animation 2s linear 1 1s forwards;

        }

        .box2 {
            position: absolute;
            right: -100px;
            width: 180px;
            top: 200px;
            height: 50px;
            opacity: 0;
            animation: box-animation 1s linear 1 3.5s forwards;
        }

        .box3 {
            position: absolute;
            left: -150px;
            top: 200px;
            height: 50px;
            opacity: 0;
            animation: box-animation 1.75s linear 1 5.5s forwards;
        }

        .box4 {
            width: 500px;
            height: 270px;
            position: absolute;
            left: -350px;
            top: -25px;
            opacity: 0;
            animation: status-animation 7s linear 1 8s forwards;
        }

        @media screen and (max-width: 600px) {
            .box1 {
                left: 5px;
                top: 150px;
            }

            .box2 {
                right: 5px;
                width: 180px;
                top: 200px;
            }

            .box3 {
                left: 5px;
                top: 200px;
                height: 50px;
            }

            .box4 {
                width: 350px;
                height: 300px;
                left: 3px;
                font-size: 18px;
                top: -50px;
            }

            .road {
                height: 70px;
            }

            .container {
                bottom: 60px;
            }

        }

        @keyframes status-animation {
            0% {
                opacity: 0;
            }

            10% {
                opacity: 1;
            }

            100% {
                opacity: 1;
            }
        }

        @keyframes box-animation {
            0% {
                opacity: 0;
            }

            10% {
                opacity: 1;
            }

            90% {
                opacity: 1;
            }

            100% {
                opacity: 0;
            }

        }

        /* pháo hoa */
        .pyro>.before,
        .pyro>.after {
            position: absolute;
            width: 7px;
            height: 7px;
            pointer-events: none;
            z-index: 99999999;
            border-radius: 50%;
            box-shadow: -120px -218.66667px blue, 248px -16.66667px #00ff84, 190px 16.33333px #002bff, -113px -308.66667px #ff009d, -109px -287.66667px #ffb300, -50px -313.66667px #ff006e, 226px -31.66667px #ff4000, 180px -351.66667px #ff00d0, -12px -338.66667px #00f6ff, 220px -388.66667px #99ff00, -69px -27.66667px #ff0400, -111px -339.66667px #6200ff, 155px -237.66667px #00ddff, -152px -380.66667px #00ffd0, -50px -37.66667px #00ffdd, -95px -175.66667px #a6ff00, -88px 10.33333px #0d00ff, 112px -309.66667px #005eff, 69px -415.66667px #ff00a6, 168px -100.66667px #ff004c, -244px 24.33333px #ff6600, 97px -325.66667px #ff0066, -211px -182.66667px #00ffa2, 236px -126.66667px #b700ff, 140px -196.66667px #9000ff, 125px -175.66667px #00bbff, 118px -381.66667px #ff002f, 144px -111.66667px #ffae00, 36px -78.66667px #f600ff, -63px -196.66667px #c800ff, -218px -227.66667px #d4ff00, -134px -377.66667px #ea00ff, -36px -412.66667px #ff00d4, 209px -106.66667px #00fff2, 91px -278.66667px #000dff, -22px -191.66667px #9dff00, 139px -392.66667px #a6ff00, 56px -2.66667px #0099ff, -156px -276.66667px #ea00ff, -163px -233.66667px #00fffb, -238px -346.66667px #00ff73, 62px -363.66667px #0088ff, 244px -170.66667px #0062ff, 224px -142.66667px #b300ff, 141px -208.66667px #9000ff, 211px -285.66667px #ff6600, 181px -128.66667px #1e00ff, 90px -123.66667px #c800ff, 189px 70.33333px #00ffc8, -18px -383.66667px #00ff33, 100px -6.66667px #ff008c;
            -moz-animation: 1s bang ease-out infinite backwards, 1s gravity ease-in infinite backwards, 5s position linear infinite backwards;
            -webkit-animation: 1s bang ease-out infinite backwards, 1s gravity ease-in infinite backwards, 5s position linear infinite backwards;
            -o-animation: 1s bang ease-out infinite backwards, 1s gravity ease-in infinite backwards, 5s position linear infinite backwards;
            -ms-animation: 1s bang ease-out infinite backwards, 1s gravity ease-in infinite backwards, 5s position linear infinite backwards;
            animation: 1s bang ease-out infinite backwards, 1s gravity ease-in infinite backwards, 5s position linear infinite backwards;
        }

        .pyro>.after {
            -moz-animation-delay: 1.25s, 1.25s, 1.25s;
            -webkit-animation-delay: 1.25s, 1.25s, 1.25s;
            -o-animation-delay: 1.25s, 1.25s, 1.25s;
            -ms-animation-delay: 1.25s, 1.25s, 1.25s;
            animation-delay: 1.25s, 1.25s, 1.25s;
            -moz-animation-duration: 1.25s, 1.25s, 6.25s;
            -webkit-animation-duration: 1.25s, 1.25s, 6.25s;
            -o-animation-duration: 1.25s, 1.25s, 6.25s;
            -ms-animation-duration: 1.25s, 1.25s, 6.25s;
            animation-duration: 1.25s, 1.25s, 6.25s;
        }

        @-webkit-keyframes bang {
            from {
                box-shadow: 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white;
            }
        }

        @-moz-keyframes bang {
            from {
                box-shadow: 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white;
            }
        }

        @-o-keyframes bang {
            from {
                box-shadow: 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white;
            }
        }

        @-ms-keyframes bang {
            from {
                box-shadow: 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white;
            }
        }

        @keyframes bang {
            from {
                box-shadow: 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white, 0 0 white;
            }
        }

        @-webkit-keyframes gravity {
            to {
                transform: translateY(200px);
                -moz-transform: translateY(200px);
                -webkit-transform: translateY(200px);
                -o-transform: translateY(200px);
                -ms-transform: translateY(200px);
                opacity: 0;
            }
        }

        @-moz-keyframes gravity {
            to {
                transform: translateY(200px);
                -moz-transform: translateY(200px);
                -webkit-transform: translateY(200px);
                -o-transform: translateY(200px);
                -ms-transform: translateY(200px);
                opacity: 0;
            }
        }

        @-o-keyframes gravity {
            to {
                transform: translateY(200px);
                -moz-transform: translateY(200px);
                -webkit-transform: translateY(200px);
                -o-transform: translateY(200px);
                -ms-transform: translateY(200px);
                opacity: 0;
            }
        }

        @-ms-keyframes gravity {
            to {
                transform: translateY(200px);
                -moz-transform: translateY(200px);
                -webkit-transform: translateY(200px);
                -o-transform: translateY(200px);
                -ms-transform: translateY(200px);
                opacity: 0;
            }
        }

        @keyframes gravity {
            to {
                transform: translateY(200px);
                -moz-transform: translateY(200px);
                -webkit-transform: translateY(200px);
                -o-transform: translateY(200px);
                -ms-transform: translateY(200px);
                opacity: 0;
            }
        }

        @-webkit-keyframes position {

            0%,
            19.9% {
                margin-top: 10%;
                margin-left: 40%;
            }

            20%,
            39.9% {
                margin-top: 40%;
                margin-left: 30%;
            }

            40%,
            59.9% {
                margin-top: 20%;
                margin-left: 70%;
            }

            60%,
            79.9% {
                margin-top: 30%;
                margin-left: 20%;
            }

            80%,
            99.9% {
                margin-top: 30%;
                margin-left: 80%;
            }
        }

        @-moz-keyframes position {

            0%,
            19.9% {
                margin-top: 10%;
                margin-left: 40%;
            }

            20%,
            39.9% {
                margin-top: 40%;
                margin-left: 30%;
            }

            40%,
            59.9% {
                margin-top: 20%;
                margin-left: 70%;
            }

            60%,
            79.9% {
                margin-top: 30%;
                margin-left: 20%;
            }

            80%,
            99.9% {
                margin-top: 30%;
                margin-left: 80%;
            }
        }

        @-o-keyframes position {

            0%,
            19.9% {
                margin-top: 10%;
                margin-left: 40%;
            }

            20%,
            39.9% {
                margin-top: 40%;
                margin-left: 30%;
            }

            40%,
            59.9% {
                margin-top: 20%;
                margin-left: 70%;
            }

            60%,
            79.9% {
                margin-top: 30%;
                margin-left: 20%;
            }

            80%,
            99.9% {
                margin-top: 30%;
                margin-left: 80%;
            }
        }

        @-ms-keyframes position {

            0%,
            19.9% {
                margin-top: 10%;
                margin-left: 40%;
            }

            20%,
            39.9% {
                margin-top: 40%;
                margin-left: 30%;
            }

            40%,
            59.9% {
                margin-top: 20%;
                margin-left: 70%;
            }

            60%,
            79.9% {
                margin-top: 30%;
                margin-left: 20%;
            }

            80%,
            99.9% {
                margin-top: 30%;
                margin-left: 80%;
            }
        }

        @keyframes position {

            0%,
            19.9% {
                margin-top: 10%;
                margin-left: 40%;
            }

            20%,
            39.9% {
                margin-top: 40%;
                margin-left: 30%;
            }

            40%,
            59.9% {
                margin-top: 20%;
                margin-left: 70%;
            }

            60%,
            79.9% {
                margin-top: 30%;
                margin-left: 20%;
            }

            80%,
            99.9% {
                margin-top: 30%;
                margin-left: 80%;
            }
        }
    </style>




</body>

</html>
