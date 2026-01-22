What patterns or surprises did you notice?
    I was deceived! Hoodwinked! Bamboozled! I had previously used Number.IsInteger while working on a different assignment, and I decided to try to check whether there was an existing function for checking whether numbers are odd or even. I began to type Numbers., and IsOdd/IsEven appeared. I thought it would work because the options appeared in the dropdown, but both my functions failed. I did some searching and realized that it doesn't exist in javascript, the actual method to check whether a number is odd or even is to divide by 2 and checking remainder with %. I'm only realizing now as I look at the code that the dropdown was probably just referring to my own function.

What logic challenged your thinking?
    I have a bad tendency to forget to actually call the functions that I've just created, or place an input. For example, I've used console.log(function()), and just saw the logic rather than the result I cared to see. I tried to check to see if my failed isOdd function was an integer since it failed (I realize I was wrong per the above from the getgo), and I ran the following code and got a "False" result. Turns out I was comparing to the function itself, and not checking whether (n) was an integer.
        function isOdd(n) {
            return n === Number.isInteger
        }
        console.log(isOdd(7))

How might this kind of toolkit be used in the real world?
    This toolkit would be really helpful for syntax reference. These felt like fairly basic functions, but assuming that "simple" = intuitive has been a fun assumption to destroy in a horribly disappointing way. I didn't realize javascript had any negative connotation until I watched one of the lecture videos, and I'm discovering that there are many tiny nuances to the language that are hard to understand, especially as a newbie. Building a toolkit that slowly became more sophisticated over time would help with refreshing the mind and having a comparison tool.