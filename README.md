### Rock, Paper, Scissor application!

###### 1. Get the user's choice

**Assign a `prompt` method to the variable `userChoice`:**
The ```prompt``` method gets input from the user, ```prompt``` has an optional message parameter which you can use to ask the user for a response.

###### 2. Get the computer's choice

Assign a `Math.random()` method to the variable `computerChoice`:

What is `Math` in JavaScript?

```Math.random()``` returns a random floating point number between 0 and 1.

###### 3. Teach the computer rock, paper, scissors.

This is our first conditional statement. 

We change the value of ```computerChoice```
to either rock, paper, or scissors depending on what number the ```computerChoice```
variable gets set to when we run the program. 

```javascript

if (computerChoice <= 0.33) {
    computerChoice = "rock";
} else if (computerChoice <= 0.66) {
    computerChoice = "paper";
} else {
    computerChoice = "scissors";
}
```

###### 4. Compare the choices and tell the user of the result.
Here we're creating a function called ```compare```. The ```compare``` function takes two
arguments ```choice1``` and ```choice2```.

###### 4.5 Calling the compare function
We're passing values of userChoice and computerChoice to run the equation. 

The function is called when someone clicks the button via the ```onclick``` attribute!
