<html>
  <head>
    <title>tables and input tags</title>
  </head>
  <body
  <!--tables-->
    <table border="1" style=border-collapse:collapse>
      <!--tr:table row-->
      <tr>
        <!--td:table data-->
        <td>1</td>
        <td>2</td>
        
      </tr>
      <tr>
        <td>3</td>
        <td>4</td>
      </tr>
      </table>
      </body>
</html>

Programs:
1))))))))))))))))))))))))))

<html>
  <head>
    <title>tables and input tags</title>
  </head>
  <body
  <!--tables-->
    <table border="4" style=border-collapse:collapse>
      <!--tr:table row-->
      <tr>
        <th>company name</th>
        <th>mail id</th>
      </tr>
      <tr>
        <!--td:table data-->
        <td>wipro</td>
        <td>abc@wipro.com</td>
       </tr>
      <tr>
        <td>nasa</td>
        <td>xyz@nasa.com</td>
      </tr>
      </table>
      </body>
</html>

2)))))))))))))))))))))))))))))))))

<html>
  <head>
    <title>tables and input tags</title>
  </head>
  <body
  <!--tables-->
    <table border="4" style=border-collapse:collapse>
      <!--tr:table row-->
      <tr>
        <th>company name</th>
        <th>mail id</th>
        <th>phone no</th>
        <th>about us</th>

      </tr>
      <tr>
        <!--td:table data-->
        <td>wipro</td>
        <td>abc@wipro.com</td>
        <td>12345</td>
        <td>wipro ltd</td>
        
      </tr>
      <tr>
        <td>nasa</td>
        <td>xyz@nasa.com</td>
        <td>23456</td>
        <td>nasa ltd</td>
      </tr>
      <tr>
        <td>devtown</td>
        <td>xyz@devtown.com</td>
        <td>34567</td>
        <td>devtown ltd</td>
        
      </tr>
      </table>
      </body>
</html>

3)))))))))))))))))))))))))))))))))))

<html>
  <head>
    <title>tables and input tags</title>
  </head>
  <body
  <!--tables-->
    <table border="4" style=border-collapse:collapse>
      <!--tr:table row-->
      <!--rowspan,colspan-->
      <tr>
        <th>company name</th>
        <th>mail id</th>
        <th>phone no</th>
        <th>about us</th>
      </tr>
      <tr>
        <!--td:table data-->
        <td  colspan="5">wipro</td>
        <!--<td>abc@wipro.com</td>-->
        <!--<td>12345</td>-->
        <!--<td>wipro ltd</td>-->
        
      </tr>
      <tr>
        <td rowspan="2">nasa</td>
        <td>xyz@nasa.com</td>
        <td>23456</td>
        <td>nasa ltd</td>
      </tr>
      <tr>
        <!--<td>devtown</td>-->
        <td>xyz@devtown.com</td>
        <td>34567</td>
        <td>devtown ltd</td>
        
      </tr>
      </table>
      </body>
</html>

4))))))))))))))))))))))))))))

<html>
  <head>
    <title>tables and input tags</title>
  </head>
  <body
  <!--tables-->
    <table border="4" style=border-collapse:collapse>
      <!--tr:table row-->
      <!--input tags-->
     <label>UserName:</label> 
      
      <input type+"text" placeholder="plz enter ur name"reqired/>
      <br/>
      <br/>
      <label>Password:&nbsp;&nbsp</label>
      <input type"password" placeholder="plz enter ur pwd"required/>
      </br>
      </br>
      <label>Gender:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp</label>
      <!--<input type="text" placeholder="plz enter ur gender"/>-->
      <input type="radio" name="gender"/><label>male</label>
      <input type="radio" name="gender"/><label>female</label>
      <input type="radio" name="gender"/><label>prefer not to say</label>
      <hr/>
      <tr>
        <th>company name</th>
        <th>mail id</th>
        <th>phone no</th>
        <th>about us</th>
      </tr>
      <tr>
        <!--td:table data-->
        <td  colspan="5">wipro</td>
        <!--<td>abc@wipro.com</td>-->
        <!--<td>12345</td>-->
        <!--<td>wipro ltd</td>-->
        
      </tr>
      <tr>
        <td rowspan="2">nasa</td>
        <td>xyz@nasa.com</td>
        <td>23456</td>
        <td>nasa ltd</td>
      </tr>
      <tr>
        <!--<td>devtown</td>-->
        <td>xyz@devtown.com</td>
        <td>34567</td>
        <td>devtown ltd</td>
        
      </tr>
      </table>
      </body>
