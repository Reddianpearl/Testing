# Testing 
<html>
<head> 
<meta charset="utf-8">
<title> box model </title>
<style>
*{box-sizing: border-box;
   margin: 10px;
   padding: 10px;}
h1 {color: blue;}
section {width: 300px;
   height: 150px;
   border: 1px solid black;
   background-color: grey;
   font-align: centre;
   float: left;
   position: relative;}  
p {width: 150px;
   height: 50px;
   border: 1px solid black;
   font-align: centre;
   margin: 0px;
   float: left;
   position: absolute;
   top: 0px;
   right: 0px;}        
#p1{background-color: pink;}
#p2{background-color: green;}
#p3{background-color: yellow;}
</style>
</head>
  
<body> 
<h1> Box model </h1>
<div> 
<section>item 1 <p id="p1"> mini item 1 </p>
</section>
<section>item 2 <p id="p2"> mini item 2 </p>
</section>
<section>item 3 <p id="p3"> mini item 3 </p>
</section>
</div>
 
</body>
</html>
