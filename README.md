ASSIGNMENT_part1


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            font-size: 10px;
        }
        #abh1{
            font-size: 2rem;
        }
        abh2{
               font-size: 4em ;
        }
        #abh3{
             font-size: 5vh;
        }
        #abh4{
            font-size: 5vw;
        }
        #abh5{
            font-size: 15px;
        }

    </style>
</head>
<body>
    <h1 >CSS_ASSIGNMENT_PART1 </H1
        
 Demo specifying the difference between rem,em,vh,vw,px.
    </h1>

    <h1 id="abh1">MY NAME IS ABHINAV BHARDWAJ</h1>

    <h1 id="abh2">MY NAME IS ABHINAV BHARDWAJ</h1>

    <h1 id="=abh3">MY NAME IS ABHINAV BHARDWAJ</h1>


    <h1 id="abh4">MY NAME IS ABHINAV BHARDWAJ</h1>
    <h1 id="abh5">MY NAME IS ABHINAV BHARDWAJ</h1>
</body>
</html>



ASSIGNMENT_part2




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="abhinav2.css">
    
</head>
<body>
    <h1 >CSS_ASSIGNMENT_PART2 </h1>
        
 

    <h1 id="abh1">MY NAME IS ABHINAV BHARDWAJ</h1>

    <h1 id="abh2">MY NAME IS ABHINAV BHARDWAJ</h1>

    <h1 id="=abh3">MY NAME IS ABHINAV BHARDWAJ</h1>

    <h1 id="abh4">MY NAME IS ABHINAV BHARDWAJ</h1>

    <h1 id="abh5">MY NAME IS ABHINAV BHARDWAJ</h1>
</body>
</html>


EXTERNAL_CSS_CODE

body{
            font-size: 10px;
        }
        #abh1 , #abh2 , #abh4{
            font-size: 2em;
        }
        #abh3 , #abh5 {
            font-size: 2em;
           background-color: brown;
        }







Assignment_part3



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
    <title style="display: inline-block;">CSS(PART3)</title>
    <style>
      .abhi1 > p {
        
        background-color: red;
      }
      .para2 + p{
        background-color: yellow;
      }
      .para3 ~ p{
        background-color: green;
      }
  </style>   
</head>
<body>
  <h1 style="display: inline-block;">CSS(PART3)</h1>
    <h2  style="font-size: 50px;">Child Selector</h2>

<p>The child selector (>) selects all elements that are the children of a specified element.</p>
 <div class="abhi1" >  

    <p>MY NAME IS ABHINAV BHARDWAJ</p>
    <p>I AM FROM KIET GROUP OF ONSTITUTIONS , GHAZIABAD </p>
    <section> <p> I LOVE TO PLAY BADMINTON</p></section>
    <p>I LOVE TO PLAY CRICKET ALSO</p>
  </div>
  <p>I AM A NATIONAL BASKETBALL PLAYER SO MY HOBBIES INCLUDE PLAYING BASKETBALL,(NOT INSIDE DIV)</p>
  <p>I HAVE KEEN INTEREST IN FRONT-END TECHNOLOGIES,(NOT INSIDE DIV)</p>



  <h2 style="font-size: 50px;">Adjacent Sibling Selector</h2>

<p>The + selector is used to select an element that is directly after another specific element.</p>
<p>The following example selects the first p element that are placed immediately after div elements:</p>


<div class="para2">
  <p>My name is</p>
  <p>ABHINAV BHARDWAJ</p>
</div>

<p>PLAY BASKETBALL. After a div.</p>
<p>PLAY BADMINTON. After a div.</p>

<div class="para2">
  <p>MOTIVATED STUDENT in the div.</p>
  <p>HARDWORKING STUDENT in the div.</p>
</div>

<p>NATIONAL LEVEL. After a div.</p>
<p>BASKETBALL PLAYER. After a div.</p>


<h2  style="font-size: 50px;">General Sibling Selector</h2>

<p>The general sibling selector (~) selects all elements that are next siblings of a specified element.</p>

<p>BASKETBALLER</p>

<div class="para3">
  <p>FOTTBALLER</p>
</div>

<p>BADMINTON</p>
<code>Some code.</code>
<p>CRICKET</p>


</body>
</html>






ASSIGNMENT_part4




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
 <style> 
        .abh1 {
          width: 50px;
          height: 50px;
          background:greenyellow;
          transition: width 1s;
        }
        
        .abh1:hover {
          width: 100px;
        }


        div.param {
                width: 100px;
                height: 100px;
                background-color:pink;
                -ms-transform: rotate(18deg); 
                 transform: rotate(18deg);
}
</style>
</head>
<body>
    <h1>The transition Property(Assignment_4)</h1>
</br>

<p>click on the div element below, to see the transition effect:</p>

<div class="abh1"></div>

<h1>The transform Property</h1>

<h2>transform: rotate(20deg):</h2>
<div class="param">Hello World!</div>
<br>
</body>
</html>
