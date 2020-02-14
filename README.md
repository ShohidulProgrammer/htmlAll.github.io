# htmlAll.github.io
In this repository I added all html tag and attribute for learning html for beginners. 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <!-- Provide list of keywords -->
    <meta name = "keywords" content = "html, javascript, PHP, Python">

    <!-- Provide description of the page -->
    <meta name = "description" content = "Simply Easy Learning by it home">

    <!-- Author information -->
    <meta name = "author" content = "it home">

    <!-- Page content type -->
    <meta http-equiv = "content-type" content = "text/html; charset = UTF-8">

    <!-- Page refreshing delay -->
    <meta http-equiv = "refresh" content = "30">

    <!-- Page expiry -->
    <meta http-equiv = "expires" content = "Wed, 21 June 2006 14:25:27 GMT">

    <!-- Tag to tell robots not to index the content of a page -->
    <meta name = "robots" content = "noindex, nofollow">

    <title>HTML ALL Tag</title>
    <base href="https://www.ithome.com/">

    <!-- style -->
    <!-- <link rel = "stylesheet" type = "text/css" href = "/css/style.css"> -->
    <style type = "text/css">
        .background {
           padding: 10px;
           margin: 90px;
           font-size:18px;
        }
     </style>

     <!-- javascript -->
     <script type = "text/JavaScript">
        function sendEmail() {
           alert("Are you sure you want ot  send a Email?");
        }

        function EventHandler() {
            alert("your mouse on the picture!!");
         }
     </script>
     <!-- <script src = "/html/script.js" type = "text/javascript"/></script> -->

