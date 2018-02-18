# new-repo
<!DOCTYPE html>
  <html>
    <head> 
     <title>My HTML </title>
     <link href="MyHTML.css" text="text/css" rel="stylesheet">
     <link href="https://fonts.googleapis.com/css?family=Lora" rel="stylesheet"> 
  <style>
    body {
        font-family: 'Lora', serif;
    }
  </style>
   </head>

<!--Website Begins -->

  <body> 
<!--Title section -->
     <div>
      <h1 class="title"> Building a Website</h1>
      <h3 id="author"> By: Kyla Trotter</h3>
      <form>
        <input class="LearnButton" type="button" value="Learn HTML"  onclick=window.location.href="https://www.codecademy.com/learn/learn-html" />
     </form> 

     </div>

<!--Getting Started -->
     <div> 
	<h2> Getting Started </h2>
         <p> In this website I give a brief overview of basic HTML tags that you can use to build a website. If you are looking to learn HTML in a greater depth you can click the link above to go to Codeacademy's program for learning HTML. </p>
         <p> Let's get started!</p>
         <ol>
            <li> First you need a text editor. On a PC running with Microsoft Windows you can access Notepad. On a Mac look for TextEdit.</li>
            <li> Enter into the text editor any of the code that you wish to build your website with like the code samples below.</li>
            <li> Once you are finished save the file and make sure to include ".html" at the end of the filename.</li>
            <li> To view the code in the browser double click the file.</li>
         </ol>
         <p> You can also download other specialized text editors used specifically for writing code.</p>
         <p > Now that you have you text editor ready you can build your website. There are many much advanced code you can use other than the basics I have listed here. </p>
 	<form> 
		<input class="MoreButton" type="button" value="Click for More!"onclick=window.location.href="https://www.w3schools.com/" />   
 	</form> 
         <p > I hope this site proves useful with your website building. <strong> Good Luck!</strong></p>
<!--Boilerplate Tags -->
     <div>
         <h2 id="boilerplate" class="h2s"> Boilerplate Tags </h2>
         <p> Boilerplate Tags are the necessary foundtion of every HTML document.</p>
         <ol  class="tags"> 	
	     <li> !DOCTYPE html- This is the first line of code in any HTML document. It tells the computer which programming language the following code will be. Once the computer understands which language is used it can begin to read              and translate the code.</li>
             <li> html- This tag contains all the HTML code.</li>
             <li> head- The <em> head </em> tag contains the title and information about the webpage. </li>
             <li> title- This tag goes inside the <em> head </em> tag and is used to title the webpage. NOTE: This does <strong> not </strong> appear on the actual page but the title is visible on the tab of your browser.</li>
             <li> body-This tag includes all visible HTML content code. Insert the <em> body </em> tag after the closing <em> head </em> tag.  </li>

       </ol>
      <img src="https://iconicdevs.com/wp-content/uploads/2016/12/The-HTML-Basics-HTML-Boilerplate.png" id="example1" height=250px width=450px class="images"/> 

   </div>

<!-- Heading section-->
   <div>
      <h2 id="headings" class="h2s"> Headings</h2>
      <p > To display text as a<strong> heading </strong> use <em> h </em> tags. There are six heading tags used for larger and smaller headings. The <strong> h1 </strong> tag is the largest.</p>
      <img src="http://kkfscs.weebly.com/uploads/1/4/1/8/14186235/2199400.jpg?425" id="example2" class="images"/> 
   </div>

<!-- Paragraph section-->
   <div>
      <h2 id="paragraphs"class="h2s"> Paragraphs </h2>
      <p >This is a Paragraph. To display text in <strong> paragraphs</strong> you can use the <em> p </em> element.</p>
      <img src="http://code4beginner.com/images/Html/HTML-Paragraph-Tag-1.png" id="example3" class="images"/>  
   </div>

