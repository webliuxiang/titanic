# Titanic

A collection of animated icons + javascript library.

![Preview](https://maxcdn.icons8.com/app/uploads/2017/01/animated-icons-preview.gif)

## Installation

You can install it either via CDN or npm.

### CDN

Insert this string to your HTML head:
```
<script src="https://cdn.rawgit.com/icons8/titanic/1af9dce0/dist/js/titanic.min.js"></script>
```
And initialize it before the body closes:

```
<script>
    titanic.begin();
</script>
```
This way, you can add icons anywhere in your HTML using this tag:
```
<div id='chat' class='titanic'></div>
```
Where chat can be any of these:
* caps
* chat
* checkbox
* expand
* expensive1
* expensive2
* idea
* mailbox
* mic
* no_microphone
* online
* pause
* quick_mode
* shopping_cart
* smile
* stop
* unlock
* zoom

### Hosting your images

If you'd like to host your images on your server instead of rawgit, pass the base URL with the init() function:
```
titanic.begin('/my/base/directory/');
```
Then, if you have a div with id="chat", Titanic will search for icons in /my/base/directory/chat.json.

## npm

```
npm install titanic --save
```

## Credits
JavaScript is basically [bodymovin](https://github.com/bodymovin/bodymovin) plus few lines of my code. It's a solid library with an awesome name. Thank you, guys.

Icons are created by [Margarita Ivanchikova](https://dribbble.com/imargarita) from [Icons8](https://icons8.com/). She has many more awesome animations in her portfolio:

![Magritte](https://d13yacurqjgara.cloudfront.net/users/1003944/screenshots/2385329/10.gif)