
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arm News || Home</title>
    <link rel="stylesheet" href="Home.css">
    <link href="https://cdn.jsdelivr.net/npm/remixicon@3.5.0/fonts/remixicon.css" rel="stylesheet">
    <link rel="shortcut icon" href="image/HF-logo.png" type="image/x-icon">
    <script async src="Home.js"></script>
</head>
<body>
    <style>
        *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: serif;
}
html{
    font-size: 10px;
}
body{
    height: 260vh;
    z-index: 1;
    background: linear-gradient(180deg, rgb(255, 0, 0) , rgb(255, 255, 255));
}
#HF-hed1{
    width: 100%;
    height: 15vh;
    display: flex;
    z-index: 16;
    position: fixed;
    align-items: center;
    transition: width 0.4s , height 0.4s;
    background-color: rgb(255, 0, 0);
}
#HF-logo{
    position: relative;
    left: 5%;
}
#HF-logo a{
    color: rgb(255, 255, 255);
    font-family: fantasy;
    font-size: 4.5rem;
    position: relative;
    cursor: pointer;
    text-decoration: none;
    left: 0%;
    transition: color 0.3s;
}
#HF-logo:hover{
    color: rgb(211, 0, 0);
}
#HF-open{
    font-size: 2rem;
    position: absolute;
    left: 92%;
    color: white;
    background-color:  rgb(187, 0, 0);
    width: 3%;
    height: 6vh;
    display: flex;
    align-items: center;
    transition: background 0.4s , color 0.4s;
    justify-content: center;
    cursor: pointer;
}
#HF-open:hover{
    background: rgb(255, 255, 255);
    color:  rgb(187, 0, 0);
}
#HF-opened{
    position: fixed;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    width: 90%;
    background-color: rgb(187, 0, 0);
    height: 86vh;
    z-index: 15;
    top: 100vh;
    transition: left 0.4s;
    left: 5%;
}
#HF-reklam{
    width: 90%;
    height: 20vh;
    position: relative;
    left: 5%;
    top: 18vh;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 2rem;
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    text-align: center;
    background-color: rgb(223, 0, 0);
}
#all-1{
    width: 90%;
    position: relative;
    background-color: rgb(235, 0, 0);
    left: 5%;
    height: 159vh;
    top: 21vh;
}
#alls{
    width: 31.5%;
    position: relative;
    cursor: pointer;
    left: 1%;
    top: 2vh;
    height: 50vh ;
    background-size: cover;
    box-shadow: 0px 0px 10px 0.5px black;
}
#alls:hover > #als-text{
    color: rgb(255, 255, 255);
}
#als-text{
    width: 100%;
    opacity: 0.7;
    height: 14vh;
    position: relative;
    display: flex;
    align-items: center;
    flex-direction: column;
    text-align: center;
    justify-content: center;
    top: 36vh;
    background-color: rgb(131, 117, 117);
}
#t1{
    font-size: 2rem;
    position: relative;
    transition: color 0.2s, text-shadow 0.3s;
    font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
#t2{
    font-size: 1.2rem;
    transition: color 0.2s, text-shadow 0.3s;
    position: relative;
    width: 92%;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
#new{
width: 80%;
height: 60vh;
display: flex;
align-items: center;
justify-content: center;
flex-direction: column;
background-color: red;
}
#new a{
    color: white;
    text-decoration: none;
    font-size: 3rem;
    margin-top: 2.5%;
    text-shadow: 0px 0px 11px black;
}




  .search{
    display: flex;
    position: relative;
    width: 16.5%;
    left: 62%;
  }

  #searchik {
    list-style-type: none;  
    padding: 0;
    margin: 0;
    z-index: 10;
    position: fixed;
    left: 0%;
    width:  100%;
    /* top: 15vh; */
    top: -35vh;
    text-align: center;
    z-index: 15;
    
  }
  
  #searchik li a {
    border: 1px solid #ddd;
    margin-top: -1px; /* Prevent double borders */
    background-color: #f6f6f6;
    position: relative;
    z-index: 888;
    height: 6vh;
    text-decoration: none;
    text-align: center;
    font-size: 1.2rem;
    color: black;
    display: flex;
    align-items: center;
    justify-content: center;
  }
  
