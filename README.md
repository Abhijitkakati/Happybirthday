<!DOCTYPE html>
<html lang="en" b:css='false' b:defaultwidgetversion='2' b:layoutsVersion='3' b:responsive='true' b:templateUrl='rockpool.xml' b:templateVersion='1.3.3' expr:dir='data:blog.languageDirection' expr:lang='data:blog.locale' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>>
<head >
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="title" content="Happy Birthday Website 2.0 | Aoudumber Bade">
    <meta name="github" content="https://github.com/Aoudumber-Bade">
    <title>HAPPY BIRTHDAY SONIA❤️</title>
    <!-- <link rel="stylesheet" href="style.css"> -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <script src="https://code.jquery.com/jquery-3.7.1.min.js" integrity="sha256-/JqT3SQfawRcv/BIHPThkBvs0OEvtFFmqPF/lYI/Cxo=" crossorigin="anonymous"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Coiny&family=Titan+One&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Nerko+One&family=Sriracha&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&display=swap');
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
:root{
    --color-pink: #feecea;
    --color-white: #fff;
    --color-black: #333;
    --color-text-pink: #ff7882;
    --color-heart: #F61F1F;
    --color-bg-letter: #fff8e4;
    --color-border: #DACCBF;
}
html{
    height: 100%;
}
body {
    position: relative;
    font-size: 16px;
    margin: 0;
    padding: 0;
    height: 100%;
    background-image:linear-gradient(var(--color-pink), var(--color-pink));
}
#wrapper{
    position: relative;
    background-color: transparent;
    background-image: linear-gradient(0deg, transparent 24%, rgba(255, 255, 255, 1) 25%, rgba(255, 255, 255, 1) 26%, transparent 27%, transparent 74%, rgba(255, 255, 255, 1) 75%, rgba(255, 255, 255, 1) 76%, transparent 77%, transparent), linear-gradient(90deg, transparent 24%, rgba(255, 255, 255, 1) 25%, rgba(255, 255, 255,1) 26%, transparent 27%, transparent 74%, rgba(255, 255, 255, 1) 75%, rgba(255, 255, 255, 1) 76%, transparent 77%, transparent);
    height:100%;
    background-size:80px 80px;
    overflow: hidden;
    z-index: 1;
}
.flag__birthday{
    display: flex;
    justify-content: space-between;
    transform: translateY(-200px);
    animation: translateYFlag 1.5s 2s forwards;
}
@keyframes translateYFlag{
    to{
        transform: translateY(-10px);
    }
}
.flag__birthday .flag__left{
    transform: rotate(-10deg) translate(-20px,30px);
}
.flag__birthday .flag__right{
    transform: rotate(10deg) translate(20px,30px) scaleX(-1);
}
.content{
    width: 100%;
    position: relative;
    display: flex;
    padding-top: 3rem;
}
.content .left, .content .right{
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.content .left{
    width: 40%;
}
.content .right{
    width: 60%;
}
.left .btn{
    transform: scale(0);
    animation: scaleCricle 2s 16s forwards ease-in-out;
}
#btn__letter{
    position: relative;
    margin-top: 30px;
    background-color: var(--color-text-pink);
    outline: none;
    padding: 5px 15px;
    font-size: 1rem;
    border-radius: 50px;
    border: 3px solid var(--color-black);
    font-family: "Sriracha", cursive;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    z-index: 2;
    transform: scale(1);
    transition: all .5s ease-in-out;
}
#btn__letter:active{
    transform: scale(0.7);
}
#btn__letter i{
    margin-left: 5px;
}
#btn__letter:hover{
    border-color: var(--color-heart);
    background-color: var(--color-heart);
    color: #fff;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
}

