<!DOCTYPE html>
<html>
    <head>
        <title>Code</title>
        <style>
        body{
            overflow:hidden;
            background-color:#f2f2f2;
           }
        *{
          margin:0px;
          padding:0px;
         }     
      .heading{
            width:auto;
            height:60px;
            background-color:#f2f2f2;
            text-align:center;
            line-height:60px;
        }    
        .c0{
            color:#ee;
            font-family:serif;
            display:inline;
        }
        .c1{
            color:green;
            font-family:serif;
            display:inline;
        }
     /*    .d{
            position:sticky;
            top:0;
            z-index:100;
        } */
        .d .menu{
            background-color:green;
            opacity:0.7;
            width:auto;
            height:60px;
            position:sticky;
        }
      
       .d .menu #sidebar{
           position:absolute;
           width:200px;
           height:1000px;
           left:-200px;
           opacity:1.0;
           background-color:black;
       }     
        .d .menu #sidebar ul li{
             color:white;
             list-style-type:none;
             padding:10px 10px;
         }  
         .d .menu #sidebar .toggle{
             position:absolute;
             left:200px;
             top:0px;
             width:50px;
             height:42px;
             margin:0px;
             padding:9px;
            // border:1px solid black;
            }
           .d .menu #sidebar ul li a{
            color:white;
            text-decoration:none;
            padding:10px 5px;
            font-weight:bold;
        }    
         .d .menu #sidebar .toggle span{
             display:block;
             width:30px;
             height:5px;
             background-color:#151719;
             margin:5px;
         }  
         .d .menu #sidebar.active 
        {
              left:0px;
        }   
         .d .menu #sidebar .toggle:hover
          {
              background-color:Dodgerblue;
          }
          .main{
              width:auto;
              margin:0px;
              height:250px;
              background-color:white;
              //border:1px solid black;
              //border-radius:4px;
              text-align:center;
          }
          .main h1{
              font-family:fantasy;
              font-size:45px;
              margin:5px;
              padding:30px 30px 15px 30px;
          }
          .main p{
              padding:15px;
              font-size:18px;
          }
          .main .bb{
              width:120px;
              height:42px;
              margin:15px 15px 15px 10px;
              border:1px solid black;
              border-radius:4px;
              text-align:center;
              position:absolute;
              left:120px;
              line-height:48px;
             }
             .main .bb a{
                 display:block;
                 text-decoration:none;
                 color:black;
             }
        </style>
    </head>
    <body>
    
    <div class="heading">
       <h1 class="c0">CODING&nbsp</h1><h1 class="c1">SCHOOL</h1>
    </div>
    
   <div class="d">
    <div class="menu">
      <div id="sidebar">
           
        <div class="toggle" onclick="gg()" >
             <span></span> 
             <span></span>
             <span></span>
          </div>
          <ul>
          <li>BASICS OF C</li>
            <li><a href="WEBSITE_SUPPORT.html">Overview of C Language</a></li>
            <li><a href="WEBSITE_SUPPORT_FEATURES.html">Features of C</a></li>
            <li><a href="WEBSITE_FIRST_PRO.html">First C Program</a></li>
            <li><a href="#">C syntax rules</a></li>
            <li><a href="#">keywords and Identifires</a></li>
            <li><a href="#">Data Types</a></li>
            <li><a href="#">Variables</a></li>
            <li><a href="#">Switch Statements</a></li>
            <li><a href="#">Arrays</a></li>
            <li><a href="#">Strings and Character Array</a></li>
            <li><a href="#">Loops</a></li>
            <li><a href="#">Storage Classes</a></li>
          </ul>
      </div>  
      </div>
      </div>
      
      <div class="main">
 <h1>C LANGUAGE</h1>
 <p>A general purpose programming language</p>
<div class="bb"><a href="WEBSITE_SUPPORT.html">Learn C</a>
</div>
      
      
    
      
      
      
      
      
      
      
    </body>
</html>