<!--List section -->
   <div>
      <h2 id="listInfo" class="h2s"> Lists </h2>
      <p > There are two main types of lists: Ordered <em>(ol)</em> and Unordered<em> (ul)</em>. In an <strong>Ordered List</strong>  each list item is numbered. In an <strong> Unordered List</strong>  the text is formatted        in bullets. </p>
      <p> To make a list choose the kind of list you want to make and then add list items. For Every <strong>  List Item</strong> (<em> li </em>) you must include an opening list item tag and a closing tag. </p>
       <img src="http://kb.politemail.com/wp-content/uploads/2014/10/list-code.jpg" id="example4" class="images"/>
   </div>

<!--Link section -->
    <div> 
       <h2 class="h2s"> Links </h2>
       <p> To add a link to a webpage use the anchor element and <em> href</em> attribute. The anchor element includes the text of a link inside of it. You can turn elemnet into a link using the anchor tag. The <em> href</em>  attribute contains the actual url. </p>
       <p> Attributes are made up of: </p>
        <ol>
           <li> The name of the attribute </li>
           <li> The value of the attribute</li>
        </ol>
       <p> The href attribute's value is the URL <br> Another attribute is the target attribute. This attribute open a link into a new window. It has a value of <em>"_blank"</em> </p>
   
       <img id= "example5" class="images" src="https://www.html-5-tutorial.com/images/a-tag.gif"/>
       <p> There are more ways to use links. We can use links to link files together such as linking a CSS stylesheet to a HTM file. </p>
         <img class="images" src="https://www.codeproject.com/KB/HTML/754214/cssExternalStyle.png"/>
         <p> The other way to use links is to add fonts. By adding a link to the font you can use the font even if it isn't installed on the computer. 
	 <a href="https://fonts.google.com/" target="_blank">Google Fonts</a> is an excellent website for linking fonts. </p>
         <img class="images" id="example6" src="http://www.mclibre.org/consultar/htmlcss/img/google-fonts/google-fonts-03.png" />

 <!--Images section -->
     <div>
	<h2> Images</h2>
        <p>To add images use the <em> img </em> tag. The <em> img </em> tag only has an opening tag and requires a <em> src attribute </em>. The <em> src  </em> attribute's value is the URL of the image.</p>
        <p>There is another attribute that can be applied to images: the <em> alt </em> attribute. The value of the <em> alt </em> attribute is the image description.</p>
        <p> The <em> alt </em> attribute is used for:</p>
            <ol> 
               <li>If an image fails to load a user can read a brief description of the image. </li>
               <li> Visually impaired users who use a screen reading software may have the image description read aloud to them. </li>
            </ol>
        <img class="images" id="example7" src="https://don16obqbay2c.cloudfront.net/wp-content/uploads/b44b2bab-46b9-4de9-aa88-9603fdfb1437_Alt-Tags_HTML_Image_Code-1478591311.png" />
     </div>

<!--Non-visible Comments section -->
    <div>
        <h2> Non-visible Comments</h2>
       <p> Non-visible Comments are notes in the code that are only visible in the code not on the webpage. </p>
       <p> Non-visible Comments are used for:</p>
           <ol> 
              <li> Help you and others writing or reviwing the code understand it better.</li>
              <li>Allow to experiment with code without deleting</li>
           </ol>
       <img class="images" id="example8" src="http://clearcodedprogramming.com/wp-content/uploads/2016/07/commentHTML2.png"/>
    </div>

<!-- Colors section
      <div>
        <h2> Colors</h2>
       <p> Color can affect these design aspects:</p>
           <ol> 
              <li> The foreground color</li>
              <li>The background color</li>
           </ol>
	<p> You can style with:</p>
           <ol> 
              <li> color: this property styles an elemnet's foreground color</li>
              <li>background-color: this property</li>
           </ol>
       <img class="images" id="example8" src="http://clearcodedprogramming.com/wp-content/uploads/2016/07/commentHTML2.png"/>
    </div>
<!-- Tables Section-->
	<h2> Tables</h2>
         <p> With the <em> table</em> element you can:</p>
            <ul>
              <li> add rows using the table row element (tr)</li>
               <li>add data using the table data element (td)</li>
                 <li>add titles using the table heading element (th)</li>
            </ul> 
         <img class="images" id="example9" src="https://www.html-5-tutorial.com/images/table-tag.gif"/>
  </body>
  </html>
