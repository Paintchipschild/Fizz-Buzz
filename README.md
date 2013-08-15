Fizz-Buzz
=========
// The challenge was to create a program that would
    //count to 100, and on multiples of 2 say "Fizz", on
    //multiples of 5 say "Buzz" and on multiples of 15 say "Fizz Buzz"
      //I'm new to programming (<1 week really) but have been doing JavaScript on Codecademy
      //This is what I came up with
      
      
for (var i = 1; i <= 100; i += 1){
    if (i%15 === 0) {
        console.log("Index is: " + i + " Fizz Buzz");
    }
    else if(i%5 === 0){
        console.log("Index is: " + i + " Buzz");
    }
    else if(i%2 === 0){
        console.log("Index is: " + i + " Fizz");
    }
}
