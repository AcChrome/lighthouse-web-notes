### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```const whatToDoForLunch = function(hungry, availableTime) {
  // console.log("I don't know what to do!")

  if (hungry === true && availableTime < 20) {
    console.log('Pick something up and eat in back in the lab or in the kitchen, where you can get to know your fellow classmates.');
  } else if (hungry === true && availableTime >= 20 && availableTime <= 30) {
    console.log("You've been working hard, take a break and try at place in Gastown.");
  } else if (hungry === true && availableTime >= 30) {
    console.log('This is a bootcamp, you should reconsider.');
  } else if (hungry === false) {
    console.log('Do not eat yet.');
  }
}
```