#btn__letter:hover i{
    animation: rotateHeart 1s infinite linear;
}
@keyframes rotateHeart{
    0%,50%, 100%{
        transform: rotate(0deg);
    }
    25%{
        transform: rotate(12deg);
    }
    75%{
        transform: rotate(-12deg);
    }
}
.title{
    position: relative;
    width: 100%;
    display: flex;
    justify-content: center;
    font-family: "Titan One", sans-serif;
    font-size: 3rem;
    flex-direction: column;
    perspective: 1000px;
}
.title .happy, .title .birthday{
    position: relative;
    text-shadow: 4px 4px var(--color-black), 
                -4px 4px var(--color-black), 
                4px -4px var(--color-black), 
                -4px -4px var(--color-black), 
                4px 8px 0 var(--color-black);
    font-weight: bold;
    display: flex;
    justify-content: center;
}
.title .happy{
    color: var(--color-white);
}
.title .happy span, .title .birthday span{
    transform: translateY(50px);
    opacity: 0;
    visibility: hidden;
    animation: txtTranslateY .5s var(--t) forwards;
}
@keyframes txtTranslateY{
    100%{
        transform: translateY(0);
        opacity: 1;
        visibility: visible;
    }
}
.title .birthday{
    color: var(--color-text-pink);
}

.title .hat{
    position: absolute;
    right: 45px;
    top: -350px;
    transform: rotate(-40deg);
    z-index: -1;
    animation: topHat 4s 7s forwards ease;
}
@keyframes topHat{
    20%, 30%{
        top: -30px;
        transform-origin: left;
        transform: rotate(-40deg);
    }
    35%, 100%{
        top: -30px;
        transform: rotate(0deg);
    }
}
.date__of__birth, .name{
    display: flex;
    justify-content:space-around;
    align-items: center;
    background-color: var(--color-text-pink);
    border-radius: 50px;
    margin-top: 20px;
    font-family: "Sriracha", cursive;
    
}
.date__of__birth{
    border: 3px solid var(--color-black);
    position: relative;
    transform: translateY(-100px);
    z-index: -1;
    opacity: 0;
    visibility: hidden;
    width: 0px;
    animation: dateOfBirth 5s 9s forwards;
}
@keyframes dateOfBirth{
    20%,40%{
        width: 0px;
        height: 0;
        transform: translateY(0px);
        opacity: 1;
        visibility: visible;
    }
    45%{
        transform: translateY(0px);
        opacity: 1;
        visibility: visible;
        width: 300px;
        height: 0px;
    }
    50%,100%{
        transform: translateY(0px);
        opacity: 1;
        visibility: visible;
        width: 300px;
        height: 50px;
    }
}
.name{
    position: absolute;
    padding: 0px 40px;
    bottom: -20px;
    border: 3px solid var(--color-black);
}
.date__of__birth span, .name span{
    font-weight: bold;
    margin: 0px 40px;
}
.date__of__birth span{
    font-size: 1.2rem;
}
.name span{
    font-size: 1.7rem;
}
.right .box__account{
    position: relative;
    transform: translateY(700px);
    animation: topBoxImage 8s 7s forwards ease-in;
}
@keyframes topBoxImage{
    to{
        transform: translateY(0);
    }
}
.content .right .image{
    position: relative;
    width: 400px;
    height: 400px;
    border-radius: 50%;
    overflow: hidden;
    display: flex;
    align-items: center;
    border: 6px solid var(--color-black);
}
.content .right .image img{
    width: 100%;
    object-fit: cover;

}
.cricle{
    position: absolute;
    top: 20px;
    right: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    transform: scale(0);
    animation: scaleCricle 3s 15s forwards ease-in-out;
}
@keyframes scaleCricle {
    0%{
        transform: scale(0);
    }
    10%{
        transform: scale(1.3);
    }
    20%{
        transform: scale(0.7);
    }
    30%,100%{
        transform: scale(1);
    }

}
.text__cricle{
    width: 100px;
    height: 100px;
    background-color: var(--color-text-pink);
    border-radius: 50%;
    border: 5px solid var(--color-black);
    display: flex;
    justify-content: center;
    align-items: center;
    animation: rotateCricle 5s linear infinite;
}
@keyframes rotateCricle{
    to{
        transform: rotate(360deg);
    }
}
.text__cricle span{
    top: 0%;
    left: 50%;
    position: absolute;
    color: var(--color-black);
    transform: rotate(calc(var(--i) * 24deg));
    transform-origin: 0 45px;
    font-family: "Sriracha", cursive;
    text-transform: uppercase;
    font-size: 0.7rem;
}
.fa-heart{
    color: var(--color-heart);
    filter: drop-shadow(0 0 3px var(--color-heart));
    animation: scaleHeart 1s infinite linear;
}
.cricle .fa-heart{
    position: absolute;
    transform: scale(0.85);
}
@keyframes scaleHeart{
    50%{
        transform: scale(1.2);
    }
}
.right .balloon_one{
    position: absolute;
    top: -70px;
    left: -70px;
    animation: balloon1 2s infinite linear;
}
@keyframes balloon1{
    0%, 50%,100%{
        transform-origin: bottom right;
        transform: rotate(0deg);
    }
    25%{
        transform-origin: bottom right;
        transform: rotate(3deg);
    }
    75%{
        transform-origin: bottom right;
        transform: rotate(-3deg);
    }
}
.right .balloon_two{
    position: absolute;
    top: 170px;
    right: -65px;
    z-index: -1;
    transform: rotate(10deg);
    animation: balloon2 2s infinite linear;
}
@keyframes balloon2 {
    0%,50%,100%{
        transform-origin: bottom left;
        transform: rotate(10deg);
    }
    25%{
        transform-origin: bottom left;
        transform: rotate(7deg);
    }
    75%{
        transform-origin: bottom left;
        transform: rotate(13deg);
    }
}

