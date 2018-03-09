#3-musketeers-cash

This software allows money convertion in 31 different currencies.

##Getting Started
Fork the project from https://github.com/92bondstreet/3-musketeers and clone it using the following command : 
	```
	git clone https://github.com/yourgit/3-musketeers.git
	```

##Prerequisites
Before running the program type the following command to install needed libraries:
	```
	npm install
	```

##Run the software
In the bin directory, open a cmd and run by typing the following line :
	```
	node index.js
	```

##To check if it works well
Usage, commands and Examples are displayed on the screen.

##Use it
Convert an amout of money in the currency of your choice with the following command :
	node index.js <amount> <currency>

Save the currency of the money you want to convert without specifying the currency at each use :
	node index.js -s <currency>

##Example 
To convert 500 USD 
	```
	node index.js 500 USD
	```

To save euro as the currency of all futur ammounts to convert
	```
	node index.js -s eur
	or node index.js --save eur
	```

Now to convert any ammount (automatically saved as euros)
	```
	node index.js 500
	```

##Built With
Javascript
NodeJS

##Versioning
1.00

##Authors
Yassine Azzout
Hanako Cetin

##License
Uncopyrighted