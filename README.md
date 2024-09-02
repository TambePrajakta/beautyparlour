<!DOCTYPE html>
<html lang="en">
<head>
   <title>Media Queries</title>
   <style>
     body{
        background-color: lavender;
     }
.img{
   height: 100px;
   width: 100px;
   display: flexbox;
   display: inline-block;

}
.text1{
        text-align: center;
        color: rgb(253, 8, 32);
        font-size: 50px;
        font-family: cursive;
}
   
   .img1{
      height: 100px;
   width: 100px;
   display: inline;
   display: flexbox;
   justify-content: center;
   display: inline-block;
   border: 10px double rgb(2, 2, 192);
   border-radius: 10px;
   margin: 25px;
   }
.img1:hover{
   transform: scale(1.05);
   transition: 0.5s;
}
     .text2{
      text-align: center;
        color: rgb(3, 26, 227);
        font-size: 50px;
        justify-content: center;
        font-family: cursive;
     } 
     .navbar{
      display:flex;
      text-align: center;
      background-color: rgb(149, 228, 228);
     height: 120px;
     }
     .img2{
      cursor: pointer;
      margin: 25px;
      height: 75px;
      width: 75px;
     }
      /* Mobile Devices */
      @media screen and (max-width:500px){
         body{
            background-color:rgb(252, 162, 207) ;
         }
         .text1{
            font-size: 30px;
         }
         .text2{
            font-size: 20px;
         }
         .img{
            height: 50px;
            width: 50px;
         }
         .img1{
            height: 50px;
            width: 50px;
            display: flex;
            display: inline-block;
         }
         .img2{
            height:40px ;
            width: 40px;
            display: flex;
            display: block;
            margin: 7px;
         }
         .navbar{
            height:50px ;
            display: flex;
            background-color: aqua;
         }
      }
     </style>
</head>
<body>
   <div class="navbar">
      <img src="./Hydrating_Face_Moisturizer.jpg" class="img2">
      <img src="./condistioner1.jpg" class="img2">
      <img src="./blush2.jpg" class="img2">
      <img src="./lipstik5.jpg" class="img2">
      <img src="./eye3.jpg" class="img2">
   
   </div>
    <h1 class="text1"> <img src="./beauty.jpg"  class="img">&nbsp;&nbsp;&nbsp;BEAUTY PARLOUR PRODUCT &nbsp;&nbsp;&nbsp;<img src="./beauty2.jpg" class="img"></h1>
   <h2 class="text2">Moisturizer</h2>
    <img src="./moisture.jpg" class="img1">
    <img src="./nivya.jpg" class="img1">
    <img src="./gel moisture" class="img1">
    <img src="./gel moisture.jpg" class="img1">
    <img src="./lakme.webp" class="img1">
    <img src="./Hydrating_Face_Moisturizer.jpg" class="img1">
   

    <h2 class="text2">Conditioner</h2>
    <img src="./condistioner1.jpg" class="img1">
    <img src="./dove.webp" class="img1">
    <img src="./onions.jpg" class="img1">
    <img src="./sunsilk.jpg" class="img1">
    <img src="./naturre.webp" class="img1">
    <img src="./pantene.jpg" class="img1">
   

    <h2 class="text2">Blush</h2>
    <img src="./-soft-cream-blush-makeup-liquid.jpg" class="img1">
    <img src="./best blush.jpg" class="img1">
    <img src="./blushes.jpg" class="img1">
    <img src="./spiring blush.jpg" class="img1">
    <img src="./blush2.jpg" class="img1">
    <img src="./1145831_-_MUR_-_Ultra_Blush_Palette_-.webp" class="img1">
    

    <h2 class="text2">lipstik</h2>
    <img src="./lipstik.jpg" class="img1">
    <img src="./lipstik2.jpg" class="img1">
    <img src="./lip3.jpg" class="img1">
    <img src="./lipstik4.webp" class="img1">
    <img src="./lipstik5.jpg" class="img1">
    <img src="./lipstik6.jpg" class="img1">


    <h2 class="text2">Eyelash curler</h2>
    <img src="./eye1.jpg" class="img1">
    <img src="./eye2.jpg" class="img1">
    <img src="./eye3.jpg" class="img1">
    <img src="./eye4.jpg" class="img1">
    <img src="./eye5.jpg" class="img1">
    <img src="./eye6.jpg" class="img1">
   </body>
</html>
