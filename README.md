# Candy Crush Sara

Original source taken from https://github.com/DDR0/ddr0.github.com/tree/master/Candy%20Crunch


## So you want your own version?

Github has a "Fork" button on the top right. Click that to create a copy of this repository inside your own github account.

You can then download the code onto your own machine, using the green "Clone or download" button.

OR - you may want to use the [Github App](https://desktop.github.com/), especially if you're using Windows.


### Running

Once you have the code on your local machine, running is simply a matter of opening index.html in a browser and voila - you should be up and running.

### Changing.

Most of this code is completely obscure and you don't need to care about. The bits you probably want to care about are below:

* `images/CC_Grid_Sprite_Sheet_v2.png` - This is the image file that contains all of the candy. It also contains your face. There is an equivalent file called `CC_Grid_Sprite_Sheet_v2-ORIGINAL.png` without faces, that you can use as a basis. Use an image editor to change this as your please.

* `images/logo.png` - This currently says Candy Crush Sara.

* `index.html` - You probably want to change the title. There's not a great deal here, and it's probably pretty ugly so if you fancy you can also change `basic.css` to make it look pretty.

* `main.js` - This is where all the magic happens. It is quite literally magic, so I've earmarked the noteworthy places that can be changed with comments starting with `AG`


### Putting it live
Once you've made whatever changes you like, you can then push these back up to the `master` branch of your forked repository (if that doesn't sound like English, read up on Github).

Github then lets you serve websites from your master branch. Click on *Settings*, scroll to the section called *Github Pages* and change the source to `master`. If all went well, it should have published at `https://<yourusername>.github.io/candy`