</html>

5))))))))))))))))

<html>
  <head>
    <title>forms in html</title>
  </head>
  <body>
    <!--forms-->
    <table>
      <tr>
        <td>
           <label>UserName:</label>
      <input type="text" placeholder="please enter ur username"/>
        </td>
        </tr>
        </br>
        </br>
        <tr>
        <td>
          <label>Password:</label>
      <input type="text" placeholder="please enter ur password"/>
      </td>
      </tr>
      <tr>
        <td>
       <label>Gender:</label>
      <input type="radio"name="Gender"/><label>male</label> 
      <input type="radio"name="Gender"/><label>female</label> 
      <input type="radio"name="Gender"/><label>prefer not to say</label> 
        </td>
      </tr>
      </br>
      </br>
      <tr>
        <td>
       <label>select course you aware about:</label>
      <input type="checkbox"  name="course"/><label>c</label>
      <input type="checkbox"  name="course"/><label>c++</label>
      <input type="checkbox"  name="course"/><label>java</label>
      <input type="checkbox"  name="course"/><label>python</label> 
        </td>
      </tr>
      </br>
      </br>
      <tr>
      <td>
          <label>Choose ur course:</label>
      <select>
        <option value=""></option>
        <option value="web">web development</option>
        <option value="ml">machine learning</option></option>
        <option value="ds">data scienece</option>
        <option value="ai">ai</option>
        <option value="bd">big data</option>
        </select>
        </td>
      </tr>
      </br>
      </br>
      <tr>
        <td><label>submit</label></td>
         <td> <input type="submit"/></td>
        <td><label>reset</label></td>
        <td><input type="reset"/></td>
      </tr>
    </table>
    <br/>
    <hr/>
    <form>
       <label>UserName:</label>
      <input type="text" placeholder="please enter ur username" />
      <br/>
      <br/>
      <label>Password:</label>
      <input type="text" placeholder="please enter ur password"/>
      <br/>
      <br/>
      <label>Gender:</label>
      <input type="radio"name="Gender"/><label>male</label> 
      <input type="radio"name="Gender"/><label>female</label> 
      <input type="radio"name="Gender"/><label>prefer not to say</label> 
      <br/>
      <br/>
      <label>select course you aware about:</label>
      <input type="checkbox"  name="course"/><label>c</label>
      <input type="checkbox"  name="course"/><label>c++</label>
      <input type="checkbox"  name="course"/><label>java</label>
      <input type="checkbox"  name="course"/><label>python</label>
      <br/>
      <br/>
      <label>Choose ur course:</label>
      <select>
        <option value=""></option>
        <option value="web">web development</option>
        <option value="ml">machine learning</option></option>
        <option value="ds">data scienece</option>
        <option value="ai">ai</option>
        <option value="bd">big data</option>
        </select>
        <br/>
        <br/>
        <input type="submit"/>
        <input type="reset"/>
        </form>
  </body>
</html>


6)))))))))))))))))))))))))))))))))))))))

<html>
  <head>video,audio,iframe and sementic tags</head>
  <body>
    <h6>here is our video displayed on ui</h6>
    <!--.mp4,.ogg-->
    <video controls  autoplay loop width=350 height=240>
      <source src="sample.mp4" type="video/mp4"/>
      <!--<source src="sample.mp4" type="video/ogg"/>-->
     hey your video does not support video tag
    </video>
    <video controls autoplay loop width=320 height=240 src="sample.ogg">
    </video>
    <audio controls autoplay loop>
      <source src="" type="audio/mp4"/>
    </audio>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/mChdjV2mEsM?si=VFKRMLVeswSVloIo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
    
  </body>
