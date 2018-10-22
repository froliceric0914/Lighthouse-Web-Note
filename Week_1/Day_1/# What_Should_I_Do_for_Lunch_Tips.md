# What_Should_I_Do_for_Lunch_Tips


function whatToDoForLunch(hungry, availableTime) {
  if (hungry == true){
    if (availableTime > 30){
    console.log("This is Bootcam after, you should reconsider it");
  }
    else if (availableTime >= 20 && availableTime <= 30){
    console.log("You deserve a break and could try a place in Gastowm!");
  }
    else if (availableTime < 20) {
    console.log("Pick something up and eat in back the Lab or in the kitchen");
  }
} else
  {
    console.log("Wait until you're hungry");
  }
}



/*
 * This is some test runner code that's simply calling our whatToDoForLunch function
 * defined above to verify we're making the right decisions. Do not modify it!
 */

console.log("I'm hungry and I have 20 minutes for lunch.");
whatToDoForLunch(true, 20);
console.log("---");

console.log("I'm hungry and I have 50 minutes for lunch.");
whatToDoForLunch(true, 50);
console.log("---");

console.log("I'm not hungry and I have 30 minutes for lunch.");
whatToDoForLunch(false, 30);
console.log("---");

console.log("I'm hungry and I have 15 minutes for lunch.");
whatToDoForLunch(true, 15);