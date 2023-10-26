# Testing 
<html>
<head> 
<meta charset="utf-8">
<title> box model </title>
<style>
*{box-sizing: border-box;
   margin: 10px;
   padding: 0px;}
h1 {color: blue;}
section {width: 300px;
   height: 150px;
   border: 1px solid black;
   background-color: grey;
   float: left;
   position: relative;}  
p {width: 80px;
   height: 10px;
   border: 1px solid black;
   background-color: pink;
   float: left;
   position: absolute;
   top: 0px;
   right: 0px;}        
#p1{}
#p2{}
#p3{}
</style>
</head>
  
<body> 
<h1> Box model </h1>
<div> 
<section>item 1 <p> mini item 1 </p>
</section>
<section>item 2</section>
<section>item 3</section>
</div>
 
</body>
</html>
