grid-template-column -> we can define how many columns we want with this
	grid-template-columns: repeat(auto-fill, minmax(min(250px, 100%), 1fr));
	 with this 

grid-auto-flow -> when i use this all of the grid children will remain in one row 
	note -> when using this you will  make unequal columns so after that 
	 you can use grid-auto-columns: 1fr;