#but{
    border: 0;
    width: 25%;
    left: 85%;
    background-color: transparent;
    position: relative;
    font-size: 1.6rem;
    cursor: pointer;
    border-bottom: 0px solid black;
    
}
#searchik li a:hover:not(.header) {
    background-color: #eee;
  }

#searchbar {
    width: 0%;
    position: relative;
    font-size: 16px;
    border: 0;
    left: 85%;
    height: 6vh;
    background-color: transparent;
    outline: 0;
    border-bottom: 1px solid rgb(0, 0, 0);
  }
#mug{
    z-index: -5;
    width: 100%;
    height: 100vh;
    opacity: 0.75;
    position:fixed;
    top: 0vh;
    transition: background 0.2s;
    background: transparent;
}
#serchi{
    position: absolute;
    font-size: 2.5rem;
    left: 85%;
    top: 1.3vh;
    transition: color 0.3s;
     background: rgb(255, 0, 0);
     color: transparent;
    z-index: 7;
    cursor: pointer;
}
::-webkit-scrollbar{
    width: 8px;
}
::-webkit-scrollbar-thumb{
    background-color: rgb(255, 200, 200);
}
#search_result{
    width: 95%;
    height: 100vh;
    position: fixed;
    z-index: 555;
    /* top: 15vh; */
    top: 100vh;
    position: fixed;
    transition: top 0.3s;
    left: 2.5%;
    background-color: rgb(148, 0, 0);
}
#hes{
    font-size: 2.5rem;
    color: white;
    position: relative;
    left: 5%;
    top: 5vh;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
}
#hes2{
    font-size: 2rem;
    display: flex;
    width: 90%;
    height: 25vh;
    color: rgb(255, 0, 0);
    background-color: transparent;
    position: relative;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    top: 7vh;
    left: 5%;
}
#hd{
    position: relative;
    left: 5%;
    color: rgb(0, 0, 0);
    width: 30%;
    height: 4vh;
    top: -12vh;
    text-align: center;
    font-size: 1.5rem;
    display: flex;
    align-items: center;
    justify-content: center;
    text-shadow: 0px 0px 12px;
    background-color: rgb(255, 0, 0);
}
.r{
    position: relative;
    left: 2.5%;
}
.txt{
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.txt a{
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}














@media screen and (max-width: 100000px){
    #hr{
        display: none;
    }
    #alls2{
        display: none;
    }
    #alls3{
        display: none;
    }
}
@media screen and (max-width: 1240px) {
    .search{
        left: 60%;
    }
}
@media screen and (max-width: 1180px) {
    #HF-open{
        width: 4%;
        left: 91%;
    }
    #alls{
        height: 40vh;
    }
    #als-text{
        top: 26vh;
    }
    #hr{
        display: block;
    }
    #t1{
        font-size: 1.9rem;
    }
    #t2{
        font-size: 1.11rem;
    }
    #all-1{
        height: 149vh;
    }
    #HF-logo:hover{
        color: white;
    }
    #HF-logo{
        left: 4%;
        font-size: 3rem;
    }
    #i1{
        display: none;
    }
    .search{
        left: 58%;
    }
}

@media screen and (max-width: 1080px) {
    .search{
        left: 56%;
    }
}
@media screen and (max-width: 960px){
    #t2{
        font-size: 0.9rem;
    }
    .search{
        left: 54%;
    }
}
@media screen and (max-width: 902px) {
    #but{
        left: 80%;
    }
    #searchbar{
        left: 80%;
    }
}
@media screen and (max-width: 890px){
    #t2{
        font-size: 0.9rem;
    }
}

