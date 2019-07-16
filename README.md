# SegundaTarea
<!DOCTYPE html><html><head>

<title>Calculator</title><meta charset="utf-8">

<script type="text/javascript">

function sqr() {  
	
	var num = document.getElementById("n1"); 
	 
	num.value = Math.pow(num.value, 2);

}

function cube() {  
	
	var num = document.getElementById("n1"); 
	
	num.value = Math.pow(num.value, 3);

}

function fourth() {
	
	var num = document.getElementById("n1");
	
	num.value = Math.pow(num.value, 4);

}

function sin() {  
	
	var num = document.getElementById("n1"); 
	 
	num.value = Math.sin(num.value, 3);

}

function inverse() {  
	
	var num = document.getElementById("n1"); 
	 
	num.value = 1/(num.value);

}

</script>

</head>

<body>
	
<h1>My calculator</h1> 
	 
	Number:
	 
	<input type="text" id="n1"> 
	 
	<p>
		 
	<button onclick="sqr()"> x^2 </button>  
		 
		<button onclick="cube()"> x^3 </button>
		 
		<button onclick="fourth()"> x^4 </button>
		 
		<button onclick="sin()"> Sin </button>  
	   	 
		<button onclick="inverse()"> 1/x </button>  
	
	</p>

</body>	

</html>
