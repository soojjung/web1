
<html>
<head>
    <meta charset="utf-8">
    <title>자기소개서</title>
    
    <style>
        a { color:black;
            text-decoration: underline;
            }

        body {background-color: mistyrose;
            margin: 5%;}

        h1 {text-align: center;
            margin-top: 10%;
            margin-bottom: 10%; 
            font-family: fantasy;
            font-size: 50px}

        img {width: 22%;
             margin : 5%;}

        .me {float: left;
             margin-left: 50px ;
             width: 230px;}
        
        #grid {/*border: 5px solid blue;*/
            display: grid;
            grid-template-columns: 1fr 1.5fr;
            }
        
        #grid ul {margin-top: 5%;}
        #grid li {font-family:cursive;
            font-size: 25px;
            padding: 5px;}
            
        h2 {font-size: 27px;
            font-family:monospace;
            text-align: center;
            margin-top: 20%;
            margin-bottom: 20%;
            }
        
        #photo {
            display: grid;
            grid-template-columns: 1fr 1fr 1fr;
            text-align: center;
        }

        #photo h3 {
            font-family:monospace;
            font-size: 20px;
            }

        #photo img {width: 70%;}

    </style>
    <!-- 
        a: selector ; color,text-decoration : declaration
    -->
</head>

<body>
    <h1>자기소개서</h1>
    <div id="grid">
        <img src="https://soojjung.github.io/images0/IMG_5155.jpg" class="me"> 
        <ul>
            <li>이름 : 정수진</li>
            <li>생년월일 : 1995.11.25 (27세)</li>
            <li>전공 : 응용수학통계학 <br> 복수전공 : 경제학</li>
            <li>SNS : <a href="https://www.instagram.com/soojjnng" target="_blank"
                title="click me!">instragram</a> </li>
        </ul>
    </div>

    <h2>likes :</h2>
    

    <div id="photo">
        <div >
            <img src="https://soojjung.github.io/images0/1.jpg">
            <h3>사진 찍기</h3>
        </div>
        
        <div >
            <img src="https://soojjung.github.io/images0/2.jpg">
            <h3>카페 투어</h3>
        </div>

        <div >
            <img src="https://soojjung.github.io/images0/3.jpg">
            <h3>힙합 공연</h3>
        </div>
    </div>
</body>

</html>
