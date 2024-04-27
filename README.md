<!doctype html>
<html lang="en">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width , initial-scale=1">
  <!-- 
   增加上面这句，可以看到浏览器的DevTools面板的模拟移动设备状态的变化
  -->
  <style>
    *{
      margin: 10px;
      text-align: center;
    }
    header{
      border: 2px solid rgb(195, 27, 229);
      height: 15%;
      font-size: 1.4em;
    }
    main{
      border: 2px solid rgb(241, 92, 204);
      height: 70%;
      font-size: 0.6em;
      background-image: url(./CSS.jpg);
      background-size: cover;
    }
    nav{
      border: 2px solid rgb(246, 118, 203);
      height: 10%;
      font-size: 1.2em;
    }
    footer{
      border: 2px solid rgb(245, 131, 220);
      height: 5%;
    }
  </style>
  <!--<link rel="stylesheet" href="myCSS.css" > 
  <script src="myInit.js"> </script>-->
  <title> "读好书、练思维、勤编程" </title>
 </head> 
 <body>
  <header>
	  <p id="book">
      开源软件开发环境
    </p> 
  </header>
  <nav>
    <button>pre1</button>
    <button>pre2</button>
    <button>pre3</button>
    <!--<p id ="chapter">
     导航章节
	  </p>-->
  </nav>
  <main id = 'main'>
    <img  id = "bookFace"> 
    通过参考文献系统的阐述了现代开源软件的历史和现状，从软件开发的角度，总结了现代开源软件的开发环境，创造性的搭建了适合个人习惯的开发环境。其中，主要用Linux命令行搭建软件操作系统环境，实现代码的版本控制，实现了代码编译器和系统操作命令行完美高效的运行，并通过修改操作系统的配置实现代码编译器，通过Git克隆获取GitHub的开源代码，实现在本地建立了个人的代码仓库以及对代码的快速修改和运行。
  </main> 

  <footer> 
   <p id="statusInfo">
     xielx 江西科技师范大学 2021--2025
	 </p>
  </footer> 

 <script>
    var UI = {};
    UI.appWidth = window.innerWidth;
    UI.appHeigth = window.innerHeight;
    let baseFont = parseInt(UI.appWidth/20);
    //字体大小、颜色可继承
    document.body.style.fontSize = baseFont + "px";
    //body高度设置为屏幕高度
    document.body.style.height = UI.appHeigth + "px";
 </script>
 </body>
</html>
