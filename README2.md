function welcometomypage(){
	alert("Hi! Welcome to Dhamar's Portfolio!");
}     



	 function myFunction() {
        var image = document.getElementById("image");
       /* image.src = "http://thefw.com/files/2013/03/Cute-Cat.gif"; */
		image.alt= "Cute cat"
		
		if (image.src =="https://lh6.googleusercontent.com/-AHImhBFMXnQ/VB0MSP9mSfI/AAAAAAAABlc/h1KwfbH83Vg0x1XmjCiqGAkLpTl3C2F6QCL0B/s591-no/10548237_1477015159215393_6159929724786602206_o.jpg"){
	     image.src = "file:///C:/Users/Girls%20Who%20Code/Pictures/wowsuchnicepic.PNG";
		 image.alt= "dhamar";
		 image.style= "width:350px; height:335px;";
		}
		else{
		 image.src = "https://lh6.googleusercontent.com/-AHImhBFMXnQ/VB0MSP9mSfI/AAAAAAAABlc/h1KwfbH83Vg0x1XmjCiqGAkLpTl3C2F6QCL0B/s591-no/10548237_1477015159215393_6159929724786602206_o.jpg";
		 }
		 }