</html>


7)))))))))))))))))))))))))))))))))))))))))))))))))
SEMANTIC TAGS
<html>
  <head>semantic tags</head>
  <body>
    <aside>
      <header>
    <h4>here is my main heading</h4>
    <h6>here is my sub heading</h6>
    </header>
    <section>
      <p>jhki</p>
      <h4>jkhu</h4>
    </section>
    <!--<pattern attribute></pattern>-->
    <input type="text" pattern="[a-z0-9]+@[a-z0-9]+\.[a-z]$"/>
    </body>
</html>

INLINE CSS
<html>
  <head>
    <title>
      intro to css
    </title>
     <!--< 3 diifeent to add css file to our html file-->
     <!-->>inline css-->
     <!-->>internal css/embeeded css-->
     <!-->>external css-->
     <!--/>-->
     <!--<inline css/>-->
     <h4 style="background:black;color:white";>hey its h4 heading tag</h4>
  </head>
</html>

INTERNAL OR EMBEDED CSS
<html>
  <head>
    <title>
      intro to css
      </title>
      <style>
       h4{
         background-color: black;
         color:white;
       }
      </style>
      <!--<internal css>-->
     <h4>hey its h4 heading tag</h4>
  </head>
</html>

EXTERNAL CSS(NOT CORRECT CODE)))))))))
<html>
  <head>
    <title>
      intro to css
      </title>
      <link rel="stylesheet" href=""
  </head>
  <h4>hey h4 is my heading tag</h4>
    h4{
    background color:black;
    color:white;
    border:2px solid red;
    border-radius:50%  
</html>

8))))))))))))))))))))))))))))))))))))))))))
selectors and box modelssss
html
<html>
  <head>
    <title>selectos in css</title>
    <link href="./day11.css" rel="stylesheet">
    </head>
  <body>
    <h2>hey this is h2-count1</h2>
    <h2>hey this is h2-count2</h2>
    <h2>hey this is h2-count3</h2>
    <h2>hey this is h2-count4</h2>
    <p>hey its p1</p>
    <p>hey its p2</p2>
  </body>
</html>

cssssss

/*element selector*/
/*h2{
    color:yellow;
    background:black;
}*/
/*body{
    color:yellow;
    background:black;
}*/
/*element selector list*/
/*h2,p{
    color:yellow;
    background:black;
}*/
/*selector*/
    body{
    color:yellow;
    border:2px red dotted;
    background:black;
    
    }
html>
  <head>
    <title>selectos in css</title>
    <link href="./day11.css" rel="stylesheet">
    </head>
  <body>
    <h2 class="h2classselector">hey this is h2-count1</h2>
    <h2>hey this is h2-count2</h2>
    <h2 id="h2count3">hey this is h2-count3</h2>
    <h2 class="h2classselector">hey this is h2-count4</h2>
    <p>hey its p1</p>
    <p>hey its p2</p2>
</body>
</html> 
csss:/*5class selector
    .h2classselector{
    color:pink;
    border:2px solid blue;
    background:black;
    width:40px;
    height:40px;
    border-radius:50%

<html>
  <head>
    <title>selectos in css</title>
    <link href="./day11.css" rel="stylesheet">
    </head>
  <body>
<ol>
    <li><a>link1</a></li>
    <li><a>link2</a></li>
    <li>link3 plaintext-1></li>
    <li>link4 plain text-2</li>
    <a>out of list anchor tag-link3</a>
  </body>
</html>

css:/*descent selector*/
parent any child
     /*li a{
        color:white;
        background:black;

    }*/
    /*a{
        color:white;
        background:black;
    }*/
    /*i{
        color:yellow;
        background:black;

    }*/

<html>
  <head>
    <title>selectos in css</title>
    <link href="./day11.css" rel="stylesheet">
    </head>
  <body>
<h1> <b>
    hey this is my  outer h1 hey its within h1 and its bold in nature but not italic
    <u>
    <i> hey its bold in nature and itellics in nature</i>
  </u>
  </b>
    <i> hey its not bold in nature and itellics in nature</i>
    </h1>

  </body>