@media screen and (max-width: 840px){
    #HF-open{
        width: 6%;
        left: 92%;
    }
    #alls{
        display: none;
    }
    #hr{
        display: none;
    }
    #alls2{
        display: block;
        width: 90%;
        position: relative;
        left: 5%;
        background-color: rgb(223, 0, 0);
        height: 30vh;
        display: flex;
        cursor: pointer;
    }
    #alimg{
        background-size: cover;
        width: 50%;
        height: 30vh;
    }
    #tal2{
        width: 45%;
        background-color: rgb(255, 52, 52);
        height: 18vh;
        position: relative;
        left: 2.5%;
        top: 6vh;
    }
    #alt1{
        font-size: 1.9rem;
        width: 90%;
        text-align: center;
        position: relative;
        top: 2vh;
        left: 5%;
        color: white;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }
    #alt2{
        position: relative;
        top: 4vh;
        left: 5%;
        font-size: 1.4rem;
        width: 90%;
        text-align: center;
        color: white;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    #HF-open:hover{
        background-color: rgb(187, 0, 0);
        color: white;
    }
    #all-1{
        height: 204vh;
    }
    body{
        height: 300vh;
    }
    #contact{
        top: 25vh;
    }
    #but{
        left: 55%;
    }
    .search{
        left: 55%;
    }

}
@media screen and (max-width: 806px){
    .search{
        left: 55%;
    }
}

@media screen and (max-width: 788px){
    #but{
        left: 88%;
    }
    .search{
        left: 52%;
    }
    #HF-open{
        background-color: transparent;
    }
    #HF-open:hover{
        background-color: transparent;
    }
}
@media screen and (max-width: 720px){
    #but{
        left: 88%;
    }
    .search{
        left: 47%;
        width: 20%;
    }
}
@media screen and (max-width: 657px){
    #but{
        left: 88%;
    }
    .search{
        left: 44%;
        width: 22%;
    }
}
@media screen and (max-width: 625px){
    #but{
        left: 88%;
    }
    #searchbar::placeholder{
        position: relative;
        left: 5%;
    }
    .search{
        left: 40%;
        width: 20%;
    }
}
@media screen and (max-width: 576px){
    #but{
        left: 88%;
    }
    #searchbar::placeholder{
        position: relative;
        left: 5%;
    }
    .search{
        left: 48%;
        width: 20%;
    }
}

@media screen and (max-width: 576px){
    #but{
        left: 88%;
    }
    #searchbar::placeholder{
        position: relative;
        left: 5%;
    }
    .search{
        left: 38%;
        width: 20%;
    }
}
@media screen and (max-width: 532px){
    .search{
        left: 34%;
    }
}
@media screen and (max-width: 488px){
    #but{
        left: 88%;
    }
    #searchbar::placeholder{
        position: relative;
        left: 5%;
    }
    .search{
        left: 30%;
        width: 19%;
    }
}

@media screen and (max-width: 457px){
    #but{
        left: 88%;
    }
    #searchbar::placeholder{
        position: relative;
        left: 5%;
    }
    #searchbar{
        width: 0%;
    }
    .search{
        left: 20%;
        width: 25%;
    }
}
@media screen and (max-width: 410px){
    #but{
        left: 88%;
    }
    #searchbar::placeholder{
        position: relative;
        left: 5%;
    }
    .search{
        left: 10%;
        width: 30%;
    }
}
@media screen and (max-width: 367px){
    #but{
        left: 88%;
    }
    #searchbar::placeholder{
        position: relative;
        left: 5%;
    }
    .search{
        left: 0%;
        width: 36%;
    }
}
@media screen and (max-width: 340px){
    .search{
        left: -3%;
    }
}
@media screen and (max-width: 324px){
    .search{
        left: -6%;
    }
}
@media screen and (max-width: 309px){
    .search{
        left: -10%;
    }
}


@media screen and (max-width: 743px) {
    #alt1{
        font-size: 1.5rem;
        top: 4rem;
    }
    #alt2{
        font-size: 1.1rem;
        top: 4.5rem;
    }
}

