# **Lab 19: Console Input With Validation**

## Learning Objectives
- Use a Scanner object to collect user input from the console.
- Write a method that constructs and returns an object using user-provided data.
- Validate user input to ensure data meets required conditions.

## Program Description
You recently made your own classes from scratch and added validity checking in your setter methods. In this lab, you will create an array of two `NetflixOriginal` objects by getting valid inputs from the user.

## Specifications
In the `Main` class:
### Step 1
- Write a method `instantiateFromInput()` that takes a `Scanner` object as a parameter and returns a `NetflixOriginal` object.
- Inside the method, prompt user to input `name`, `starRating` and `genre`.
- Set `starRating` and `genre` only when the inputs are valid.
- Keep asking the user to enter `starRating` (0 - 5) and `genre` (Action, Comedy, Drama, etc.) until they are valid.

### Step 2
Inside the `main()` method,
- Create a `Scanner` object.
- Create an array of `NetflixOriginal` shows of size 2.
- Use a loop to fill the array:
  	- Instantiate those two objects by calling the `instantiateFromInput()` method and assign to each element in the array.

## Step 3:
Loop through the array and print each show.
- You may use:
	- toString() (recommended), or
	- getters

Example output format:
```
	Please enter the name of the show: Atypical
	Please enter the star rating: 4.5
	Please enter the genre: drama
	Atypical,4.5,drama
	Please enter the name of the show: Stranger Things
	Please enter the star rating: 5.0
	Please enter the genre: science fiction
	Stranger Things,5.0,science fiction
```
