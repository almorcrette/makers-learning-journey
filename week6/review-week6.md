## Week 6

### Personal goals for the week

* I can explain how asynchronous programming is different from synchronous, blocking programming.
* I have applied a coherent process to learn a new language - Javascript
* I have test-driven a simple Javascript program using Node and Jest.
* I have managed my own wellbeing, during a stressful time at home.

### Plan for the week

* Complete the [JS fundamentals syllabus](https://github.com/makersacademy/javascript-fundamentals#sequence), and test-drive the [thermostat](https://github.com/makersacademy/javascript-fundamentals/blob/main/challenges/04_thermostat.md) progam, including [building it as a web app using Express.js](https://github.com/makersacademy/javascript-fundamentals/blob/main/challenges/07_web_server.md)
* Repogram my [Ruby Bowling challenge](https://github.com/almorcrette/bowling-challenge-ruby) in [JS](https://github.com/makersacademy/bowling-challenge)
* Learn about [asynchronous JS and callbacks by participating in the workshop on it](https://github.com/makersacademy/javascript-fundamentals/tree/main/workshops/async-js-and-callbacks), and watching additional videos about [callbacks](https://www.youtube.com/watch?v=xHneyv38Jro) and the [the event loop](https://www.youtube.com/watch?v=8aGhZQkoFbQ).
* If I need to, fly solo to maintain flexibility and manage my mental health while my wife is in hospital.

### Self-assessment

* I can explain how asynchronous programming in JS works. Drawing on [this explanation](https://www.youtube.com/watch?v=8aGhZQkoFbQ):
```
JS is single-threaded which means it can only process one block of code at a time.

In single threaded synchronous programming languages, a script is executed one line at a time in the order they come in a script: each line is read and pushed onto the call stack, and is executed in order, popping out of the stack once they are executed. A later block in the script will be executed after an earlier one.

In JS, to avoid some blocks of code that take a longer(er) time to complete (such as ones that fetch data from web APIs) from blocking the call stack, once they are reached on the call stack, they are moved off the call stack and onto a task queue for callback later by the event loop. Once a process executed by the block is complete, the event loop will push the callback block back onto the call stack for execution, once the call stack is clear.

This allows concurrency, because lengthy blocks of code do not 'hog' the call stack, as they are taken off the call stack and put into the task queue while the length process is executed. While that happens the call stack can continue executing other code (which comes later in the script).

This means that the call stack is available for other quick processes, such as browser refresh. A consequence of this is that blocks of code higher up the script may finish executing after blocks of code later in the script. It also means that all callbacks will be executed after the end of blocks of code without a callback.JS is single-threaded which means it can only process one block of code at a time.

In single threaded synchronous programming languages, a script is executed one line at a time in the order they come in a script: each line is read and pushed onto the call stack, and is executed in order, popping out of the stack once they are executed. A later block in the script will be executed after an earlier one.

In JS, to avoid some blocks of code that take a longer(er) time to complete (such as ones that fetch data from web APIs) from blocking the call stack, once they are reached on the call stack, they are moved off the call stack and onto a task queue for callback later by the event loop. Once a process executed by the block is complete, the event loop will push the callback block back onto the call stack for execution, once the call stack is clear.

This allows concurrency, because lengthy blocks of code do not 'hog' the call stack, as they are taken off the call stack and put into the task queue while the length process is executed. While that happens the call stack can continue executing other code (which comes later in the script).

This means that the call stack is available for other quick processes, such as browser refresh. A consequence of this is that blocks of code higher up the script may finish executing after blocks of code later in the script. It also means that all callbacks will be executed after the end of blocks of code without a callback.
```

__have sought feedback from Leo on this explanation__

* I [test drived the thermostat program and built it as a (very) simple webapp](https://github.com/almorcrette/js-practice)
* I did decide to fly solo this week to conserve my social / emotional batteries while my wife was very sick and in hospital.
* __However__ I got __quite stuck__ during the reprogramming of the Bowling Challenge trying to get user input with `readline` to work, getting stuck with asynchronous aspects of the code.
* I completed the [JS fundamentals syllabus](https://github.com/makersacademy) without any real problems, I did __struggle__ researching and learning about aspects of JS that I didn't understand during the weekend challenge, so feel like I still have a way to go with applying a coherent process to learning a new language.


### Next steps

* Get feedback on my description of asynchronous programming

__have sought feedback from Leo on this explanation__

* Deepen my understanding of asynchronicity and callback functions, [watching this](https://www.youtube.com/watch?v=xHneyv38Jro), and considering [this practical](https://github.com/makersacademy/javascript-fundamentals/tree/main/practicals/callbacks)

__complete__

* Read about [learning a new language by translation](https://hackmd.io/kMNgXiPHQf2Q_P9A-tnS9A) to help me gain more confident in applying a coherent process to learning a new language, and learning using online materials

__complete__