.decorate_star{
    position: absolute;
    transform: scale(0);
    background-color: var(--color-black);
    clip-path: polygon(0 50%, 35% 35%, 50% 0, 65% 35%, 100% 50%, 65% 65%, 50% 100%, 35% 65%);
    animation: scaleCricle 3s var(--t) forwards, 
            scaleStar 2s 16s infinite ease-in-out;
}
.decorate_star.star1{
    width: 20px;
    height: 20px;
    top: 75px;
    left: 300px;
}
.decorate_star.star2{
    width: 15px;
    height: 20px;
    top: 35px;
    right: 360px;
}
.decorate_star.star3{
    width: 14px;
    height: 14px;
    top: 290px;
    left: 630px;
}
.decorate_star.star4{
    width: 18px;
    height: 18px;
    bottom: 60px;
    left: 35px;
}
.decorate_star.star5{
    width: 16px;
    height: 18px;
    bottom: 140px;
    left: 500px;
}
@keyframes scaleStar {
    25%{
        transform: scale(0.8);
    }
    50%{
        transform: scale(1.1);
    }
}
.decorate_bottom{
    position: absolute;
    right: 0;
    bottom: -10px;
}
.decorate_flower--one{
    position: absolute;
    top: 250px;
    left: 50px;
    transform: scale(0);
    animation: scaleCricle 3s var(--t) forwards ease-in-out;
}
.decorate_flower--two{
    position: absolute;
    top: 225px;
    left: 540px;
    transform: scale(0);
    animation: scaleCricle 3s var(--t) forwards ease-in-out;
}
.decorate_flower--three{
    position: absolute;
    top: 150px;
    right: 235px;
    transform: scale(0);
    animation: scaleCricle 3s var(--t) forwards ease-in-out;
}
.smiley__icon{
    position: absolute;
    bottom: 180px;
    left: 600px;
    transform: scale(0);
    animation: scaleCricle 3s 15s forwards ease-in-out;
}