</html> 

css:above one desecent selector

/*direct child*/
parent>direct child
<html>
  <head>
    <title>selectos in css</title>
    <link href="./day11.css" rel="stylesheet">
    </head>
  <body>
<h1> <b>
    hey this is my  outer h1 hey its within h1 and its bold in nature but not italic
    <u>
    <i> hey its bold in nature and itellics in nature</i>
  </u>
  </b>
    <i> hey its not bold in nature and itellics in nature</i>
    </h1>
  </body>
</html>
css::/*direct child*/
/*b> i {
    colors:yellow;
  background:black;
} (NO COLORS IT SHOWS BECAUSE I IS CHILD OF U NOT B SO U NEED TO WRITE U TO GET COLORS)  */
u>i{
    color:yellow;
        background:black;
}


9))))))))))))))))))))))
<html>
<hrad>
<title>selectors in css</head>
<style>
 (internal( h6 {
    color:red;
    background:purple;
  }
  <link href="day11.css" rel="stylesheet"/>
  </head>
  <body>
  <h6 style="color:aqua;background:black;">
  hey it has inline internal and external
  </h6>
  </body>
  </html>
  
 css::(extternal)h6{
    color:brown;
    background:purple;
}
css:h6{
    border:2px solid;
    padding:20px;or padding:0px 10px 15px 20px;
    padding top:10px;
    padding right:20px;
    padding bottom:20px;
    padding left:20px;
    margin:20px;
    margin:0px 10px 15px 20px;
    
10)))))))))))))))))))))))))))))


<html>
    <head>
        <title>Box Model, Display and Position in CSS</title>
        <link rel="stylesheet" href="./day-12-boxModelDisplayAndPosition.css" />
    </head>
    <body>
        <!-- Box Model -->
        <!-- <h6>Hey this is an example with respect to Box Model</h6> -->

        <!-- Display in CSS -->
        <!-- 
            >> block
            >> inline
            >> inline-block
         -->

         <!-- Block: It will take entire width of ur screen -->
         <!-- <div>
            <div class="displayInCss1">Segment 1</div>
            <div class="displayInCss2">Segment 2</div>
         </div> -->


         <!-- Inline: It will take what space is required -->
         <!-- <div>
            <div class="displayInCss1">Segment 1 </div>
            <div class="displayInCss2">Segment 2 </div>
         </div> -->

         <!-- Inline-Block: Where it is a combination of both 1 n 2 -->
         <!-- <div>
            <div class="displayInCss1">Segment 1 </div>
            <div class="displayInCss2">Segment 2 </div>
         </div> -->



         <!-- Postion in CSS -->

         <!-- 
            >> static (default)
            >> relative
            >> absolute
            >> fixed
            >> sticky
          -->

          <!-- 
            Offset: top, right, bottom, left
           -->

           <h3>Hello this is an example wrt to positions in CSS</h3>

           <p>Hey its just a para over here ...</p>

           <span class="positionInCss">hello this is an example with respect to Position in CSS</span>

</body>
</html>


css::/* * {
    box-sizing: border-box;
    /* padding: 0;
    margin: 0; 
} */



/* h6{
    background-color: black;
    color: white;
    border: 2px solid red; */
    /* padding-left: 15px;     */
    /* padding: 10px 0 0 15px; */
    /* margin-left: 20px; */
    /* margin: 0 0 0 20px;
} */

 /* top right bottom left (clk wise directions) */
/* 
Spacings:
    Padding => Internal to Box/Border
    Margin  => External to Box/Border
*/

/* ctrl + alt + down key */

/* block */
/* .displayInCss1{
    background-color: yellow;
    color: aqua;
    height: 55px;
    width: 40px;
    display: block;
}

.displayInCss2{
    display: block;
    background-color: red;
    height: 45px;
    color: white;
} */

/* 
*{
    padding: 0;
    margin: 0;
} */

