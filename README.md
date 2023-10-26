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
p {width: 100px;
   height: 30px;
   border: 1px solid black;
   background-color: pink;
   font-align: centre;
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
<section>item 2 <p> mini item 2 </p>
</section>
<section>item 3 <p> mini item 3 </p>
</section>
</div>
 
</body>
</html>
