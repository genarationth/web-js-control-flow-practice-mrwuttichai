#### Create a day of the week translator.</br>
Your program should read a variable called “dayNumber”, </br>
and print (with console.log) the corresponding day of the week, where 0 is Sunday and 6 is Saturday.</br>
For any other values, your program should print “Invalid day number”.</br>
Test your program for all week days values.


let dayNumber = 0;
if(dayNumber===6){
  console.log("Saturday");
} else if (dayNumber===5){
  console.log("Friday");
} else if (dayNumber===4){
  console.log("Thursday");
} else if (dayNumber===3){
  console.log("Wednessday");
} else if (dayNumber===2){
  console.log("Tuesday");
} else if (dayNumber===1){
  console.log("Monday");
} else if (dayNumber===0){
  console.log("Sunday");
} else{
  console.log("Invalid day number");
}