@media screen and (max-width: 592px) {
    #HF-reklam{
        font-size: 1.5rem;
    }
    #HF-open{
        width: 7%;
        left: 90%;
    }
    #alt1{
        top: 3rem;
        font-size: 1.2rem;
    }
    #alt2{
        top: 3.5rem;
    }
}
@media screen and (max-width : 480px) {

    #alls2{
        display: none;
    }
    #HF-open{
        width: 10%;
        left: 88%;
    }
    #HF-reklam{
        font-size: 1.3rem;
    }
    #alls3{
        display: block;
        height: 50vh;
        width: 90%;
        position: relative;
        top: -20vh;
        cursor: pointer;
        left: 5%;
        background-color: rgb(223, 0, 0);
    }
    #alimg3{
        width: 100%;
        background-size: cover;
        height: 30vh;
    }
    #HF-open{
        left: 86%;
    }
    #tal3{
        width: 100%;
        height: 20vh;
        display: flex;
        align-items: center;
        justify-content: center;
        text-align: center;
        flex-direction: column;
    }
    #alt31{
        color: white;
        font-size: 1.7rem;
        font-family:system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    #alt32{
        color: white;
        position: relative;
        top: 1vh;
        font-size: 1.3rem;
        font-family: Verdana, Geneva, Tahoma, sans-serif;
    }
    #all-1{
        height: 215vh;
    }
    #contact{
        display: none;
    }
    body{
        height: 260vh;
    }
}
@media screen and (max-width: 383px) {
    #HF-open{
        left: 84%;
        width: 12%;
    }
}
    </style>
    <header id="HF-hed1">
        <div id="HF-logo"><a href="Home.html">HF-News</a></div>
        <div class="search">
        <button onclick="butt()" id="but"><i id="isearch" class="ri-search-line"></i></button>
       <input type="text" onkeyup="searchh()" name="search" id="searchbar" placeholder="Որոնում">
    </div>
        <i id="HF-open" class="ri-list-unordered"></i>
    
    
    </header>
    <div id="HF-opened">
        <div id="new">
            <a  href="Home.html" id="H1" style="transition: color 0.3s, text-shadow 0.3s;"><i style="position: absolute; left: 49%; color: transparent; transition: color 0.3s, text-shadow 0.3s; text-shadow: 0px 0px 0px ;" id="i1" class="ri-home-2-fill"></i> Home</a>
            <a href="#" id="H2" style="transition: color 0.3s, text-shadow 0.3s;"><i style="position: absolute; left: 49%; color: transparent; transition: color 0.3s, text-shadow 0.3s; text-shadow: 0px 0px 0px ;" id="i2" class="ri-tv-2-fill"></i> About</a>
            <a href="#" id="H3" style="transition: color 0.3s, text-shadow 0.3s;"><i style="position: absolute; left: 49%; color: transparent; transition: color 0.3s, text-shadow 0.3s; text-shadow: 0px 0px 0px ;" id="i3" class="ri-add-box-fill"></i> New News</a>
            <a href="#" id="H4" style="transition: color 0.3s, text-shadow 0.3s;"><i style="position: absolute; left: 49%; color: transparent; transition: color 0.3s, text-shadow 0.3s; text-shadow: 0px 0px 0px ;" id="i4" class="ri-phone-fill"></i> contact</a>
        </div>
    </div>

    <div id="HF-reklam">
      <div class="txt" style="color: black;">  Գլխավոր Նյութեր HF-News Կայքում <br> Գովազդի համար Գրել Էլ փոստին <a style="color: black;" href="https://mail.google.com/mail/u/0/?to=hf.news.hf@gmail.com&su=%D4%B5%D5%BD+%D5%A3%D6%80%D5%B8%D6%82%D5%B4+%D5%A5%D5%B4+HF-News+%D5%AF%D5%A1%D5%B5%D6%84%D5%AB%D5%B6+%D5%A3%D5%B8%D5%BE%D5%A1%D5%A6%D5%A4%D5%AB+%D5%B0%D5%A1%D5%B4%D5%A1%D6%80&fs=1&tf=cm"> hf.news.hf@gmail.com </a> </div>
    </div>


    <ul id="searchik">
        <li id="span" onclick="disp()" ><a id="span"  href="#">Արզախանթյանը և իր կինը  <div id="d" style="display: none;">  arzaxantyany ev ir kinny </div></a></li>
        <li id="span" ><a id="span"  href="#">Նիկոլ Փաշինյանը  <div id="d" style="display: none;">  nikol pashinyany </div></a></li>
      
        <li id="span" ><a id="span"  href="#">Ծրագրավորման դասեր Անվճար  <div id="d" style="display: none;">  cragravorman daser anvchar </div></a></li>
        <li id="span" ><a id="span"  href="#">Էրդողանը ուզում է հեռանալ ԵՄ - ից  <div id="d" style="display: none;">  erdoxany wuzum e heranal emic </div></a></li>
      
        <li id="span" ><a id="span"  href="#">Ջղայն ուսուցիչը  <div id="d" style="display: none;"> jxayn usucichy  </div></a></li>
        <li id="span" ><a id="span"  href="#">ԻՄ Յութուբյան ալիքը  <div id="d" style="display: none;">  im yutubyan aliqy </div></a></li>
      </ul>
      <div onclick="her()" id="mug"></div>

