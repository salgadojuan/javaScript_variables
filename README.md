# javaScript_variables
Variables practice using JavaScript 


/*Imitate a Twitter "Tweet" by creating a 280 max-character JavaScript prompt for the user to enter a tweet. Once the user enters his/her Tweet, display an alert with the amount of characters the user entered & the remaining characters left (max characters: 280). */

var tweet = prompt("Enter a tweet: ");
var tweetCount = (tweet.length);

alert("you have entered " + tweetCount + " you have " + (280 - tweetCount) + " remaining.");
