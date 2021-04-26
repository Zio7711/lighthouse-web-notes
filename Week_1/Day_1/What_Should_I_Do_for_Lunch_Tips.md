## Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.


```javascriot

const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry) {
    if (availableTime < 20) {
      return console.log("Pick something up and eat it in the lab.");
    } else if (availableTime >= 20 && availableTime <= 30) {
      return console.log("Try a place nearby.");
    } else {
      return console.log("We are in a bootcamp, and we should reconsider how much time we actually have to spare.");
    }
  } else {
    return console.log("Get back to work");
  }
};

```


