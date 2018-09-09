
function myFoo(array){
	var lastEl;
	for(var i = 0; i < array.lenght; i++){
		document.write("Ячейка - " + i +  "Значение" + array[i] + "<br \>);
		lastEl = array[i];
	}
	return lastEl;
}
var recult = myFoo([12,34,45,67,78]); 
alert(result);
 
