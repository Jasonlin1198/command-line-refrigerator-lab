# Lab: Clean Up The Fridge!

![Dirty Fridge](https://img.clipartfest.com/b59ba28ca25e5c8b42c7b5de82e491c5_mortimer-dirty-refrigerator-clipart_462-585.jpeg)

Your kitchen is a disaster. We're not blaming anyone, but when we opened up the fridge today, we almost passed out. Please, please clean up your mess.

## Instructions

You'll be practicing your command line skills by organizing the files in your refrigerator.

1. Fork and Clone this repository. Once you have it on your maching, `cd` into the project directory. Here is what your refrigerator currently looks like:

![tree of directories](https://s3.amazonaws.com/upperline/curriculum-assets/command-line/current-tree.png)

2. Using `ls`, `pwd`, `cd`, `mv`, and `rm`, get the food files in their correct directories. Here's how we'd move the watermelon from the meat directory into the fruits directory (first you'll need to `cd` into the meat directory):

```
mv watermelon.jpg ../produce/fruit
```
This will move the watermelon up one level (..) which will place it in the general fridge directory, and then it is moved into "produce" and then "fruit"


3. Use `rm` to remove any roaches you find!

4. Use `touch` to add at least three new foods - label them as .txt files. For example (in the fruit directory) type:

```
touch peaches.txt
```
