## Iterações com array simulando for

var myArray = ['item1','item2','item3'];
	
	//jQuery
	$.each(myArray, function(index, obj){
		console.log(index, obj);
	});
	
	//Javascript puro
	var length = myArray.length;
	for(var x=0; x<length; x++){
		console.log(x, myArray[0]);
	}

	myArray.forEach(function(obj, index){
		console.log(index, obj);
	});