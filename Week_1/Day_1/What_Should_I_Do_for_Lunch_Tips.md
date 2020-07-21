### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  console.log("I don't know what to do!");
  if (!hungry) {
    console.log("Get back to work.");
  }
  if (hungry) {
    
    if (availableTime < 20) {
      console.log("Pick something up and eat it in the lab!");
    } else if (availableTime >= 20 && availableTime < 30) {
      console.log("Try a place nearby.");
    } else if (availableTime >= 30 && availableTime <= 50) {
      console.log("Remember that your in a bootcamp. You should reconsider how much time we actually have to spare.");
    }
  }
};
```

