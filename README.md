Link Tag in HTML

-	The <link> tag defines the relationship between the current document and an external resource.
- It is placed in head section of document.
-	Most often used to link to external style sheets but is also used to establish site icons
-	It is an empty element, it contains attributes only.
-	Supported in all majoe browsers - Google, Edge, Firefox, Opera, Safari
-	Example -
		
	<!DOCTYPE html>
	<html>
		<head>
			<title>link Tag</title>
			<link rel = "stylesheet" href = "stylenew.css">
		</head>
		<body>
			<div class = "para">
				<p>Welcome to the world of magic.</p>
			</div>
		</body>
	</html>
	
	CSS for above -
		
		.para{
			color : orchid;
		}

-	It supports al the Globar attributes in HTML

- Supports specific attributes - href, media, charset, hreflang, rel, rev, sizes, target, type
