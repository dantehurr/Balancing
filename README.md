# Balancing
Ever needed to balance an array and find the location of the equilibrium point? Well, look no further! Here is the program for you!

This program was written as part of the entry process for the 2021 Microsoft New Technologists program. The prompt called to wite a function int balanced(int[]arr); that given a sequence arr[] of size n, returns the index (if any) or -1 if no index position is found.

When approached with this question, I inititally was intrigued yet still met with a bit on confusion on how to get going. I decided to write out what I called my 'map' which was basically an 8 page written document of what I wanted the code to do, possible arrays to use for testing and any other notes on roadblocks I ran into while doing my first draft.

My first approach had a similar style prompt to the final code, asking the user for a length and an array and then I wrote out a very long block of code that checked each possible outcome with an if else statement. Ex: 

if (arr[0] == arr[2] + arr[3] + arr[4] + arr[5] + arr[6] + arr[7] + arr[8] + arr[9]) {
			index = "1"; // this will print the index of the result
} else if (arr[0] + arr[1] == arr[3] + arr[4] + arr[5] + arr[6] + arr[7] + arr[8] + arr[9]) {
			index = "2"; }
      
and so on and so forth. It just kept going and going and only could support arrays that were 10 elements or less. The program was inefficient and I was ultimately dissatisfied with that execution method. I continued to reach out to people who were more experienced in Java and a good friend of mine recommended that I create a loop. Ironically this was the upcoming topic in my college Programming class. I spoke with my professor, who gave me a great example of a loop that I had already used in a prior week. This set the ground work for me to be able to create the loop function and then enter my user prompts.

Still after this, I found myself hitting a wall where my array variable wasn't getting called upon because it was stuck inside the loop. So I backtracked a bit and did some class work where we put a loop inside the class and then called it later. This assignment showed glaring similarity to the puzzle I was already working on. We had to write a program that would scan user input and detect upper case, lower case and digits and index them. So I used a bit of technique and finesse from that lesson to rework the array loop inside of the class and then call upon it later on, after I have created my user prompts. Success!

// Writen by Dante Hurr; 3/4/21
