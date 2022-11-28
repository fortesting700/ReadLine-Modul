# Readline module

# What is Readline module 

```
Readline Module in Node.js allows the reading of input stream line by line. This module wraps up the process standard output and process standard input objects. Readline module makes it easier for input and reading the output given by the user.(Readline module- take information from the terminal, save it and carry out certain work on it)
```

# How we can do this? 

```
To do this, we first open JS file. For example arg.js. Node Js has readline module for this. First we call the Readline module.

```

![image](https://user-images.githubusercontent.com/119097684/204079256-3892217f-1e67-4d05-80cf-01f551ab2a57.png)


# readline.createInterface

```

The method createInterface() takes two parameters – the input stream and output stream – to create a readline interface. The third parameter is used for autocompletion and is mostly initialized as NULL. For example, one may want to access the tab, similar to how we might press the TAB key to complete a give string.

As input parameter, createInterface uses process.stdin. As output parameter, createInterface uses process.stdout.

```

![image](https://user-images.githubusercontent.com/119097684/204077475-092755b6-6818-43ff-8edf-dafa038719e5.png)

# readline.pause()
```
Pauses the readline input stream, allowing it to be resumed later if needed.

Note that this doesn't immediately pause the stream of events. Several events may be emitted after calling pause, including line.
```

# readline.resume()
```
Resumes the readline input stream.
```

# readline.close()
```
Closes the Interface instance, relinquishing control on the input and output streams. The "close" event will also be emitted.
```

# Code
```
Example: 1

We subtract the number entered by the user in the terminal. The program is terminated since readline is closed in line 13.

```
![image](https://user-images.githubusercontent.com/119097684/204081304-74630e7a-d12f-4e07-a639-809dcd0e6f9c.png)

```
Example: 2

In this exercise, we will edit the array using data from the terminal.

The program asks us for a number. The program will run until the user enters any information other than a number. If you enter data other than a number, the program stops and returns an array.

In the 11 line of the program, the user is asked for a number.

In the 12 line of the program, it is checked that the number entered by the user is a type number, and not a NaN. If the check goes correctly adds to the array and recursive functions will call back and perform ammals from another.
In the 11 line of the program, the user is asked for a number.
If an error passes the check i.e. not a number if another type is entered, the array will be returned to the user and the program will stop working. We can see this in rows 16, 17, 18


```
![image](https://user-images.githubusercontent.com/119097684/204220445-520cd7ba-31b6-4643-a513-4d6093f270cb.png)

# Multiple Lines (algorithm input)
```
Sometimes, particularly in algorithm questions, you might want to:

Read in multiple lines
Parse the input, line-by-line
Call an algorithm, only when you’ve read the entire input
To do this, we’ll take an event-driven approach.

Readline’s .on() takes two arguments: an event and a callback function. Click on the link and take a look at some of the events you can use.

Let’s set up a function that reads lines, then stores the input in an array until it gets too long.

We’ll tell readline what to do in ‘line’ event, which is triggered when a newline character is seen (you press enter in the terminal), with the line itself as the argument.
```