<div id="search_result">
    <h2 id="hes">Որոնումը չի հայտնաբերվել</h2>
    <div id="hes2">Որոնումը չի հայտնաբերվել , Ստուգեք  Բառը կամ կրկին փորձեք</div>
    <div id="hd"></div> 
</div>


    <div id="all-1">
        <!-- this is one  -->





<!-- This is 1 -->
<!-- This is 1 -->
<!-- This is 1 -->
<!-- This is 1 -->
<!-- This is 1 -->
<!-- This is 1 -->
<!-- This is 1 -->
<!-- This is 1 -->
<!-- This is 1 -->
<!-- This is 1 -->


        <div id="alls" onclick="disp()"  style="background-image: url(image/arz.jpg); position: absolute;" class="animals">
            <div id="als-text">
                <div id="t1">Արզախանթյանը և իր կինը </div>
                <div id="t2">Արզախանթյանի հիմարությունը և կնոչ տգետությունը միասնի գեղեցիկ զույգ են կազմում </div>
            </div>
        </div>

        <br><hr id="hr" style="position: absolute; top: 48vh; width: 100%; color: black;"><br>
        <div id="alls" style="background-image: url(image/nikol.jpg); left: 34%; position: absolute;" class="animals">
            <div id="als-text">
                <div id="t1">ՆԻկոլ Փաշինյանը</div>
                <div id="t2">Նիկոլ Փաշինյանը իր անհիմն մեղադրանքով նախկիններին</div>
            </div>    
        </div>
        <br><hr id="hr" style="position: absolute; top: 101vh; width: 100%; color: black;"><br>
        <div id="alls" style="background-image: url(image/crag.jpg); left: 67%; position: absolute;" class="animals">
            <div id="als-text">
                <div id="t1">Ծրագրավորման դասեր</div>
                <div id="t2">Ծրագրավորման  դասընթացներ Օնլայն | Անվճար դասեր , հեռախոսահամար ՝ +(374)-93-39-01-17</div>
            </div>    
        </div>



