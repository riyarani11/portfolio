<!DOCTYPE html>
><html>
    <head>
        <title>My portfolio</title>
    </head>

    <style>
    .top {
        position: relative;
        text-align: center;
        color: white;
               }
    .one{
        position:relative;
        text-align:left;
        color:rgb(252, 250, 248);
    }

    .left{
        position:absolute;
        top: 2px;
        left:10%;
        right:33%;
    }
    .box{
      position: relative;
      text-align:right;
      color:bisque;
      ;

    }

    .right{
      position: absolute;
      top:10px;
      right:20%;
      left: 30%;
      color:black;
    }


    .header{
        background-color: black;
        text-align:left;
        color:cornsilk;
        padding: 20px;
           }
div.gallery {
  border: 1px solid #ccc;
}

div.gallery:hover {
  border: 1px solid #777;
}

div.gallery img {
  width: 100%;
  height: auto;
}

div.desc {
  padding: 20px;
  text-align: center;
  color:burlywood;
  font-size:20px;
}

* {
  box-sizing: border-box;
}

.in {
  padding: 0 6px;
  float: left;
  width: 24.99999%;
}

@media only screen and (max-width: 700px) {
  .in {
    width: 49.99999%;
    margin: 6px 0;
  }
}

@media only screen and (max-width: 500px) {
  .in {
    width: 100%;
  }
}

.clearfix:after {
  content: "";
  display: table;
  clear: both;
}
table {
            font-family: arial, sans-serif;
            border:inset 10px;


            color:black;

        }

        td, th {
            border: 1px solid black;
            text-align: left;
            padding: 30px;
        }

        tr:nth-child(odd) {
            background-color:#0D4D5A;
          }
        tr:nth-child(even) {
                background-color:#0D4D5A;
        }
        table.center {
    margin-left:auto;
    margin-right:auto;
  }


.button {
  border: none;
  color: black;
  padding: 2px 3px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
}


.button {
  background-color: rgb(0, 0, 0);
  color: black;
  border: 2px solid #000000;
  border-radius: 12px;
}

.button:hover {
  background-color: #ffffff;
  color: white;
}
#js {
  display: none;
  position: fixed;
  bottom: 20px;
  right: 30px;
  z-index: 99;
  font-size: 18px;
  border: none;
  outline: none;
  background-color: rgb(34, 2, 10);
  color: white;
  cursor: pointer;
  padding: 15px;
  border-radius: 4px;
}

#js:hover {
  background-color: rgb(82, 30, 30);
}


    </style>
    <body bgcolor="black">
      <button onclick="topFunction()" id="js" title="Go to top">Scroll Top</button>

    <div class="header"><p style=font-size:30px align="center">My Portfolio</p></div>
    <script>

      var mybutton = document.getElementById("js");


      window.onscroll = function() {scrollFunction()};

      function scrollFunction() {
        if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
          mybutton.style.display = "block";
        } else {
          mybutton.style.display = "none";
        }
      }


      function topFunction() {
        document.body.scrollTop = 0;
        document.documentElement.scrollTop = 0;
      }
      </script>
    <div class="top">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTjFJfVJJRlv46hbfgtm-_OgflJZHTNT5pnbA&usqp=CAU" style="width:100%">

        <div class="content">
            <p align ="center" style="font-size: 55px; font-family:palatino, Times, serif  ;">Hello! I am Riya Rani<br></p>
            <p align ="center" style="font-family:palatino, Times, serif; font-size: 30px;">Welcome to my portfolio.</p>

        </div>
    </div>

    <div class="one">
        <img src="https://dailypost.files.wordpress.com/2015/04/turnpike-blur.jpg" style="width: 100%" />
        <div class="left"><h1 style="font-size: 50px"><br><U>ABOUT</U></h1><br><p style="font-size: 20px; font-family:  PALATINO, Times, serif;">
        <br>
         Hello! I am Riya Rani persuing BTech in CSE from <i><a href="http://chennai.vit.ac.in/">VIT University</a></i>.I always loved coding and programming so here i am with my first personal site. Feel free to explore and navigate through my small work.<br /> THANKYOU!!
