Created a object contained common tools used a lot for adding event. Try to figure out the compatible problem against horrible IE. Just for practice.     

This object has these method temporaily:

- addHandler(element, type, handler)
- removeHandler(element, type, handler)
- getEvent(event)
- getTarget(event)
- preventDefault(evnet)
- stopPropagation(event)
- getButton(event)
- getWheelData(event)
- getChardCode(event)
<<<<<<< Updated upstream
=======


Add encapsulated ajax tool function.



```javascript
//params
opt = {
	url: '', //request url 
	type: 'get', //request type (post)
	data: {}, //data passed in
	dataType: 'json', //type of the data returned
	succ: function () {}, //when reuqest succeed, this function will be called.
	erro: function () {} //when reuqest failed, this function will be called.
}
```
>>>>>>> Stashed changes
