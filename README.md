<p align="center">
<img src="https://i.imgur.com/076a7RX.pngg" alt="Logo"/>
</p>

<h1 align="center">Touch Typing</h1>


- Typing tests are instrumental for people in many different ways. It provides advantages in not just work related things but also day to day activities like doing homework or texting friends. The problem to solve here is to help the user get better, faster and more proficient in touch typing. I will create a simple, small program that will give you random words to type and will convert your time to how many words per minute you are able to achieve. When executed, the program will first ask if you are ready with a count down timer. Second, the random words will appear on the screen for the user to type. I have inputted in a couple of random words in an array to achieve this. After that, your WPM will be displayed after hitting enter on the last word typed. For fun I have added comments to help motivate the user to get faster in the lines below their score.

- To help solve slow typing speeds, lack of typing techniques & limited familiarity with the keyboard, I will be inputting a timer that counts in nanoseconds how long it will take for the user to finish the group of words displayed, an array full of random words to feed the user many options & not just do the same words over & over again, then an output that displays your score to help motivate you to want to beat it the next time you play. For this specific program, there are not much scenarios involved to solving our problem besides getting the user to play as much as possible. 

<h2>Pseduocode:</h2>

Import necessary libraries

     Create an Array of Words = *Input random words to be displayed for the user here*

Main Program

     Display “Ready?” on the screen
     Wait for 2 seconds 

     Display “3” 
     Wait for 1 second

     Display “2”
     Wait for 1 second

     Display “1”
     Wait for 1 second

     Print “Go!”
     Wait for 1 second

Create a random number generator 
Repeat 10 times to display 10 different words
(Generates random index from words in array)

Print randomly selected words from array

Get the current time to store it for the starting time

Stores line inputted by user 

Get the current time to store it for the ending time

Calculate time by subtracting the start line from the ending time

Convert time

Display message: Your WPM is only [WPM value]! 
Display message: You can do better than that.
Display message: Try again :)


<h2></h2>

While writing and testing the program code, I made sure to approach things very carefully and systematically to minimize the chance of errors. 
I reviewed the code line by line, making sure I understood the functionality, logic and purpose of each part. While doing that I also made sure to go over the syntax. 
Fortunately, if I were to encounter any errors it were just simple things like missing brackets or an out of bounds exception error due to simply forgetting to add the 0 at the beginning of the index count for the array as you can see in this screenshot below. All I had to do was change “53” to “51”.

![Picture1](https://github.com/Emq17/Touch-Typing/assets/147126755/09b5ee5a-5036-43d0-96a2-54856a37fef6)

After that, everything ran smoothly as expected. 
One of the test cases I did involved double checking the accuracy of the timer & conversion of the WPM result. I simply went to other websites like Monkeytype.com & chose the option to do a test for 10 words. After I received the results from that website, I would input those same words into the program code Array & do the same test with the same amount of effort to try & match the speed I did earlier. I compared the two values from the website result & my code which displayed very similar times. By choosing a specific input (group of words) I was able to indicate that the program logic was running correctly.
