# JavaScript-Theremin-Function-Problem-Data-Structure-
What condition is tested in the if/else statement? We need to know if the string argument starts with an uppercase or lowercase "s".

Create the function doYouPlayTheTheremin. If your name starts with the letter "S" or "s", you are playing the Theremin!



Given EXAMPLES
- INPUT: doYouPlayTheTheremin("Griffin")
- OUTPUT: "Griffin does not play the Theremin!";


- INPUT: doYouPlayTheTheremin("Scott");
- OUTPUT: "Scott plays the Theremin!";


Solutions : 

function doYouPlayTheTheremin(name){
	if(name[0].toLowerCase() === "s"){
		return name + " plays the Theremin!";
	} else {
		return name + " does not play the Theremin!";
	}
}
