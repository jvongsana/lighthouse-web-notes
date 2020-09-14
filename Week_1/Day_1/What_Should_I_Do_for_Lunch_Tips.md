### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  switch (hungry) {
  case true:
    if (availableTime < 20) {
      console.log("Pick up something and eat it in the lab.");
      break;
    } else if (availableTime < 30) {
      console.log("Try a place near by.");
      break;
    } else {
      console.log("We are in a bootcamp, maybe the amount of time for lunch should be reconsidered.");
      break;
    }
  default:
    console.log("Get back to work.");
    break;
  }
};
}```