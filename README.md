# Readline module

# What is Readline module 

```
Readline module- take information from the terminal, save it and carry out certain work on it.
```

# How we can do this? 

```
To do this, we first open JS file. For example arg.js. Node Js has readline module for this. First we call the Readline module.

```
![image](https://user-images.githubusercontent.com/119097684/204076992-c13134d0-45b5-4d70-8452-09e00b7ce4ca.png)

# Create interface

```

The method createInterface() takes two parameters – the input stream and output stream – to create a readline interface. The third parameter is used for autocompletion and is mostly initialized as NULL. For example, one may want to access the tab, similar to how we might press the TAB key to complete a give string.

As input parameter, createInterface uses process.stdin. As output parameter, createInterface uses process.stdout.

```

![image](https://user-images.githubusercontent.com/119097684/204077475-092755b6-6818-43ff-8edf-dafa038719e5.png)
