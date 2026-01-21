![[Pasted image 20250908115844.png]]
### Data and Storage
 - Does my project use more than a simple text file?

	Page 58(design) is the first mention of my data storage. In that section i justify why I'm using a JSON file in the first place, and then I also suggest some of the data that I want to put in it, being:  the key variables that my users can change during the simulation, and the information for each of my bacteria species(including description and transmission).

	 Yes, I have used more than a simple text file in my NEA, and I have also used it to store data that is important to how my NEA works.

 - Am I storing and retrieving data in a way that needs careful design?

	![[Pasted image 20250908121035.png]]
	
	In my code, I made a method that let the class using my UI access a python object version of my JSON file. I did this so that I would be allowed to make changes to the entries of my JSON file(I couldn't find a more efficient way, and I'm not sure if one exists).

	![[Pasted image 20250908121232.png]]
	I then made a second method that, when called, lets me save the edits I've made to my file.

	I'm not sure if this classifies as requiring 'careful design', but it took a good amount of thinking to do.
	
### Programming and structure
- Am I using a clear programming style?
	Yes, I've been using OO for the whole of my project. Made class to contain and run my UI, and in my simulation, but I've made a few separate disconnected functions that didn't really make sense in any of my existing classes

- Does my project involve combining different technologies?
	I'm not very sure what this means, but have been using PyQt5 for my front end.

### Algorithms and Logic
- Do I need to design or adapt an algorithm?
	Yes, in design, I made my first and second version of my life cycle algorithms, which I further developed and changed in my second iteration, most notably my death function.

- Do I need to use or adapt data structures?
	Yes, during my second iteration, I needed to use dictionaries to get the objects in my simulation that were colliding with other objects, being either other bacteria or food items.
### Libraries and Tools
- Am I using external libraries?
	Yes. In my NEA I use PyQt5, as well as Pygame and PyQtGraph. Pygame is used to handle everything related to my simulation. I also use PyQtGraph in my statistics tab to display my variable axis graph(was changed from original plan of using Matplotlib, because PyQtGraph is better at handling regular updates to graphs, and is easier to integrate into a PyQt5 User Interface). 
### Extra complexity
 My project does not interact with the internet or networks in any way, and also does not require any additional hardware other than a mouse and keyboard to use.


### Questions
- In programming and structure, what do they mean when they say 'combining different technologies'.

