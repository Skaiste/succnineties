# [Stirling University Computer Clubs Give It A Go: 90's challenge](https://skaiste.github.io/succnineties/)

Hey guys, welcome to the succ 90’s website GIAG.
The idea as I’m sure you know is to build a website as tacky and functional as possible that reflects the pure genius some back in the 90s did. Here is a real basic webpage illustrating some features and providing you with a template to start from. Of course whoever has any experience in HTML, CSS and JS etc can just jump right in and work from scratch. But the template is here for anyone without any experience and below a basic explanation of the tags to get you started.

`<head> </head>`
Within these two tags in the HTML document, there is a referenced CSS document, since the demo connects to an already created CSS document this isn’t something you need to worry about right now. Just know it works and it is where the CSS goes for now. So! If you look at any text between two of these symbols `< >` they are known as tags. Tags have properties that let a web browser display the content just as you want it. For example `<p>` stands for paragraph, so any text written between two connected `<p> </p>` tags, is essentially a paragraph to be displayed on screen. Now within some tags, you will see the term `id` and `id=` followed by a word. This is a method of giving a particular name to a part of a web page so if you connect a CSS file and write some code to change the way it looks, it will only change the tags sharing the same id.

An example is below!
Bare in mind, however the code looks in here, there ARE other ways to do it, some better and worse. These methods are pretty stock and easy to use :)

So if we look at the code below, both a div tag with an id of ‘sidebar’ and one with an id of ‘const’ exist. Meaning if we look into our css document. We can find the corresponding css. In web development there are multiple ways of having identifiers, in HTML you can have class and id. id is denoted with `id=“”` and class with `class=“”`. When we look at css, we look for the same id but prefaced with a `#`. The `#` symbol means that that block of CSS is applying style specifically to div tags with the same id.
```html
<div id="sidebar">
  <ul>
    <li><a href="index.html" >Home!</a></li>
    <li><a href="abductme.html" >abduct me</a></li>
  </ul>
  <img src="images/aliens3.gif">
</div>
<div id="const">
  <img src="images/foot1.gif">
</div>
```

So these are the properties of sidebar. Sidebar is used as an unordered list type menu. So the menu to the left is the sidebar. We can see here it's font size, that it has a border made of little dashes, its colour etc. These css properties along with any other css property can go inside any #id. Hopefully this helps you towards building your tacky webpage. 
Write code, play around, try connecting a new html div to css.
```css
#sidebar {
	font-size: 28px;
	border: 2px dashed;
	border-color: black;
	height: 400px;
	width: 150px;
	color: blue;
	text-shadow: 4px 2px #ff0000;
}
```

Find yourself some tacky gifs online and popart, flashing texts. 
W3schools is a perfect reference to html and css tags.
“w3schools html tags” + “w3schools css properties” are pretty appropriate google searches if you need reference.
I find the spacejam website is the best example for a good 90s website 
