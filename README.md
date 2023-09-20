
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