</head>
<body class="background">
    <div>
        <h1>HTML Text Links <a name = "top"></a></h1>

        <div>
            <!-- head h1 to h6 -->
            <h1>This is h1 Head Line</h1>
            <h2>This is h2 Head Line</h2>
            <h3>This is h3 Head Line</h3>
            <h4>This is h4 Head Line</h4>
            <h5>This is h5 Head Line</h5>
            <h6>This is h6 Head Line</h6>
        </div>
       
        <hr>

        <div>
            <!-- Letter Style      -->
            <h3><u>Letter Style</u></h3>
            
            <!-- boald Letter -->
            <b>Boald Letter</b> <br>
            <strong>Strong Letter</strong> <br>
            <br>
            <big>big Letter</big> <br>
            <acronym title="Larg Text">acronym Letter</acronym> <br>

            <br>
            <!-- Italic Letter -->
            <i>Italic Letter</i> <br>
            <em>em Letter</em> <br>
            <dfn>dfn Letter</dfn> <br>
            <cite>cite Letter</cite> <br>

            <br>
            <small>small Letter</small> <br>
            <mark>mark Word</mark> <br>
            <p>Span use for some portion take <span style="color:brown">different style</span></p>
            
            <br>
            <strike>strike Word</strike> <br>
            <del>Del use for Delete Word</del> <br>

            <br>
            <ins>ins use for Inserted Word</ins> <br>
            
            <br>
            <q>q use for Qutation</q> <br>
            <tt>tt use for Monospaced Word</tt> <br>

            <hr>
            <h3>Letter Direction</h3>
            <p dir="ltr">Left to Right</p>
            <p dir="rtl">Right to Left</p>
            <p><bdo dir="rtl"></bdo> bdo dir rtl use for writting Direction or Bi-Direction Override with Right to Left </p>
            <p><bdo dir="ltr"></bdo> bdo dir ltr use for writting Direction or Bi-Direction Override with Left to Right </p>

            <hr>
            <p>abbr use for given a Name with tooltip eg, <abbr title="My Name">Shoikat</abbr></p>
            
            <p>
                address use for given a House Address. eg, <address>342/2, mirpur-1, dhaka-1216</address>
            </p>
            <p>kdb use for <kbd>Keyboard</kbd> Letter</p>

            <hr>
            <!-- subscript -->
            <p>a<sup>2</sup>  is sup </p>
            <p>H<sub>2</sub>O is sub</p>
            <hr>
            <!-- programming code writting style -->
            <pre> 
                <h4>pre style</h4>
                <!-- display as we write -->
                function add(a,b){
                    alert(a+b)
                }
            </pre>

            <code>
                <h4>Code Style</h4>
                main()
                {
                    int <var>a</var>, <var>b</var>, <var>varStyle</var>;
                }
            </code>
            <p>
                    samp use for program Output. eg, <samp>Hello World!</samp>
            </p>

            <hr>
            <p>
                <h4>Conditional comment</h4>
                <!-- <[if IE6]
                    Some Special instruction for IE6 here
                <![Endif] -->
            </p>
            
        </div>
        <hr>
        <div>
            <p>
                <h3>Align Style</h3>
                <!-- align -->
                <p align="left">Align Left</p>
                <p align="center">Align Center</p>
                <p align="right">Align Right</p>

                <hr>
                <!-- valign -->
                <p valign="middle">Valign Middle</p>
                <p valign="top">Valign Top</p>
                <p valign="buttom">Valign Bottom</p>
            </p>          
        </div>
        <hr>
        
        <div>
            <p>
                <img 
                onmouseover = "EventHandler()"
                src="http://2.bp.blogspot.com/-RoQQ5fACBTI/U1t3hEO8w3I/AAAAAAAAL4k/4gSg7FiYGqg/s1600/beautiful-images-wallpapers-(1).jpg" alt="boat beautiful-images-wallpapers" width="350" height="200" border="1" align="center"> 
                <br> <br>
                img src="folderName\imageFileName.jpg
            </p>
        </div>
        <hr>
        <div>
            <table 
                border="5" 
                width="450"
                hight="200"
                align="center"
                bordercolor="white" bgcolor="yellow" 
                cellpadding="20" cellspacing="35" 
               font style="color:red"
            >
            

                <thead>
                    <tr>
                        <td colspan="2" align="center">This is Table Header</td>
                    </tr>
                    <tr>
                        <td>Head1</td>
                        <td>Head2</td>
                    </tr>
                </thead>
                
                <tr>
                    <td>r1 value1</td>
                    <td>r1 value2</td>
                </tr>
                <tr>
                    <td>r2 value1</td>
                    <td>r2 value2</td>
                </tr>
                <tr>
                    <td>r3 value1</td>
                    <td>r3 value2</td>
                </tr>
                <tr>
                    <td>r4 value1</td>
                    <td>r4 value2</td>
                </tr>
                 
                <tfoot>
                        <tr rowspan="2" colspan="3">
                            This is Table Footer
                        </tr>
                    </tfoot>
                 
                </font>
            </table>
        </div>
        <hr>

        <div>
            <p><h3>html List</h3></p>
            <p>
                <ul type="square">
                    <h5>unorder sqyare type List</h5>
                    <li>value 1</li>
                    <li>value 1</li>
                    <li>value 1</li>
                    <li>value 1</li>
                </ul>
            </p>

            <p>
                <ul type="disc">
                    <h5>unorder sqyare type List</h5>
                    <li>value 1</li>
                    <li>value 1</li>
                    <li>value 1</li>
                    <li>value 1</li>
                </ul>
            </p>

            <p>
                <ul type="circle">
                    <h5>unorder sqyare type List</h5>
                    <li>value 1</li>
                    <li>value 1</li>
                    <li>value 1</li>
                    <li>value 1</li>
                </ul>
            </p>

            <p>
                <ol type="1">
                    <h5>order number type List</h5>
                    <li>value 1</li>
                    <li>value 1</li>
                    <li>value 1</li>
                    <li>value 1</li>
                </ol>
            </p>

            <p>
                <ol type="I">
                    <h5>order Capital Roman number type List</h5>
                    <li>value 1</li>
                    <li>value 1</li>
                    <li>value 1</li>
                    <li>value 1</li>
                </ol>
            </p>

            <p>
                <ol type="i">
                    <h5>order small roman number type List</h5>
                    <li>value 1</li>
                    <li>value 1</li>
                    <li>value 1</li>
                    <li>value 1</li>
                </ol>
            </p>

            <p>
                <ol type="A">
                    <h5>order Capical Letter type List</h5>
                    <li>value 1</li>
                    <li>value 1</li>
                    <li>value 1</li>
                    <li>value 1</li>
                </ol>
            </p>

            <p>
                <ol type="a">
                    <h5>order smmall Letter type List</h5>
                    <li>value 1</li>
                    <li>value 1</li>
                    <li>value 1</li>
                    <li>value 1</li>
                </ol>
            </p>

            <p>
                <ol type="a" start="3">
                    <h5>order start from difined Letter type List</h5>
                    <li>value 1</li>
                    <li>value 1</li>
                    <li>value 1</li>
                    <li>value 1</li>
                </ol>
            </p>

            <dl>
                <h5>Defination List with Defination Tag and Defination Description</h5>
                <dt>HTML</dt>
                <dd>Hyper Text Merkup Language</dd>

                <dt>CSE</dt>
                <dd>Computer Scinence and Engineering</dd>
            </dl>

        </div>

        <hr>
        <div>
            <h3>Font Style</h3>
            <font size="30" color="darkorange" face="Arial Bold Italic">font size="30" <br> color="darkorange"<br> face="Arial Bold Italic" </font>
        </div>

        <hr>
        <div>
            <h3>Html Form</h3>
            <form action="https://mail.google.com">
                <font size="4">
                    <p>
                        Select Image: 
                        <input type = "file" name = "fileupload" accept = "image/*" />
                    </p>
                    <p for="Name">
                        Name: 
                        <input type="text" name="name" value="Enter your Name" maxlength="30" tooltip="Enter Your Name">
                    </p>
                    <p>
                        Password: <input type="password" name="password" value="Password here" tooltip="Password here">
                    </p>
                    
                    <p>
                        Gender: 
                        <input type = "radio" name = "gender" value = "Male"> Male
                        <input type = "radio" name = "gender" value = "Female"> Female
                    </p>

                    <p>
                        Department:
                        <select name = "department">
                            <option value = "CSE" selected>CSE</option>
                            <option value = "EEE">EEE</option>
                            <option value="BBA">BBA</option>
                        </select>
                    </p>

                    <p>
                        Interestd in: 
                        <input type = "checkbox" name = "programming" value = "on"> Coding
                        <input type = "checkbox" name = "gmae" value = "on"> Play Games
                        <input type = "checkbox" name = "Study" value = "on"> Study
                    </p>


                    <p>
                        Comment : <br />
                        <textarea rows = "5" cols = "50" name = "description">
                            Enter your comment here...
                        </textarea>
                    </p>

                    <p>
                        <input type = "submit" name = "submit" value = "Submit"/>
                        <input type = "reset" name = "reset"  value = "Reset" />
                        <input type = "button" name = "send" value = "Send Email" onclick = "sendEmail()"/> <br> <br>
                        <input type = "image" name = "imagebutton" width="100" height="50" src = "https://i.gadgets360cdn.com/large/gmail_logo_1508252521961.jpg" />
                        <br><br>
                        here input is: <input type = "hidden" name = "pagename" value = "This page name" /> hidden
                    </p>
                    
                    
                </font>
            </form>

        </div>
        <hr>
        <div>
            <p>
                    <!-- <embed src = "/html/yourfile.swf"  -->
                <embed src = "https://thumbs.gfycat.com/WigglyBigAmoeba-size_restricted.gif" width = "950" height = "400" >
                    <!-- <noembed><img src = "yourimage.gif"  -->
                    <noembed><img src = "https://uploads.scratch.mit.edu/users/avatars/26547619.png" alt = "Alternative Media" ></noembed>
                </embed>
                <br>

                BackGround Sound: 
                <bgsound src = "/html/yourfile.mid">
                    <noembed><img src = "yourimage.gif" ></noembed>
                </bgsound>
            </p>
        </div>
        
        <hr>
        <div>
            Marquee: 
                <marquee>This is called marquee</marquee> <br>
                <marquee width = "50%">width 50% start from half of window</marquee> <br>
                <marquee direction = "right">direction right will scroll from left to right</marquee> <hr>
                <marquee direction = "up">direction up This text will scroll from bottom to up</marquee>
                <marquee direction = "down">direction down This text will scroll from up to bottom</marquee>
                
        </div>

    </div>
    
    <hr>
    <div style = "width:100%">

        <div style = "background-color:#d69915; width:100%">
            <font color="white" face="new roman" size="10"><center>This is Web Page Main title</center>
                <center>
                    <input type = "button" name = "home" value = "Home" onclick = "goHome()"/>
                    <input type = "button" name = "ourProduct" value = "our Product" onclick = "goProduct()"/>
                    <input type = "button" name = "aboutUs" value = "About Us" onclick = "goAboutUs()"/>
                    <input type = "button" name = "address" value = "Address" onclick = "goAddress()"/>
                </center>            
            </font>
        </div>
           
        <div style = "background-color:rgb(237, 243, 200); height:200px; width:150px; float:left;">
            <div style="padding: 5px">
                <div><b>Main Menu</b></div>
                HTML<br />
                PHP<br />
                PERL...
            </div>
        </div>
           
        <div style = "background-color:rgb(192, 179, 103); height:200px; width:75%; float:left;" >
               <p style="padding: 10px;">Technical and Managerial Tutorials</p>
        </div>
        
        <div style = "background-color:rgb(237, 243, 200); height:200px; width:150px; float:right">
            <div style="padding: 10px">
                <div><b>Right Menu</b></div> 
                HTML<br />
                PHP<br />
                PERL...
            </div>
        </div>
           
        <div style = "background-color:#d69915; clear:both;">
               <center>
                  Copyright © 2019 ItHome.com
               </center>
        </div>
               
    </div>
    <a href="mailto:shoikat.cse@gmail.com?subject = Feedback&body = Message" style="font-size: 20px;">Email Me</a>
    <br>
    <a href = "file:///F:/STUDY/programming/web%20base%20workplace%20source%20code/Front%20end/html/html%20all%20tag.html#top">Go to the Top</a>


</body>
</html>
