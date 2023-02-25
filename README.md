# challenge_number_4


In this repository you´ll find how to build pseudocode and how to find prime numbers and mathematical roots through flowcharts and the pseudocode build.  Let´s try something. Through flowcharts and pseudocode building we will try to find the way to determine what numbers and how they are prime numbers. To do so, we have to first identify what exactly do I need. That being said, the pseudocode building will be our focused topic.



# :stars: How to build pseudocode to find prime numbers :stars: #

Bearing in mind you already knew about pseudocode, what is it and how to work with it, thenext step is build it. 

With that being said, there are some important things you have to take into account when building pseudocode. The first one is to find what you are looking for. This case, we are interesetd in finding a way to determine what are the prime numbers and how to find them through pseudocode building. :computer:

### What I did? 🖱️ ###

First of all, I searched in the web what the prime numbers are. What I found was that prime numbers are indeed just numbers greater than one and which have only two factors (one and his own self). Once clarified what the prime numbers are, th enext steps are creating the pseudocode and the flowcharts. 

#### For the pseducode building ####

Taking as example one of the previous challenges and examples given by the teacher, I built the pseudocode from a theory of how to find when a number is factor or not of another number. For building this pseudocode I´ve taken into account some variables as "while", "then". "if", etc. Now, I´ll share a little bit of the pseudocode I created an what I took as first attempt of pseudocode:

`$ npm install marked`

i:integer
start
	i: = 1
	n: = (n^0.5) + 1
	while (i < n)
		If module (n,i): == 0
			Then
				write ("i is factor of n")
					If more than 2i are factors
						Then write ("i is not prime number")
					If not 
						write (i is prime number)
End while