/* inline */
/* .displayInCss1{
    background-color: yellow;
    color: aqua;
    height: 55px;
    width: 40px;
    display: inline;
}

.displayInCss2{
    display: inline;
    background-color: red;
    height: 45px;
    color: white;
} */


/* inline-block */
/* .displayInCss1{
    background-color: yellow;
    color: aqua;
    height: 55px;
    width: 40px;
    display: inline-block;
}

.displayInCss2{
    display: inline-block;
    background-color: red;
    height: 45px;
    width: 80px;
    color: white;
} */


/* Static Position */

/* .positionInCss{
    position: static;
    background-color: black;
    color: white;
    border: 1px solid red;
} */

/* Relative Position */
.positionInCss{
    position: static;
    top: 80px;
    background-color: black;
    color: white;
    border: 1px solid red;
}



11))))))))))))))))))))))))))
    Pseudo Classes:
            >> These are mainly used to apply styles to a particular state of an element/tag.
 -->

 <!-- 
    button states:
        >> Hover (Universal)
        >> Active
        >> Focus
  -->
 <!DOCTYPE html>
 <html>
    <head>
        <title>Pseudo Classes & Pseudo Elements in CSS</title>
        <link rel="stylesheet" href="./day-14-cssPseudoClassesAndPseudoElements.css" />
    </head>
    <body>
        <!-- PseudoClasses -->
        <!-- <button>Click On Me &#128526;</button>
        <br /><br />
        <a href="https://www.google.com" target="_blank">Click here to know abt devTown &#128578;</a> -->

        <!-- ctrl + alt+ down key -->
        <!-- <br/><br/>
        <div class="parent">
            <span class="child">Hello Guys</span>
            <span class="child">Hello Guys</span>
            <span class="child">Hello Guys</span>
            <span class="child">Hello Guys</span>
            <span class="child">Hello Guys</span>
            <span class="child">Hello Guys</span>
            <span class="child">Hello Guys</span>
            <span class="child">Hello Guys</span>
            <span class="child">Hello Guys</span>
            <span class="child">Hello Guys</span>
        </div> -->


        <!-- Pseudo Elements -->

        <!-- <h1> client</h1> -->
        <!-- <h1>hello client g'morning</h1> -->
        <!-- hello client g'morning -->

        <div class="shape"></div>
    </body>
 </html>



css::::
    Pseudo Classes:
            >> These are mainly used to apply styles to a particular state of an element/tag.
 -->

 <!-- 
    button states:
        >> Hover (Universal)
        >> Active
        >> Focus
  -->
 <!DOCTYPE html>
 <html>
    <head>
        <title>Pseudo Classes & Pseudo Elements in CSS</title>
        <link rel="stylesheet" href="./day-14-cssPseudoClassesAndPseudoElements.css" />
    </head>
    <body>
        <!-- PseudoClasses -->
        <!-- <button>Click On Me &#128526;</button>
        <br /><br />
        <a href="https://www.google.com" target="_blank">Click here to know abt devTown &#128578;</a> -->

        <!-- ctrl + alt+ down key -->
        <!-- <br/><br/>
        <div class="parent">
            <span class="child">Hello Guys</span>
            <span class="child">Hello Guys</span>
            <span class="child">Hello Guys</span>
            <span class="child">Hello Guys</span>
            <span class="child">Hello Guys</span>
            <span class="child">Hello Guys</span>
            <span class="child">Hello Guys</span>
            <span class="child">Hello Guys</span>
            <span class="child">Hello Guys</span>
            <span class="child">Hello Guys</span>
        </div> -->




        <!-- Pseudo Elements -->

        <!-- <h1> client</h1> -->
        <!-- <h1>hello client g'morning</h1> -->
        <!-- hello client g'morning -->

        <div class="shape"></div>
    </body>
 </html>


1}}}}}}}}}}}}}}}}}}}}}}}}}}

animations
<html>
  <head>
    <title>animations</title>
    <link href="./day15.css" rel="stylesheet"/>
  </head>
  <body>
    <button>click on me</button>
  </body>
</html>


