# coding-notes
notes on html
html

basic frame of webpage
<!DOCTYPE html>
<html>
<head>
<title>Bananas!</title>
</head>
<body>
</body>
</html>

<!DOCTYPE html>
<html>
	<head> every page has a head and a body
		<title>title doesn’t show up on page</title>
	</head>
</html>very end of doc

<body>
</body>put at end of page before </html>

	<p>shows up
	</p>

		<h1>largest size heading
		</h1>

			<a href=“https://www.codeacademy.com”>Code Academy</a> link to a word
			</a>

			<img src”=url” /> inserts a picture

			If you want the picture to be a link:

			<a href=“https://www.codeacademy.com”>
			<img src”=url” /> 
			</a>

lists go in the body
<ol> for ordered list
	<li> each item with a number</li>
</ol>
<ul> for unordered list with bullets

comments don't show up
<!--Make me into a comment.-->

styling in html
<p style="font-size: 10px"> Some text for you to make tiny! </p>
<p style="color: red; font-size: 10px">But the bear got hungry and ate the duck.</p>
<li style="font-size: 16px; font-family: Arial">This item is big Arial.</li>  other items can be styled
<p style="font-size: 20px; color: blue; font-family: Arial">>A truly spectacular paragraph!</p>

background and list colors
<body style="background-color: brown;">
		<h3>Favorite Football Teams</h3>
			<ol style="background-color: yellow">
				<li>The Hawthorn Football Club</li>	
				<li>San Franscisco 49ers</li>
				<li>Barcelona FC</li>
			</ol>			
	</body>
	
centering
<h3 style="text-align: center;">Favorite Football Teams</h3>
<li style="text-align: left;">The Hawthorn Football Club</li>	

Bold just a word
<p>No I don't. I'm <strong>too</strong> busy eating cake.</p>
Italics
<p>I am <em>so</em> tired.</p>

Tables-go inside body
 <table border="1px">
            <tr>
                <td>King Kong</td>
                <td>1933</td>     
            </tr>
            
            <tr>
                <td>Dracula</td>
                <td>1897</td>
            </tr>
            
            <tr>
                <td>Bride of Frankenstein</td>
                <td>1935</td>
            </tr>
        </table>
	
more on tables, tables have heads and bodies too!
colspan means the title spans more than on column
<html>
    <head>
        <title>Table Time</title>
    </head>
    
    <body>
        
        <table style="border-collapse:collapse;">
            <thead>
                <tr>
                    <th style="color: red"; colspan="2">Famous Monsters by Birth Year</th>
                </tr>
                <tr style="border-bottom:1px solid black;">
                    <th style="padding:5px;"><em>Famous Monster</em></th>
                    <th style="padding:5px;border-left:1px solid black;"><em>Birth Year</em></th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td style="padding:5px;">King Kong</td>
                    <td style="padding:5px;border-left:1px solid black;">1933</td>     
                </tr>
                
                <tr>
                    <td style="padding:5px;">Dracula</td>
                    <td style="padding:5px;border-left:1px solid black;">1897</td>
                </tr>
                
                <tr>
                    <td style="padding:5px;">Bride of Frankenstein</td>
                    <td style="padding:5px;border-left:1px solid black;">1944</td>
                </tr>
            </tbody>
        </table>
        
    </body>

</html>

Divide page into sections:
<!DOCTYPE html>
<html>
	<head>
		<title>Result</title>
	</head>
	<body>
		<div style="width:50px; height:50px; background-color:red"></div>
		<div style="width:50px; height:50px; background-color:blue"></div>
		<div style="width:50px; height:50px; background-color:green"></div>
		<a href="http://www.cooltanarts.org.uk/wp-content/uploads/2013/10/robot.jpg">
		<div style="width:50px; height:50px; background-color:yellow">
	    </div></a>
	</body>
</html>

Span let's you style a section, can style color, font, etc.
<!DOCTYPE html>
<html>
	<head>
		<title>Result</title>
	</head>
	<body>
		<p>My favorite font is <span style="font-family: Impact;">Impact</span>!</p>
	</body>
</html>
