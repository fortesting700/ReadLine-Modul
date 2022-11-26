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


# Syntax of Create interface

```

The method createInterface() takes two parameters – the input stream and output stream – to create a readline interface. The third parameter is used for autocompletion and is mostly initialized as NULL. For example, one may want to access the tab, similar to how we might press the TAB key to complete a give string.

As input parameter, createInterface uses process.stdin. As output parameter, createInterface uses process.stdout.

```

![image](https://user-images.githubusercontent.com/119097684/204077475-092755b6-6818-43ff-8edf-dafa038719e5.png)

# Code
```
Example: 1

We subtract the number entered by the user in the terminal. The program is terminated since readline is closed in line 13.

```
![image](https://user-images.githubusercontent.com/119097684/204081304-74630e7a-d12f-4e07-a639-809dcd0e6f9c.png)

```
Example: 2

Now we will perform a more difficult task. We write the data entered from the terminal to the array calculated in a specific mold and return it to the user in the table view. Here we also use the generator function
```


