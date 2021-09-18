# Introduction
Simple and Small Basic CSS UI where you can make your
project beautiful. textarea, buttons, edittext, typography, weights, gravity, and helpers.

# Getting Started
Copy this code and paste it to your project so you can save your time.
```html
<link href="https://cdn.jsdelivr.net/gh/someoneperson112/Simple-UI@main/src/simpleui.css" rel="stylesheet">
```
You can use Minified Version
```html
<link href="https://cdn.jsdelivr.net/gh/someoneperson112/Simple-UI@main/src/simpleui.min.css" rel="stylesheet">
```
Example Template:
```html
<!DOCTYPE HTML>
<html>
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/gh/someoneperson112/Simple-UI@main/src/simpleui.min.css" rel="stylesheet">
  </head>
  <body>
    <h2>Hello, World!</h2>
  </body>
</html>
```

# Documentation
Here you can learn how to use Simple UI.

## Typography
This feature change any heading font weight to normal and resizes a little bit, this doesn't required any classes.

## Buttons
**Note that this feature don't have outline version yet**
This feature is for buttons but you need to add the class manually, use `btn btn-COLOR`.

All colors and its class will be listed here (copy and paste the snippets):
|Colors|Class|VSCode Snippets|
|------|-----|--------|
|Light|btn btn-light|button.btn.btn-light|
|Dark|btn btn-dark|button.btn.btn-dark|
|Blue|btn btn-blue|button.btn.btn-blue|
|Gray|btn btn-gray|button.btn.btn-gray|
|Green|btn btn-green|button.btn.btn-green|
|Yellow|btn btn-yellow|button.btn.btn-yellow|
|Red|btn btn-red|button.btn.btn-red|

Buttons have 3 types:
`Plain (default)`, `Flat`, and `Raised`.
To use any of these types, add it like this:
```html
<button class="btn btn-light-flat">Flat Button</button>
```
or
```html
<button class="btn btn-light-raised">Raised Button</button>
```

## EditTexts
EditTexts is just an input,
once an element is editable, it's an EditText.
```html
<!-- EditText -->
<input type="text">
```
This feature is not automatically detects an EditText due to password, number, etc types, but i will tried my best!
so you can use this class: `edittext-view` to identify the edittext view.

There are 2 types of edittext: `Plain (default)` and `Rounded`.
you can just:
```html
<!-- Plain -->
<input type="text" placeholder="First Name" class="edittext-view edittext">

<!-- Rounded -->
<input type="text" placeholder="Last Name" class="edittext-view edittext-rounded">
```

**Note that this feature only have 1 color (blue)**
> You can change it manually!

## Textareas
Just like EditText, it's the same thing but without `textarea-view`.

Example:
```html
<textarea class="textearea">Hello</textarea>
<textarea class="textearea-rounded">World</textarea>
```

## Weights
Android Apps also have "weight", so i also add one for Simple UI but complicated (a little bit).

To specify the family of the weight, use `weight-family`.

then, any element with `weight-1|weight-2|weight-3|weight-4|weight-5` class.

Never forget to add the orientation of the family: `orientation-vertical|orientation-horizontal` (class)

Example:
```html
<div class="weight-family orientation-horizontal">
  <p class="weight-2">Hello, </p>
  <p class="weight-1">World!</p>
</div>
```

## Gravity
Android Apps also have "gravity", here the list by the way:

|Direction|Class|
|---------|-----|
|Left/Start|gravity-left|
|Right/End|gravity-right|
|Top|gravity-top|
|Bottom|gravity-bottom|
|Center Vertically|gravity-center-vertical|
|Center Horizontally|gravity-center-horizontal|

# Ending
Thanks for using Simple UI, please let me know if there's any bugs.
> Version: 1.0