.box__letter{
    position: fixed;
    top: 0;
    left: 0;
    background-color: rgba(0,0,0,.5);
    width: 100%;
    height: 100%;
    z-index: 10;
    display: none;
}
.box__letter .letter__border{
    position: absolute;
    width: 55vw;
    height: 450px;
    background-color: var(--color-white);
    border-radius: 27px;
    padding: 17px;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    display: none;
}
.letter__border .close{
    position: absolute;
    right: -10px;
    top: -10px;
    width: 30px;
    height: 30px;
    background-color: var(--color-white);
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    box-shadow: rgba(99, 99, 99, 0.2) 0px 2px 8px 0px;
    cursor: pointer;
}
.letter__border .letter{
    width: 100%;
    height: 100%;
    background-color: var(--color-bg-letter);
    border-radius: 10px;
    padding-top: 15px;
}
.letter__border .letter .title__letter{
    text-align: center;
    font-family: 'Dancing Script', cursive;
    font-weight: bold;
    font-size: 2.4rem;
}
.title__letter .fa-solid{
    margin-left: 5px;
    font-size: 1.3rem;
}
.letter__border .letter .content__letter{
    position: relative;
    width: 100%;
    height: 100%;
    display: flex;
    padding-top: 1.5rem;
    padding-bottom: 70px;
}
.letter__border .letter .content__letter .left{
    position: relative;
    width: 50%;
    height: 100%;
    padding: 1.7rem;
    border-right: 3px solid var(--color-border);
}
.content__letter .left #heart__letter{
    opacity: 0;
    width: 100%;
}
#heart__letter.animationOp{
    animation: opacityHeart 1s 1s forwards;
}
@keyframes opacityHeart{
    to{
        opacity: 1;
    }
}
.content__letter .left .heart{
    position: absolute;
    opacity: 0;
}
.content__letter .left .heart.animation{
    animation: scaleHeartLetter 1s var(--t) infinite ease-in-out;
}
@keyframes scaleHeartLetter{
    0%{
        opacity: 1;
        transform: scale(0);
    }
    10%{
        opacity: 1;
        transform: scale(1.3);
    }
    20%{
        opacity: 1;
        transform: scale(0.7);
    }
    30%,100%{
        opacity: 1;
        transform: scale(1);
    }
    
}
.content__letter .left .heart_1{
    top: 90px;
    left: 30px;
}
.content__letter .left .heart_2{
    top: 20px;
    right: 70px;
}
.content__letter .left .heart_3{
    bottom: 50px;
    left: 145px;
}
.content__letter .left .heart_4{
    top: 140px;
    right: 35px;
}
.content__letter .right{
    position: relative;
    width: 50%;
}
.content__letter .right .love__img{
    opacity: 0;
    position: absolute;
    right: 20px;
    top: -100px;
}
.love__img.animationOp{
    animation: opacityHeart 1s 1s forwards;
}
.content__letter .right .text__letter{
    margin-top: 60px;
    padding: 20px 15px 10px 15px;
    font-family: 'Dancing Script', cursive;
    font-size: 1.3rem;
}
.content__letter .right #mewmew{
    position: absolute;
    bottom: 0;
    right: 0;
    opacity: 0;
}
#mewmew.animationOp{
    animation: opacityHeart 1s 1s forwards;
}


#copy {
    position: fixed;
    bottom: 12px;
    left: 50%;
    transform: translateX(-50%);
    font-size: 1rem;
}

#copy a {
    text-decoration: none;
    color: #191919d7;
}

#copy p {
    color: #ff3d5a;
    text-align: center;
    font-weight: 700;
    cursor: pointer;
}



