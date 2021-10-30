# <svg fill="none" viewBox="0 0 100% 100%" width="100%" height="130" xmlns="http://www.w3.org/2000/svg"> <foreignObject width="100%" height="100%"> <div xmlns="http://www.w3.org/1999/xhtml"> <style> #s_wrap { display: flex; justify-content: center; flex-direction: column; } #s_title { font-size: 55px; padding-bottom: 5px; text-align: center; } #s_img { width: 100%; } #s_imgwrap { width: 100%; height: 60px; } </style> <div id="s_wrap"> <div id="s_imgwrap"><img src="./logo_small.svg" height="60px" id="s_img"></div> <div id="s_title">Valerian.js</div> </div> </div> </foreignObject> </svg>

<div>
<p>Fast, readable, flexible web development.</p>
<p>Custom markdown incorporating the powers of a web framework.</p>
<b>Zero dependencies.</b> 
</div>

<img style="float: right;" src="./logo.svg" width="400">

## hello.vlr
```php
html:
    head:
        title: "My Valerian.js Website"
    body:
        (Header
            h1: "Welcome!"
        )
        (Content
            p: "😊"
        )
```

## hello.html
```html
<html>
	<head>
		<title>
			My Valerian.js Website
		</title>
	</head>
	<body>
		<div id="Header">
			<h1>
				Welcome!
			</h1>
		</div>
		<div id="Content">
			<p>
				😊
			</p>
		</div>
	</body>
</html>
```