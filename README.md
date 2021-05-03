# Wine-glass-with-html-css
.....html.....
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <script src="script.js"></script>
    <html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Wine glass</title>
</head>
<body>
    <div class="container">
    	<!--First wine glass -->
    	<div class="body">
    		<div class="wine"></div>
        </div>
        <div class="middle"></div>
        <div class="base"></div>
    </div>
        <!--Second wine glass -->
        <div class="container2">
    	<div class="body2">
    		<div class="wine2"></div>
        </div>
        <div class="middle2"></div>
        <div class="base2"></div>
        </div>
        <!--Third wine glass -->
        <div class="container3">
    	<div class="body3">
    		<div class="wine3"></div>
        </div>
        <div class="middle3"></div>
        <div class="base3"></div>
        </div>


</body>
</html>
  </body>
</html>
.....css....
body{
	display: flex;
  justify-content: center;
  padding-top: 50px;
}
.container{
	float: left
}

.body{
	background: rgba(180, 180, 180, 0.3);
	width: 200px;
	height: 300px;
	border-radius: 53% 47% 49% 51% / 0% 0% 100% 100%;
	border: 1px solid transparent;
	filter: blur(0px);
	box-shadow: inset 0 1px 0px #444444, inset 0 2px 0 white, inset 0 -6px 3px #444444;
}
.wine{
	background: linear-gradient(to bottom, transparent, transparent, transparent, #b86b77, #b86b77, #b86b77);
	width: 200px;
	height: 300px;
	border-radius: 53% 47% 49% 51% / 0% 0% 100% 100%;
}
.middle{
	background: rgba(180, 180, 180, 0.3);
	width: 20px;
	height: 250px;
	border-radius: 0 0 5px 5px;
	border: 1px solid transparent;
	filter: blur(0px);
	box-shadow: inset 0 1px 0px #444444, inset 0 2px 0 white, inset 0 -6px 3px #444444;
	position: relative;
	left: 90px;
	bottom: 5px;
}
.base{
	background: rgba(180, 180, 180, 0.3);
	width: 130px;
	height: 25px;
	border-radius: 50%;
	border: 1px solid #777;
	filter: blur(0px);
	filter: drop-shadow(8px 8px 8px black);
	position: relative;
	left: 30px;
	bottom: 10px;
}
.container2{
	float: left;
	margin-left: 20px;
	margin-right: 20px;
}
.body2{
	background: rgba(180, 180, 180, 0.3);
	width: 300px;
	height: 300px;
	border-radius: 0px 0px 50% 50%;
	border: 1px solid #777;
	filter: blur(0px);
	box-shadow: inset 0 1px 0px #444444, inset 0 2px 0 white, inset 0 -6px 3px #444444;
}
.wine2{
	background: linear-gradient(to bottom, transparent, transparent, transparent, #5e1224, #5e1224, #5e1224);
	width: 300px;
	height: 300px;
	border-radius: 0px 0px 50% 50%;
}
.middle2{
	background: rgba(180, 180, 180, 0.3);
	width: 30px;
	height: 250px;
	border-radius: 0 0 5px 5px;
	border: 1px solid transparent;
	filter: blur(0px);
	box-shadow: inset 0 1px 0px #444444, inset 0 2px 0 white, inset 0 -6px 3px #444444;
	position: relative;
	left: 135px;
	bottom: 4px;
}
.base2{
	background: rgba(180, 180, 180, 0.3);
	width: 200px;
	height: 25px;
	border-radius: 50%;
	border: 1px solid #777;
	filter: blur(0px);
	filter: drop-shadow(8px 8px 8px black);
	position: relative;
	left: 50px;
	bottom: 10px;
}
.container3{
	float: left;
	margin-left: 20px;
	margin-right: 20px;
}
.body3{
	background: rgba(180, 180, 180, 0.3);
	width: 150px;
	height: 200px;
	border-radius: 52% 48% 47% 53% / 10% 9% 91% 90%;
	border: 1px solid #777;
	filter: blur(0px);
	box-shadow: inset 0 1px 0px #444444, inset 0 2px 0 white, inset 0 -6px 3px #444444;
	position: relative;
	top: 175px;
}
.wine3{
	background: linear-gradient(to bottom, transparent, transparent, transparent, #c9ffe5, #c9ffe5, #c9ffe5);
	width: 150px;
	height: 200px;
	border-radius: 52% 48% 47% 53% / 10% 9% 91% 90%;
}
.middle3{
	background: rgba(180, 180, 180, 0.3);
	width: 20px;
	height: 170px;
	border-radius: 0 0 5px 5px;
	border: 1px solid transparent;
	filter: blur(0px);
	box-shadow: inset 0 1px 0px #444444, inset 0 2px 0 white, inset 0 -6px 3px #444444;
	position: relative;
	left: 70px;
	top: 170px;
}
.base3{
	background: rgba(180, 180, 180, 0.3);
	width: 100px;
	height: 25px;
	border-radius: 50%;
	border: 1px solid #777;
	filter: blur(0px);
	filter: drop-shadow(8px 8px 8px black);
	position: relative;
	left: 30px;
	top: 165px;
}