@media screen and (max-width: 658px)   {

    .flag__birthday .flag__left {
        transform: rotate(-10deg) translate(-119px,3px);
    }

    .flag__birthday .flag__right {
        transform: rotate(10deg) translate(-106px,39px) scaleX(-1);
    }

    .content {
        width: 100%;
        position: relative;
        display: flex;
        flex-direction: column;
        justify-content: center;
        gap: 25px;
        align-items: center;
        padding-top: 2rem;
    }

    .title {
        position: relative;
        width: 100%;
        display: flex;
        justify-content: center;
        font-family: "Titan One", sans-serif;
        font-size: 1.5rem;
        letter-spacing: 8px;
        flex-direction: column;
        perspective: 1000px;
    }

    #btn__letter {
        position: relative;
        margin-top: 17px;
        width: 209px;
        background-color: var(--color-text-pink);
        outline: none;
        padding: 6px 4px;
        font-size: 1rem;
        border-radius: 50px;
        border: 3px solid var(--color-black);
        font-family: "Sriracha", cursive;
        display: flex;
        align-items: center;
        justify-content: center;
        cursor: pointer;
        z-index: 2;
        /* transform: scale(1); */
        transition: all .5s ease-in-out;
    }

    .cricle {
        position: absolute;
        top: 10px;
        right: -54px;
        display: flex;
        justify-content: center;
        align-items: center;
        transform: scale(0);
        animation: scaleCricle 3s 15s forwards ease-in-out;
    }

    .title .hat {
        position: absolute;
        right: -98px;
        top: -51px !important;
        transform: rotate(-40deg);
        z-index: -1;
        animation: topHat 4s 7s forwards ease;
    }

    .box__letter .letter__border {
        position: absolute;
        width: 90vw;
        height: 315px;
        background-color: var(--color-white);
        border-radius: 27px;
        padding: 17px;
        box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
        top: 50%;
        left: 50%;
        transform: translate(-50%,-50%);
        display: none;
    }

    .letter__border .letter {
        width: 100%;
        height: 100%;
        background-color: var(--color-bg-letter);
        border-radius: 10px;
        padding-top: 15px;
    }

    .letter__border .letter .title__letter {
        text-align: center;
        font-family: 'Dancing Script', cursive;
        font-weight: bold;
        font-size: 1.4rem;
    }

    .letter__border .letter .content__letter {
        position: relative;
        width: 100%;
        height: 100%;
        display: flex;
        padding-top: .7rem;
        padding-bottom: 70px;
    }

    .content__letter .right .text__letter {
        margin-top: -14px;
        padding: 20px 15px 10px 15px;
        font-family: 'Dancing Script', cursive;
        font-size: .8rem;
    }

    .content__letter .right .love__img {
        opacity: 0;
        position: absolute;
        right: 126px;
        top: 167px;
    }

    .love__img img {
 
            width: 84px;

    }

    .content .right .image {
        position: relative;
        width: 200px;
        height: 200px;
        border-radius: 50%;
        overflow: hidden;
        display: flex;
        align-items: center;
        border: 6px solid var(--color-black);
    }

    .name {
        position: absolute;
        padding: 0px 3px;
        bottom: -6px;
        border: 3px solid var(--color-black);
    }

    .name span {
        font-size: 1rem;
    }

    .right .balloon_one {
        position: absolute;
        top: 10px;
        left: -77px;
        animation: balloon1 2s infinite linear;
    }

    .right .balloon_one img{
        width: 76px !important;
    }
    .close {
        display: inline-block; /* Makes it behave like a button */
        padding: 10px 20px; /* Add some space inside the element */
        color: #fff; /* Text color */
        background-color: #f44336; /* Background color (red, for a close button) */
        border: none; /* Remove borders */
        border-radius: 5px; /* Add rounded corners */
        cursor: pointer; /* Show the pointer cursor on hover */
        font-size: 16px; /* Text size */
        transition: background-color 0.3s ease; /* Smooth background change */
    }
    
    .close:hover {
        background-color: #d32f2f; /* Slightly darker shade on hover */
    }
    


}
    </style>
