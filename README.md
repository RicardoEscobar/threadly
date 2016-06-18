# Threadly
## Description
In this project you'll help create a commenting service using the .keypress event, .text(), and .appendTo.

## Objective
Threadly is creating a commenting service. [Here's what it looks like]("https://s3.amazonaws.com/codecademy-content/projects/2/threadly/index.html"). Type a comment into the comment box and click the Post button.

## Tasks
### 1.
Look at `index.html`:

In the `.main` section, there is a `<form>` element containing an input `<id="comment">`.

In the `.main` section, there is also a `<ul class="comments">` element. When the form is submitted, the value of `<input id="comment">` is prepended to `<ul class="comments">`.

Look at `script.js`:

There's a submit event handler attached to the form element. When the Post button is clicked and the form submits, the code inside this event handler runs.

### 2.
In `script.js`, inside the submit event handler above the if statement, fetch the value typed into the `<input id="comment">` using `.val()`. Save the value into a variable named `comment`.

### 3.
Inside the `if` statement, if `comment` is not empty, a new `<li>` element is created and saved into a variable named `html`. Prepend `html` to the `<ul class="comments">` element using `.prependTo()`.

### 4.
After prepending `html` to the `list`, set the value of `<input id="comment">` to an empty string `""` to clear out the comment box.
