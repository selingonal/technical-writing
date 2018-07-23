# How to use Markdown
Last Updated: July 2018

Welcome to this markdown guide, this resource is here to provide information on Markdown's syntax and how to use it as a formatting tool.

## What is Markdown? 
Markdown is a "lightweight markup language" with "plain text formatting syntax". Basically it's a tool to format simple text by converting certain combinations or usages of symbols into HTML commands to change the appearance of the text.  
It is usually used to format README files (hence the .md extension)


## Let's begin: Headings
 
Headings, like the one you see at the top of the page, are made using a single # sign.  
ex: 
```
	# How to use Markdown
```
These types of headings separate main ideas and sections of your file.

There area also cases where you might need a subheading, such as at the beginning of this section and the one before, entitled "What is Markdown?"  
These subheadings are created using two # signs.  
ex: 
```
	## What is Markdown?
```
You can use these to separate subtopics, just as you would in any other document.


## Section Content: 

Markdown does not require any sort of formatting or tags to write in plain text. To start a new paragraph leave one blank line between two bodies of text.  
ex: 
```
These types of headings separate main ideas and sections of your file.

There area also cases where you might need a subheading, such as at the beginning of this section and the one before, entitled "What is Markdown?"  
```

Linebreaks are created by leaving the end of one line blank, spacing twice, and returning to a new line directly below the first.  
ex:
```
This is the first line I want to use in my paragraph.  
This is the second, in the same paragraph
```
Be aware that in the first line above, I have pressed the spacebar _twice_ before making a new line. 

---

Markdown also provides means of depicting different text attributes such as:
1. **bold**
2. _italic_
3. `monospace`

See how to format these below:
```
**bold**
_italic_
`monospace`
```
Note: the character used for the monospace attribute is called a "back quote". It is located unter the tilde (~) key on the top left corner of your keyboard. Please do not confuse this with a single quotation mark.  

You could also use 3 of these symbols in succession and surround a body of text to allow for multiple lines of monospace font. This is typically used for inserting lines of code into your documentation. 

## Lists, Links, and images

Markdown provides a simple way to create lists.  
A bulleted list simply needs an asterisk at the beginning of each item of the list, it would display as:
* Item 1 
* Item 2
* Item 3
but under the hood it would be: 
```
* Item 1 
* Item 2
* Item 3
```

Similarly, a numbered list would display as: 
1. Item 1 
2. Item 2
3. Item 3
but would look like: 
```
1. Item 1 
2. Item 2
3. Item 3
```

---

Horizontal Rules like the one seen directly above can be created with 3 successive hyphens:`---`

A **Link** can be inserted as such: 
[Click Here](http://google.com).

```
[Click Here](http://google.com).
```
An **Image** can be inserted like so:
```
![Image](Image_icon.png)
```