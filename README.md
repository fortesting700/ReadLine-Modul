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

We return the value written to the terminal

The following code explains how a user can interact. The terminal prompts a question, “How old are you”. The users enter their response. The program notes the response and terminal then responds with “Really? I'm too”. The program is terminated since readline is closed in line 13.

```
![image](https://user-images.githubusercontent.com/119097684/204080999-86b3a4eb-869d-46ed-8250-1c16fc5bad45.png)

