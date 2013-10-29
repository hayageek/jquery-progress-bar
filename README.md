jquery-progress-bar
===================

##Overview
Simple jQuery Progress bar


###Initialization
---
````html
<div id="progress"></div>
````
````javascript
var bar1 = $("#progress").progressbar();
	bar1.progress(60); 
````


###Examples
````javascript
	$("#progress").progressbar();
	
	$("#progress").progressbar({color:'#145ABA'});

	$("#progress").progressbar({width:'400px',color:'#0A8F2B',border:'2px solid #0A8F2B',padding:'3px'});
	
	$("#progress").progressbar({width:'500px',color:'#B3240E',border:'1px solid #000000'});

````


###Demo
---
http://hayageek.com/examples/jquery/progress-bar/index.php
