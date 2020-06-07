Website link -> adamwk97.epizy.com

#1. My Java code for this week is

```
<!DOCTYPE html>
<html>
<body>

<p>Click the number to see how big it is!</p>
<button onclick ="javaFunction()">Try it</button>
<p id="Mod4"></p>
<script>	
function javaFunction(){
	int num = Math.random()%6+1;
	
	if(num <=2){
		result = "Small number";
	} else if (num >2 & num < 5);
		result = "Medium number";
	}else{
		result = "Big number";
	}
	document.getElementByld("Mod4").innerHTML = result;
	}
	</script>
	</body>		
</html>
```

However clicking the button does not show anything and I am unsure why. 

#2. The fixed code looks like:

```
<!DOCTYPE html>
<html>
<body>

<p id="demo">Display the result here.</p>

<script>
var greeting;
var hour = new Date().getHours();

if (hour < 18) {
greeting = "Good day";
}else{
greeting = "Good evening";
}

document.getElementById("demo").innerHTML = greeting;
}
</script>

</body>
</html>
```

#3. I found it fairly simple to follow on how to save a web image for a website using Photoshop. I saved and downloaded the file as a PNG,
imported it into photoshop and then saved it using the appropriate height/width dimensions. I did not have any problems with this.