</head>
<body>
    <div id="wrapper">
        <div class="flag__birthday">
            <img src="./images/1.png" alt="" width="350" class="flag__left">
            <img src="./images/1.png" alt="" width="350" class="flag__right">
        </div>
        <div class="content">
            <div class="left">
                <div class="title">
                    <h1 class="happy">
                        <span style="--t: 4s;">H</span>
                        <span style="--t: 4.2s;">a</span>
                        <span style="--t: 4.4s;">p</span>
                        <span style="--t: 4.6s;">p</span>
                        <span style="--t: 4.8s;">y</span>
                    </h1>
                    <h1 class="birthday">
                        <span style="--t: 5s;">B</span>
                        <span style="--t: 5.2s;">i</span>
                        <span style="--t: 5.4s;">r</span>
                        <span style="--t: 5.6s;">t</span>
                        <span style="--t: 5.8s;">h</span>
                        <span style="--t: 6s;">d</span>
                        <span style="--t: 6.2s;">a</span>
                        <span style="--t: 6.4s;">y</span>
                    </h1>
                    <div class="hat">
                        <img src="./images/hat.png" alt="" width="130">
                    </div>
                </div>
                <div class="date__of__birth">
                    <span></span>
                </div>
                <div class="btn">
                    <button id="btn__letter">
                        Click here Sonia
                        <i class="fa-regular fa-envelope"></i>
                    </button>
                </div>
            </div>
            <div class="right">
                <div class="box__account">
                    <div class="image">
                        <img src="./images/soniaa.jpg" alt="">
                    </div>
                    <div class="name">
                        <i class="fa-solid fa-heart"></i>
                        <span>Sonia</span>
                        <i class="fa-solid fa-heart"></i>
                    </div>
                    <div class="balloon_one">
                        <img width="100px" src="./images/balloon1.png" alt="">
                    </div>
                    <div class="balloon_two">
                        <img width="100px" src="./images/balloon2.png" alt="">
                    </div>
                </div>
                <div class="cricle">
                    <div class="text__cricle">
                        <span style="--i: 1;">h</span>
                        <span style="--i: 2;">a</span>
                        <span style="--i: 3;">p</span>
                        <span style="--i: 4;">p</span>
                        <span style="--i: 5;">y</span>
                        <span style="--i: 6;">-</span>
                        <span style="--i: 7;">b</span>
                        <span style="--i: 8;">i</span>
                        <span style="--i: 9;">r</span>
                        <span style="--i: 10;">t</span>
                        <span style="--i: 11;">h</span>
                        <span style="--i: 12;">d</span>
                        <span style="--i: 13;">a</span>
                        <span style="--i: 14;">y</span>
                        <span style="--i: 15;">-</span>
                    </div>
                    <i class="fa-solid fa-heart"></i>
                </div>
            </div>
        </div>
        <div class="decorate_star star1" style="--t: 15s;"></div>
        <div class="decorate_star star2" style="--t: 15.2s;"></div>
        <div class="decorate_star star3" style="--t: 15.4s;"></div>
        <div class="decorate_star star4" style="--t: 15.6s;"></div>
        <div class="decorate_star star5" style="--t: 15.8s;"></div>
        <div class="decorate_flower--one" style="--t: 15s;">
            <img width="20" src="./images/decorate_flower.png" alt="">
        </div>
        <div class="decorate_flower--two" style="--t: 15.3s;">
            <img width="20" src="./images/decorate_flower.png" alt="">
        </div>
        <div class="decorate_flower--three" style="--t: 15.6s;">
            <img width="20" src="./images/decorate_flower.png" alt="">
        </div>
        <div class="decorate_bottom">
            <img src="./images/decorate.png" alt="" width="100">
        </div>
        <div class="smiley__icon">
            <img src="./images/smiley_icon.png" alt="" width="100">
        </div>

        

        <div class="box__letter">
            <div class="letter__border">
                <div class="letter">
                    <div class="title__letter">
                    </div>
                    <div class="content__letter">
                        <div class="left">
                            <img  src="./images/sonaa.jpg" alt="" width="350" height="220">
                            <img class="heart heart_1" style="--t: 0.2s" width="20" src="./images/heart.png" alt="">
                            <img class="heart heart_2" style="--t: 0.4s" width="20" src="./images/heart.png" alt="">
                            <img class="heart heart_3" style="--t: 0.6s" width="20" src="./images/heart.png" alt="">
                            <img class="heart heart_4" style="--t: 0.8s" width="20" src="./images/heart.png" alt="">
                        </div>
                        <div class="right">
                            <div class="love__img">
                                <img src="https://media.giphy.com/media/m85llaN7ZkFIHtURiC/giphy.gif" alt="" width="220">
                            </div>
                            <div class="text__letter">
                                 <p></p>
                            </div>
                            <img id="mewmew" width="80" src="./images/mewmew.gif" alt="">
                        </div>
                    </div>
                </div>
                <div class="close">
                    <i class="fa-solid fa-xmark"></i>
                </div>
            </div>
        </div>
    </div>

   