<!-- this is two  -->
<!-- this is two  -->




        <div id="alls" style="background-image: url(image/youtube.png); top: 54.5vh; position: absolute;" class="animals">
            <div id="als-text">
                <div id="t1">Youtube Օնլայն Կայք</div>
                <div id="t2">Իմ Յութուբյան ալիքը իմ կայքում</div>
            </div>
        </div>
        <div id="alls" style="background-image: url(image/teacher.jpg); left: 34%; position: absolute; top: 54.5vh;" class="animals">
            <div id="als-text">
                <div id="t1">Չափից շատ ջղայն ուսուցիչը</div>
                <div id="t2">Ինչ է պատահում երբ ուսուցիչը լինում է Չափից շատ ջղայն աշակերտի վրա</div>
            </div>    
        </div>
        <div id="alls" style="background-image: url(image/cexaspanutyun.jpg); left: 67%;  top: 54.5vh; position: absolute;" class="animals" >
            <div id="als-text">
                <div id="t1">Թուրքերը ուզում են կրկնել անցյալը</div>
                <div id="t2">Թուրքերը ուզում են կրկնել 1915 թվականի կատարված իրադարձությունը</div>
            </div>    
        </div>


 <!-- This is 3 -->


        <div id="alls" style="background-image: url(image/crag.jpg); top: 107.1vh; position: absolute;" class="animals">
            <div id="als-text">
                <div id="t1">Արզախանթյանը և իր կինը</div>
                <div id="t2">Արզախանթյանը և իր կինը հրապարակում ժրավազանի մեջ ձուկ բռնելուց</div>
            </div>
        </div>
        <div id="alls" style="background-image: url(image/arz.jpg); left: 34%; position: absolute; top: 107.1vh;" class="animals">
            <div id="als-text">
                <div id="t1">ՆԻկոլ Փաշինյանը</div>
                <div id="t2">Նիկոլ Փաշինյանը իր անհիմն մեղադրանքով նախկիններին</div>
            </div>    
        </div>
        <div id="alls" style="background-image: url(image/nikol.jpg); left: 67%;  top: 107.1vh; position: absolute;" class="animals">
            <div id="als-text">
                <div id="t1">Ծրագրավորման դասեր</div>
                <div id="t2">Ծրագրավորման  դասընթացներ Օնլայն | Անվճար դասեր , հեռախոսահամար ՝ +(374)-93-39-01-17</div>
            </div>    
        </div>
        <!-- This is 4 -->



        <!-- This is 4 -->
        <!-- This is 4 -->



        <div id="alls" style="background-image: url(image/crag.jpg); top: 160vh; position: absolute;" class="animals">
            <div id="als-text">
                <div id="t1">Արզախանթյանը և իր կինը</div>
                <div id="t2">Արզախանթյանը և իր կինը հրապարակում ժրավազանի մեջ ձուկ բռնելուց</div>
            </div>
        </div>
        <div id="alls" style="background-image: url(image/arz.jpg); left: 34%; position: absolute; top: 160vh;" class="animals">
            <div id="als-text">
                <div id="t1">ՆԻկոլ Փաշինյանը</div>
                <div id="t2">Նիկոլ Փաշինյանը իր անհիմն մեղադրանքով նախկիններին</div>
            </div>    
        </div>
        <div id="alls" style="background-image: url(image/nikol.jpg); left: 67%;  top: 160vh; position: absolute;" class="animals">
            <div id="als-text">
                <div id="t1">Ծրագրավորման դասեր</div>
                <div id="t2">Ծրագրավորման  դասընթացներ Օնլայն | Անվճար դասեր , հեռախոսահամար ՝ +(374)-93-39-01-17</div>
            </div>    
        </div>





