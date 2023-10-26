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
   float: left;
   position: relative;}  
p {width: 150px;
   height: 50px;
   border: 1px solid black;
   text-align: centre;
   margin: 0px;
   float: left;
   position: absolute;
   top: 0px;
   right: 0px;}        
#p1{background-color: pink;}
#p2{background-color: green;}
#p3{background-color: yellow;}
/********** responsive media-queries **********/
.row {width: 100%;} 
/** for large devices **/
@media (min-width:992px) {.col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {float: left;} 
.col-lg-1 {width:8.33%;}
.col-lg-2 {width:16.66%;}
.col-lg-3 {width:25%;}
.col-lg-4 {width:33%;}     
.col-lg-5 {width:41.66%;}                 
.col-lg-6 {width:50%;}                    .col-lg-7 {width:58.33%;} 
.col-lg-8 {width:66.66%;} 
.col-lg-9 {width:74.99%;}                 .col-lg-10 {width:83.33%;}
.col-lg-11 {width:91.66%;} 
.col-lg-12 {width:100%;}                         
/** for md devices **/
@media (min-width:768px) and (max-width:991) {.col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {float: left;} 
.col-md-1 {width:8.33%;}
.col-md-2 {width:16.66%;}
.col-md-3 {width:25%;}
.col-md-4 {width:33%;}     
.col-md-5 {width:41.66%;}                 
.col-md-6 {width:50%;}                    .col-md-7 {width:58.33%;} 
.col-md-8 {width:66.66%;} 
.col-md-9 {width:74.99%;}                 .col-md-10 {width:83.33%;}
.col-md-11 {width:91.66%;} 
.col-md-12 {width:100%;}                          
/** for sm devices **/
@media (min-width:767px) {.col-lg-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {float: left;} 
.col-sm-1 {width:8.33%;}
.col-sm-2 {width:16.66%;}
.col-sm-3 {width:25%;}
.col-sm-4 {width:33%;}     
.col-sm-5 {width:41.66%;}                 
.col-sm-6 {width:50%;}                    .col-sm-7 {width:58.33%;} 
.col-sm-8 {width:66.66%;} 
.col-sm-9 {width:74.99%;}                 .col-sm-10 {width:83.33%;}
.col-sm-11 {width:91.66%;} 
.col-sm-12 {width:100%;}                                               
</style>
</head>
  
<body> 
<h1> Box model </h1>
<div class="row"> 
<section class="col-lg-3 col-md-6 col-sm-1" >item 1 <p id="p1"> mini item 1 </p>
</section>
<section class="col-lg-3 col-md-6 col-sm-1">item 2 <p id="p2"> mini item 2 </p>
</section>
<section class="col-lg-3 col-md-6 col-sm-1">item 3 <p id="p3"> mini item 3 </p>
</section>
</div>
 
</body>
</html>