</div>
    </div>
    <div class="box">
      <img src="https://cdn.pixabay.com/photo/2016/11/29/07/21/blur-1868068_960_720.jpg" style="width: 100%"/>
      <div class="right">
        <br><br><br><br><h1 style="font-size: 50px"; align="center" color="red"><u>EDUCATION</u></h1><br><p style="font-size: 20px; font-family:PALATINO, Times, serif;"> <br>
        <TABLE>
           <tr>
            <td>
              PROGRAMME
            </td>
            <TD>
              INSTITUTE
            </TD>
            <TD>
              YEAR OF COMPLETION
            </TD>
          </tr>
          <tr>
          <Td>
            Graduation
          </td>
          <td>
            <a href="http://chennai.vit.ac.in">VIT University,Chennai</a>
          </td>
          <td>
            2019-2023
          </td>
        </tr>
        <tr>
        <Td>
        Higher secondary
        </td>
        <td>
          <a href="https://www.scsranchi.com/">Surendranath Centenary School,Ranchi</a>
        </td>
        <td>
          2019
        </td>
        </tr>
        <tr>
        <Td>
        High school
        </td>
        <td>
          <a href="https://www.scsranchi.com/">Surendranath Centenary School,Ranchi</a>
        </td>
        <td>
          2017
        </td>
        </tr>
        </thead>
        </table>
        </p>
      </div>
    </div>
    <p style="text-align: center; font-size: 30px; color:#AB9CC2; font-family: 'PALATINO', Times, serif;"> SOME CERTIFICATES </p>
    <div class="in">
        <div class="gallery">
          <a target="_blank" href="COMAPP.JPG">
            <img src="COMAPP.JPG" alt="sunday noon" width="600" height="400">
          </a>
          <div class="desc">COMPUTER APPLICATION </div>
        </div>
      </div>


      <div class="in">
        <div class="gallery">
          <a target="_blank" href="MGT.JPG">
            <img src="MGT.JPG" alt="Horse" width="600" height="400">
          </a>
          <div class="desc">MARKETING MANAGEMENT</div>
        </div>
      </div>

      <div class="in">
        <div class="gallery">
          <a target="_blank" href="DBMS.JPG">
            <img src="DBMS.JPG" alt="Sunsetz" width="600" height="400">
          </a>
          <div class="desc">DBMS</div>
        </div>
      </div>


    <div class="clearfix"></div>

    <p style="text-align: center; font-size: 30px; color:#AB9CC2; font-family: 'PALATINO', Times, serif;">TECHNICAL SKILLS</p>
    <div class="in">
      <div class="gallery">
        <a target="_blank" href="https://miro.medium.com/max/792/1*lJ32Bl-lHWmNMUSiSq17gQ.png">
          <img src="https://miro.medium.com/max/792/1*lJ32Bl-lHWmNMUSiSq17gQ.png" alt="Birds of prey" width="600" height="400">
        </a>
        <div class="desc">HTML & CSS </div>
      </div>
    </div>


    <div class="in">
      <div class="gallery">
        <a target="_blank" href="https://logodix.com/logo/374736.png">
          <img src="https://logodix.com/logo/374736.png" alt="dobby" width="600" height="400">
        </a>
        <div class="desc">
          JAVASCRIPT
        </div></div>
      </div>
    </div>

    <div class="in">
      <div class="gallery">
        <a target="_blank" href="https://developers.redhat.com/blog/wp-content/uploads/2020/06/C_C_featuredimage.png">
          <img src="https://developers.redhat.com/blog/wp-content/uploads/2020/06/C_C_featuredimage.png" alt="rose" width="600" height="400">
        </a>
        <div class="desc">C & C++</div>
      </div>
    </div>

    <div class="in">
      <div class="gallery">
        <a target="_blank" href="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRxRVmZ0vGCWrcyl9516QQQal5XDYawhsmM2A&usqp=CAU">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcRxRVmZ0vGCWrcyl9516QQQal5XDYawhsmM2A&usqp=CAU" alt="Birds" width="600" height="400">
        </a>
        <div class="desc"> PYHTON</div>
      </div>
    </div>

<br><br><br><br><br><br><br><br><br><br><br>/div><br><br><br>

<div class="one">
    <img src="https://t3.ftcdn.net/jpg/02/95/39/32/240_F_295393208_jue1ObYal5COSi5imlaxHiMwD8MNArVk.jpg" HEIGHT="500"style="width: 100%" />
    <div class="left"><h1 style="font-size: 50px"><br><U>INTEREST</U></h1><br><p style="font-size: 20px; font-family:  PALATINO, Times, serif;">
    <br>
    <br />
    <br />
    <h3>
    <ul>
      <li>
        Dancing
      </li>
      <li>
        Playing basketball
      </li>
      <li>
        Gardening
      </li>
      <li>
        Watching movies and series
      </li>
    </ul>
    </h>
</div>

<p style="text-align: center;font-size: 20px; font-family: 'PALATINO', Times, serif;color: WHITE;">CONTACT ME<br>
  <button class="button button"><a href="https://www.instagram.com/riya.agrawal11/" target="_blank"><img src="https://www.instagram.com/static/images/ico/apple-touch-icon-76x76-precomposed.png/666282be8229.png" style="border-radius: 12px;"/></a></button>
  <button class="button button"><a href="https://mail.google.com/mail/u/0/#inbox" target="_blank"><img src="https://ssl.gstatic.com/ui/v1/icons/mail/rfr/logo_gmail_lockup_default_2x.png" style="border-radius: 5px;"/></a></button>
  <button class="button button"><a href="https://www.linkedin.com/in/riya-rani-aa7451193/" target="_blank"><img src="https://static-exp1.licdn.com/sc/h/2if24wp7oqlodqdlgei1n1520" style="border-radius: 5px;"/></a></button>
<button class="button button"><a href="https://www.facebook.com/riya.rani.9406/" target="_blank"><img src="https://lh3.googleusercontent.com/ccWDU4A7fX1R24v-vvT480ySh26AYp97g1VrIB_FIdjRcuQB2JP2WdY7h_wVVAeSpg" style="border-radius: 5px; height="70" width="70""/></a></button>
<button class="button button"><a href="https://twitter.com/Riyaagr55940959" target="_blank"><img src="https://media.altpress.com/uploads/2018/07/twitter_2014-5.jpg" style="border-radius: 5px; height="70" width="70""/></a></button></p>









    <script async src="https://drv.tw/inc/wd.js"></script></body>
</html>
