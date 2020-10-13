# FloatingWindowApp

This repository contains source codes of a test app related to the StackOverflow question: 

[How to create a floating window like Clipboard Pro App?](https://stackoverflow.com/questions/52980478/how-to-create-a-floating-window-like-clipboard-pro-app)

<br/>

![Visual Result][1]

Sepcial thanks to [bolds07](https://github.com/bolds07) for reporting the issue leading to the fact that we should always use application-level context to get an instance of `WindowManager`. In this case, the floating window is going to be shown, even after the activity gets minimized.

  [1]: https://media.giphy.com/media/1k3WSA8AbDDZ0uC9LM/giphy.gif
