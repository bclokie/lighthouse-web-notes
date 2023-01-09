### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
let whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === true) {
    if (availableTime < 20) {
      console.log('You should pick up a snack or grab something you have ready at home');
    } else if (availableTime >= 20 && availableTime <= 30) {
      console.log('You deserve a break, cook yourself a tasty meal');
    } else if (availableTime > 30) {
      console.log('This is an intense program, you should probably reconsider');
    }
  } else if (hungry === false) {
    console.log('You do not need to eat if you are not hungry');
  }
  whatToDoForLunch;
  console.log("hungry is", hungry);
  console.log("availableTime is", availableTime);
};
```