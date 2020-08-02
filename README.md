<!DOCTYPE html>

<html lang="en">

 

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <meta http-equiv="X-UA-Compatible" content="ie=edge">


    <style type="text/css">

        * {

            margin: 0;

            padding: 0;

        }

 

        .header {

            width: 100%;

            height: 58px;

            background-color: #191D3A;

        }

 

        .inner {

            width: 1000px;

            height: 58px;

            margin: 0 auto;

            clear: both;

        }

 

        .inner .logo {

            float: left;

            width: 225px;

            height: 44px;

            margin: 7px 0;

        }

 

        .header .nav {

            float: left;

            height: 58px;

        }

 

        .header .inner .navs #current {

            color: #E2E4ED;

            background-color: #252947;

        }

 

        .header .inner .navs a {

            float: left;

            width: 85px;

            height: 58px;

            border-left: 1px solid #252947;

            border-right: 1px solid #252947;

            color: #818496;

            text-decoration: none;

            text-align: center;

            line-height: 58px;

            font-size: 14px;

        }

 

        .header .inner .navs .joinus {

            margin: 12px 0 0 10px;

            height: 32px;

            width: 98px;

            border: 1px solid #3aca7a;

            border-radius: 3px;

            background-color: #38b774;

            color: #fff;

            text-align: center;

            line-height: 32px;

        }

 

        .header .inner .nav:hover {

            color: #fff;

        }

 

        .header .inner .navs .joinus:hover {

            background-color: green;

        }

 

        .header .inner .changelang {

            float: right;

            line-height: 58px;

            /*   padding-left:20px;  在盒子里改的话，若未设置盒子高宽，则会缩短内容的长度 ，比如原来

            自动分配给内容90px，但有了边距，则会自动分配70px，另外20px给了边距*/

            /* 在内容里改的话，相当于内容的外边距 */

 

 

        }

 

        .header .inner .changelang a {

            display: block;

            margin-right: 10px;

            float: left;

            color: #818496;

            text-decoration: none;

            text-align: center;

            font-size: 14px;

        }

 

        .header .inner .changelang .cn {

            color: #1F9574;

 

        }

 

        .header .inner .changelang a:hover {

            color: #1F9574;

        }

 

        /* banner */

        .banner {

            width: 100%;

 

        }

 

        /* content */

        .content {

 

            width: 1200px;

            margin: 10px auto;

 

        }

 

        /* .content li {

            list-style: none;

        } */

 

        /* 列表 */

        .content ul li {

            list-style: none;

            float: left;

            width: 218px;

            margin-right: 40px;

        }

 

        .content ul li  img { 

            width: 218px;

            height: 130px;

 

        }

 

        .content ul li h4 {

            text-align: center;

            line-height: 38px;

            font-size: 14px;

        }

 

        .content ul li .bf {

            text-align: center;

            height: 20px;

        }

 

        .content ul li a {

            color: green;

            font-size: 14px;

            text-decoration: none;

            background: url(imgs/sanjiaoxing.png) no-repeat right 7px;

            padding-right: 12px;

        }

    </style>

</head>

 

<body>

    <!-- 导航栏 -->

    <div class="header">

        <div class="inner">

            <div class="logo">

                <img src="imgs/logo.png" alt="">

            </div>

            <div class="navs">
