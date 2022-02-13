## JavaScript Basics OR JavaScript Fundamentals

* Javascript Data Types




#### Javascript Data Types

* JavaScript provides different **data types** to hold different types of values. There are two types of data types in JavaScript.
  * Primitive data type
  * Non-primitive (reference) data type

* JavaScript is a **dynamic type language**, means you don't need to specify type of the variable because it is dynamically used by JavaScript engine. You need to use **var** here to specify the data type. It can hold any type of values such as numbers, strings etc.

* **For example:**

![image](https://user-images.githubusercontent.com/40323661/153751038-5fcddb0a-2d10-4cab-82d1-9ac35e1f69ef.png)

![image](https://user-images.githubusercontent.com/40323661/153751021-2767044b-63d2-4660-b2b5-cfacd0999373.png)


```JavaScript
<!DOCTYPE html>
<html>
<body>
	<h1>Demo: JavaScript Variables </h1>
	
	<p id="p1"></p>
	<p id="p2"></p>
	<p id="p3"></p>
	<p id="p4"></p>
	<p id="p5"></p>

	<script>
		var myvariable = 1;  // numeric value
		document.getElementById("p1").textContent = myvariable;

		myvariable = 'one'; // string value
		document.getElementById("p2").textContent = myvariable;

		myvariable = 1.1; // decimal value
		document.getElementById("p3").textContent = myvariable;

		myvariable = true; // Boolean value
		document.getElementById("p4").textContent = myvariable;

		myvariable = null; // null value
		document.getElementById("p5").textContent = myvariable;
    </script>
</body>
</html>
```

![image](https://user-images.githubusercontent.com/40323661/153751137-42bc496c-f4ff-4848-bb10-c01cc6326201.png)

* The followings are primitive data types in JavaScript:

![image](https://user-images.githubusercontent.com/40323661/153751242-fced1d55-b7fe-4588-a6a7-c07d0bd3ccae.png)

![image](https://user-images.githubusercontent.com/40323661/153751358-f3e8edd9-1707-4015-84ba-0f57de5c2c62.png)

#### JavaScript String Literals, Objects, Concatenation, Comparison

* Here you will learn what string is, how to create, compare and concatenate strings in JavaScript.

* String is a primitive data type in JavaScript. A string is textual content. It must be enclosed in single or double quotation marks.

![image](https://user-images.githubusercontent.com/40323661/153752561-f239d8fc-ccf4-496d-b4c7-209791663fc9.png)

![image](https://user-images.githubusercontent.com/40323661/153752576-0ea0f414-86d7-474f-a1a7-404e09109569.png)

```JavaScript
<!DOCTYPE html>
<html>
<body>
	<h1>Demo: JavaScript String</h1>
	
	<p id="p1"></p>
	<p id="p2"></p>
	
	<script>
		var str1 = "Hello World";

		var str2 = 'Hello World';

		document.getElementById("p1").innerHTML = str1;
		document.getElementById("p2").innerHTML = str2;
    </script>
</body>
</html>
```
![image](https://user-images.githubusercontent.com/40323661/153752605-3d98aee6-1f5a-44f9-aa20-8a9bde436790.png)

```JavaScript
<!DOCTYPE html>
<html>
<body>
	<h1>Demo: JavaScript String</h1>
	
	<p id="p1"></p>
	<p id="p2"></p>
	<p id="p3"></p>
	<p id="p4"></p>
	<p id="p5"></p>
	<p id="p6"></p>
	
	<script>
		var str = 'Hello World';

		document.getElementById("p1").innerHTML = str[0];

		document.getElementById("p2").innerHTML = str[1];

		document.getElementById("p3").innerHTML = str[2];

		document.getElementById("p4").innerHTML = str[3];

		document.getElementById("p5").innerHTML = str[4];

		document.getElementById("p6").innerHTML = str.length

    </script>
</body>
</html>

```
![image](https://user-images.githubusercontent.com/40323661/153752686-1889763d-74c8-47f8-9267-351cb2f19fa6.png)

![image](https://user-images.githubusercontent.com/40323661/153752704-1fcc77ff-20d0-43d4-8939-33836b87ca5c.png)

```JavaScript
<!DOCTYPE html>
<html>
<body>
	<h1>Demo: JavaScript String</h1>
	
	<p id="p1"></p>
	<p id="p2"></p>
	
	<script>
		var str = 'Hello World';

		for(var i =0; i< str.length;i++)
		    document.getElementById("p1").innerHTML = document.getElementById("p1").innerHTML + str[i];

		for(var ch of str)
			document.getElementById("p2").innerHTML = document.getElementById("p2").innerHTML + ch;

    </script>
</body>
</html>
```
![image](https://user-images.githubusercontent.com/40323661/153752753-4e5efb5d-055f-47ad-96d5-58fb6a1991a0.png)

```JavaScript
<!DOCTYPE html>
<html>
<body>
	<h1>Demo: JavaScript String Concatenation</h1>
	
	<p id="p1"></p>
	
	<script>
		var str = 'Hello ' + "World " + 'from ' + 'TutorialsTeacher';

		document.getElementById("p1").innerHTML = str;
    </script>
</body>
</html>
```

![image](https://user-images.githubusercontent.com/40323661/153752816-8e6d7ca2-2e7c-44ef-844f-57ea9938de21.png)

![image](https://user-images.githubusercontent.com/40323661/153752826-71c5a83a-0086-4506-8c72-7c1ea8094816.png)

```JavaScript
<!DOCTYPE html>
<html>
<body>
	<h1>Demo: JavaScript String</h1>
	
	<p id="p1"></p>
	<p id="p2"></p>
	
	<script>
		var str1 = "This is 'simple' string";

		var str2 = 'This is "simple" string';

		document.getElementById("p1").innerHTML = str1;
		document.getElementById("p2").innerHTML = str2;
    </script>
</body>
</html>
```