<!-- This is 2 -->
<!-- This is 2 -->
<!-- This is 2 -->
<!-- This is 2 -->
<!-- This is 2 -->
<!-- This is 2 -->
<!-- This is 2 -->
<!-- This is 2 -->
<!-- This is 2 -->
<!-- This is 2 -->
<!-- This is 2 -->




        <div id="alls2">
            <div style="background-image: url(image/arz.jpg);" id="alimg"></div>
            <div id="tal2">
                <div id="alt1">Արզախանթյանը և իր կինը</div>
                <div id="alt2">Արզախանթյանը և իր կինը հրապարակում ժրավազանի մեջ ձուկ բռնելուց</div>
            </div>
        </div>
        <div id="alls2" style="top: 3vh;">
            <div style="background-image: url(image/nikol.jpg);" id="alimg"></div>
            <div id="tal2">
                <div id="alt1">Նիկոլ Փաշինյանը</div>
                <div id="alt2">Նիկոլ Փաշինյանը իր անհիմն մեղադրանքով նախկիններին</div>
            </div>
        </div>
        <div id="alls2" style="top: 6vh;">
            <div style="background-image: url(image/crag.jpg);" id="alimg"></div>
            <div id="tal2">
                <div id="alt1">Նիկոլ Փաշինյանը</div>
                <div id="alt2">Նիկոլ Փաշինյանը իր անհիմն մեղադրանքով նախկիններին</div>
            </div>
        </div>
        <div id="alls2" style="top: 9vh;">
            <div style="background-image: url(image/youtube.png);" id="alimg"></div>
            <div id="tal2">
                <div id="alt1">Արզախանթյանը և իր կինը</div>
                <div id="alt2">Արզախանթյանը և իր կինը հրապարակում ժրավազանի մեջ ձուկ բռնելուց</div>
            </div>
        </div>
        <div id="alls2" style="top: 12vh;">
            <div style="background-image: url(image/nikol.jpg);" id="alimg"></div>
            <div id="tal2">
                <div id="alt1">Նիկոլ Փաշինյանը</div>
                <div id="alt2">Նիկոլ Փաշինյանը իր անհիմն մեղադրանքով նախկիններին</div>
            </div>
        </div>
        <div id="alls2" style="top: 15vh;">
            <div style="background-image: url(image/crag.jpg);" id="alimg"></div>
            <div id="tal2">
                <div id="alt1">Նիկոլ Փաշինյանը</div>
                <div id="alt2">Նիկոլ Փաշինյանը իր անհիմն մեղադրանքով նախկիններին</div>
            </div>
        </div>









<!-- This is 3 -->
<!-- This is 3 -->
<!-- This is 3 -->
<!-- This is 3 -->
<!-- This is 3 -->
<!-- This is 3 -->
<!-- This is 3 -->
<!-- This is 3 -->
<!-- This is 3 -->
<!-- This is 3 -->
<!-- This is 3 -->
<!-- This is 3 -->
<!-- This is 3 -->






<div id="alls3" style="top: -3.5vh;">
    <div style="background-image: url(image/crag.jpg);" id="alimg3"></div>
    <div id="tal3">
        <div id="alt31">Նիկոլ Փաշինյանը</div>
        <div id="alt32">Նիկոլ Փաշինյանը իր անհիմն մեղադրանքով նախկիններին</div>
    </div>
</div>
<div id="alls3" style="top: -0.8vh;">
    <div style="background-image: url(image/arz.jpg);" id="alimg3"></div>
    <div id="tal3">
        <div id="alt31">Նիկոլ Փաշինյանը</div>
        <div id="alt32">Նիկոլ Փաշինյանը իր անհիմն մեղադրանքով նախկիններին</div>
    </div>
</div>
<div id="alls3" style="top: 2.3vh;">
    <div style="background-image: url(image/nikol.jpg);" id="alimg3"></div>
    <div id="tal3">
        <div id="alt31">Նիկոլ Փաշինյանը</div>
        <div id="alt32">Նիկոլ Փաշինյանը իր անհիմն մեղադրանքով նախկիններին</div>
    </div>
</div>
<div id="alls3" style="top: 5vh;">
    <div style="background-image: url(image/youtube.png);" id="alimg3"></div>
    <div id="tal3">
        <div id="alt31">Youtube Օնլայն Կայք </div>
        <div id="alt32">Իմ Յութուբյան ալիքը իմ կայքում  </div>
    </div>
</div>

    </div>




    <!-- This is 4 -->
    <!-- This is 4 -->
    <!-- This is 4 -->
    <!-- This is 4 -->
    <!-- This is 4 -->
    <!-- This is 4 -->
    <!-- This is 4 -->
    <!-- This is 4 -->
    <!-- This is 4 -->
    <!-- This is 4 -->
    <!-- This is 4 -->
    <!-- This is 4 -->






    <div style="display: none;" id="all2"></div>
</body>
</html>
