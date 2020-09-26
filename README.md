This script will fit the ao3 fic header inside your own fanfic. It's fun to use for meta fanfictions if your character likes to write fanfic on the side.

[live example here](https://archiveofourown.org/works/26662207)

The links are functioning if you want them to function (you'll need to add all the urls yourself) and **they will make the proper animation when you hover over them**. 

It is quite easy to achieve. It requires 2 parts: HTML code and a workskin in css. 

# How to use it
### Set up a new work skin
This is easy don't worry. Ao3 makes it really fast.
* Go to your **dashboard** on Ao3 and then on the right you'll find **"Skins"**. Click on there
* On the left there's a button **"Create site Skin"**
* Set the **Type** as **'Workskin'**, this is important!
* Add a title for you to remember it (something like 'Fic Header' should work fine)
* Now Scroll and copy paste  [this code](https://github.com/electricalice/fic-header-workskin/blob/master/workskin-code.css)  in the part labelled **"CSS"**
* Now press submit!
* This is it!
Now your workskin is set and if you want you can use it for multiple fanfic. You don't need to set it up multiple times!

### How to modify the header to suit your needs

* Go and take [this code here](https://github.com/electricalice/fic-header-workskin/blob/master/header-code.html) and **copy-paste it in a text editor**. Notepad works just fine, **but anything that will highlight the html will be easier to work with** (there are also several online editor. Just google 'html online editor' and you'll find plenty).  Ao3 editor is not the best to make those changes and it will remove all the comments as soon as you click 'preview', making it harder to make the changes.
* I put **comment on all the parts where you should edit stuff**. Hopefully they are self-explanatory.
* To make the work tags work proper (so, become red when you hover over them) and have the right spacing between them **you'll need to keep the html sort of intact**. 
	* Each tag should look like this: `<span><a href="#">Text of the tag</a>,</span>`
	* the comma can be removed when it's the last tag in the line. 
	* it should have both the `<span>` and the `<a>` as both are needed
	* change the `href="#"` if you want to add a functioning link. You can leave it like those if you want to, the links will still look real but nothing will happen if someone clicks on them
* **Title, Author, Summary and Author notes should be self explanatory**. You can use normal html inside (so, `<br>` if you want to break line, `<b>` for bold and `<I>` for italics
* Now save your text somewhere and you can add the code to your fic! 
	* go edit your fic 
	* find the option **"Select Work Skin"** and find in the dropdown menu the workskin you saved earlier.
	* make sure you are **on html mode** and not Rich Editor (you should be, by default) 
	* **copy paste** all your code in the point of the story where you want to put the header

And this is it. Be sure to preview your work, as something might have happened that made everything wonky!
