# Activities-findings

1) I received this error on the activity two when I was using the given path (if you right click you can copy the object path).
![1) Error for server api image callback](https://user-images.githubusercontent.com/76451565/112080505-7e765800-8b58-11eb-9687-b4c63f76eb99.PNG)

2)	This was my code. I used the dot array syntax.
![2) Error for server api - source code](https://user-images.githubusercontent.com/76451565/112080518-8504cf80-8b58-11eb-9238-4c7979ab56c9.PNG)

3) I did a typeof on the data variable and it was an “object” type. So I looked it up online on how to convert objects to array and found this: 
https://stackoverflow.com/questions/38824349/how-to-convert-an-object-to-an-array-of-key-value-pairs-in-javascript

5) This person’s solution was the best:
![mdn solution for object to arrays](https://user-images.githubusercontent.com/76451565/112080605-ad8cc980-8b58-11eb-8075-a4bd30ae6524.PNG)

4) So then I did a wrapped data in the Object.entries() function and copied the path of the “image_url” I wanted and pasted into the script.js -> 
![3) Updated - source code](https://user-images.githubusercontent.com/76451565/112080616-b1b8e700-8b58-11eb-94b5-3e770d2f6d54.PNG)

5) This was the result I received with no errors ^_^  
![4) Updated - ser api image result](https://user-images.githubusercontent.com/76451565/112080670-ca290180-8b58-11eb-8157-04f86f0b7909.PNG)

6) I searched nested arrays (because that’s how I know them in Python) and found they talk about it on MDN if you scroll all the way down: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Indexed_collections