</body>
<script>
    let datetxt = "5 April 1996";
    let datatxtletter = "My love. You are a very special girl. I always silently thank you for coming into my life. Today, I wish you all the best, lots of health, and lots of joy. I always hope we will celebrate many more birthdays like this together. Happy birthday to you.💕";
    let titleLetter = "To you";
    let charArrDate = datetxt.split('');
    let charArrDateLetter = datatxtletter.split('');
    let charArrTitle = titleLetter.split('');
    let currentIndex = 0;
    let currentIndexLetter = 0;
    let currentIndexTitle = 0;
    let date__of__birth = document.querySelector(".date__of__birth span");
    let text__letter = document.querySelector(".text__letter p");
    setTimeout(function(){
        timeDatetxt = setInterval(function(){
            if(currentIndex < charArrDate.length){
                date__of__birth.textContent += charArrDate[currentIndex];
                currentIndex++;
            }
            else{
                let i = document.createElement("i");
                i.className = "fa-solid fa-star"
                document.querySelector(".date__of__birth").prepend(i)
                document.querySelector(".date__of__birth").appendChild(i.cloneNode(true))
                clearInterval(timeDatetxt)
            }
        },100)
    },12000)

    var intervalContent;
    var intervalTitle;
    $("#btn__letter").on("click", function(){
        $(".box__letter").slideDown()
        setTimeout(function(){
            $(".letter__border").slideDown();
        },1000)
        setTimeout(function(){
            intervalTitle = setInterval(function(){
                if(currentIndexTitle < charArrTitle.length){
                    document.querySelector(".title__letter").textContent += charArrTitle[currentIndexTitle];
                    let i = document.createElement("i");
                    i.className = "fa-solid fa-heart"
                    document.querySelector(".title__letter").appendChild(i)
                    currentIndexTitle++;
                }
                else{
                    clearInterval(intervalTitle)
                }
            },100)
        },2000)
        setTimeout(function(){
            document.querySelector("#heart__letter").classList.add("animationOp");
            document.querySelector(".love__img").classList.add("animationOp");
            document.querySelector("#mewmew").classList.add("animationOp");
        },2800)
        setTimeout(function(){
            document.querySelectorAll(".heart").forEach((item)=>{
                item.classList.add("animation")
            })
        },3500)
        setTimeout(function(){
            intervalContent = setInterval(function(){
                if(currentIndexLetter < charArrDateLetter.length){
                    text__letter.textContent += charArrDateLetter[currentIndexLetter];
                    currentIndexLetter++;
                }
                else{
                    clearInterval(intervalContent)
                }
            },50)
        },6000)
    })
    $(".close").on("click", function(){
        clearInterval(intervalContent)
        document.querySelector(".title__letter").textContent = "";
        text__letter.textContent = "";
        currentIndexLetter = 0
        currentIndexTitle = 0
        document.querySelector("#heart__letter").classList.remove("animationOp");
        document.querySelector(".love__img").classList.remove("animationOp");
        document.querySelector("#mewmew").classList.remove("animationOp");
        document.querySelectorAll(".heart").forEach((item)=>{
                item.classList.remove("animation")
            })
        $(".box__letter").slideUp();
        $(".letter__border").slideUp();
    })
</script>
</html>
