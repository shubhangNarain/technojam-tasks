# TECHNOJAM TASKS INFO:

**ALL THE TASK NUMBERS HERE ARE BASED ON THE OLDER VERSION OF THE TASK LIST WHICH HAD THE MANDATORY INSTALLATION OF UBUNTU**
**SO THERE MIGHT BE A CHANCE THAT I GET THE QUESTION NUMBERS WRONG, FOR THAT, I'VE MENTIONED THE QUESTION NAME WITH THE TASK**
**NUMBER**

## COMPETITIVE PROGRAMMING (EASY):
It is of no surprise that these easy questions were not so easy for the students of first. As of me, I had to study
some of the basics of DataStructres and Algorithms, I have been studying C/C++ from the past 3-5 months which helped
me in dealing with the questions given in the tasks. Here is how I dealt with the given questions:

1. **Question 1:** In this question we were given a condition in which we had to find which person will be facing 
Rob stark, where 0's count as a 90 degree rotation to the right and, 1's count as a 90 degree rotation to the left.
I made two arrays, one for clockwise rotation(for 0's) and one one for anti-clockwise rotation(for 1s'). Remember 
0 and 1 cancel out each other here, so we just had to calculate which number is in a larger quantity in the String 
that the user inputs. If 0's are more than 1's, we print the person on the position of the difference b/w 0's and 
1's form the clo[] array, and from antclo[] if 1's are more.**Time complexity: O(n^2)**.

2. **Question 2:** We are given an array consisting of N integers. In every operation we perform, we are allowed
to choose any 2 elements from the array and replace both of them with a new number in the array which is equal
to the sum of both numbers. Our task is to find the maximum possible number of elements divisible by 4 that are
in the array after performing the above operation any number of times.

    Firstly, we find the remainder for each element of the array after dividing it by 4 (a[ i ]%4), we calculate the
    number of 1's, 2's, 3's and 0's in the array now, Initially, the number of zeroes in the array represent the 
    elements divisible by 4, for the next step, we calculate how many 1+3's are there in the array then add the number
    to the number of zeroes, then we move on to 2+2's, then 1+1+1+1's and then finally 3+3+3+3's. The final number of 
    zeroes is our answer.**Time complexity: O(n)**.

3. **Question 3:** We are given an array of n integers. We want to make all the numbers in this array as odd. We
can only make an even as odd by using an odd number present in the array, So the total number of evens in the array
is the number of odds we can make in the array ONLY IF one of the elements of the array is odd. If all the elements
of the array are even, it is impossible to make the array odd by adding any two elements of the array. Hence, our
final answer is the number of evens present in the array.**Time complexity: O(n)**.

4. **Question 4:** We are given with an array of n integers. We have to find the sum of all prime numbers present
in the array and then have to check whether all the digits in that sum are unique or not. For this question, I used
vectors, as they have dynamic sizes, I made a function that tells whether a number is prime or not(isPrime(int n)),
if true, then we add that number in the sum variable to calculate the sum of all elements in the array/vector.
Finally we extract the digits in the sum of prime numbers of the array and check whether the digits of the number 
are different or not, if they are all different then we say, the number is Unique and return the message "YES", if
not then we return the message "NO". **time complexity: O(n^2)**.

5. **Question 5:** Given a two-dimensional array or matrix of size n*m, Write an algorithm to print the given matrix
in a zigzag manner or in other words print all the diagonals from bottom to up in the matrix starting from the
position p as stated below: For p=1, Start from 0,0 position For p=2, Start from 0,m-1 position For p=3,
Start from n-1,m-1 position For p=4, Start from n-1,0 position. I made a single function with different if else if
conditional statements(depending upon the value of p), and for each value I have made 2 nested loops to fill the 
array from the start and from the end upto the middle diagonal.

## BIRTHDAY CARD (EASY):

**Question. :** Design a birthday card in Android Studio using XML. ​It should contain a single screen displaying 
the birthday card. Use different layouts and components like(textView, imageView, etc.) to make it attractive and
stand apart.
To do this, I download the AndroidStudio application and made an empty activity, then, I pasted some of the images
that I wanted to use in the ".res" folder of the application. Then I added some text using the ImageView function
and then went on to add the images too, In the end, I finished my birthday application/card and built the .apk file
and saved it on to the desktop.

## WEB APPLICATION <HTML> (EASY):

**Question. :** Build a web application that counts the number of words in a paragraph. ​Allows the user to pass a set
of lines as input. ​Displays the count of the words available in input as output.

To do this task, I downloaded all the extensions that were necessary for the code to work, then I started writing the code.
In the <style> tag I wrote the code for the design of the text area and the button. I attached a function countwords() with 
the button which calculates the number of words in the paragraph. In the <script> tag, I wrote the function countwords() to
print the number of words in the alert box of the browser with .match(//g) function which made an array of words, and in the 
end I printed the length of that array with .length() function, which in the end is the number of words in the paragraph.