css::
button{
    background-color: black;
    color:white;
    padding:10px;
    font-size: 20px;
    margin: 20px;;
    fond font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
    transition-delay:500ms;
    transition-duration:500ms;
    transition-property:back-ground color color;
    transition-timing-function:ease-out;
    transition-timing-function:ease-in;
}


button:hover{
    background-color: aqua;
    color:black;
}

html::<html>
  <head>
    <title>animations</title>
    <link href="./day15.css" rel="stylesheet"/>
  </head>
  <body>
    <div>hello</div>
    <div class=box>
    <div class="ball"></div>
    </div>
    
  </body>
</html>


css:::.box{
    background-color: black;
    height:100vh;
    /*width:100vw;*/
}
.ball{
    background-color: yellow;
    height:100px;
    width:100px;
    border-radius: 100%;
}
.ball:hover{
    animation:movetheball 5s ease-in-out forwards;
}
@keyframes movetheball {
    25%{
        transform:translate(400%,0);
    }
    50%{
        transform:translate(400%,600%);
        background-color: aqua;
    }
    75%{
        transform:translate(0,600%);
        background-color: white;
        border-radius: 25%;
    }
    100%{
        transform:translate(0,0_)
    }



1))))))))))))))))))))))))))))))))))))))
<html>
  <head>
    <title>
      media queeries
    </title>
  </head>
  <link href="./day13.css" rel="stylesheet"/>
  <body>
     <h2>hi to all all are nice to see u all here and best of luck</h2>
     <p>hi to all</p>
</html>
  


    css::
                     /*max width :it is<=1200px
                      min width:it is >=1200px
if screen size in range of 0-1200*/
@media only screen and (min-width:1200px){
    h2{
        fond-size:20px;
        color:yellow;
    }
    p{
        color:brown;
    }
}
/*if screen size in range of 0-800*/
@media only screen and (min-width:800px){
    h2{
        fond-size:20px;
        color:aqua
    }
    p{
        color:pink;
}
/*if screen size in range of 0-400*/
@media only screen and (min-width:800px){
    h2{
        fond-size:20px;
        color:red;;
    }
    p{
        color:blue;;
    }



/*if both th widths are maximum then which has higher value should be at top  will executed the styles*/
@media only screen and (max-width:800px){
    h2{
        fond-size:20px;
        color:yellow;
    }
    p{
        color:brown;
    }
}
@media only screen and (min-width:800px){
    h2{
        fond-size:20px;
        color:red;;
    }
    p{
        color:blue;;
    }
}


/*if both are minimum values the minimum value should be top or lesser value*/
@media only screen and (min-width:400px){
    h2{
        fond-size:20px;
        color:yellow;
    }
    p{
        color:brown;
    }

@media only screen and (min-width:800px){
    h2{
        fond-size:20px;
        color:red;;
    }
    p{
        color:blue;;
    }
}


13))))))))))))))))))
var obj name={
student=("Suhas",Surishetty")
}

var obj={
name="Suhas";
age=21
}
obj.age

var obj 2={
name="Suhas"
age=9
}
var obj={
name="ss"
age=22
}
var new arr=[obj1,obj2]

<!--string operations
slice operations-->
console.log("slice:",data.slice(1,2);
<!--data: hey
o/p:h y-->

<!--length o/p=3-->
<!--replace-->
console.log)("replace",data.replace("hey"."hi");
data=data.replace("hey","hi")
<!--include-->
console.log)("include",data.include("hey");
<!--index-->
var  new data="Suhas"
console.log("slice",newdata.slice(2,-2)
<!--o/p:h,a-->
<!--js operations-->
var num1=10;
var num2=2;
var sum=num1+num2;
console.log(sum);
<!--functions js-->
var sum=[a,b]=>{
console.log(a+b)
}
sum(4,5);

<!--array method-->.
var array={1,2,3,4}
console.log("current array=>",array);
var new array=array.map(data)=>data+2);
console.log("new array=>with map=>new array);
<!--o/p:current array ={1,2,3,4,5}
new array=>with map={3,4,5,6,7}-->
