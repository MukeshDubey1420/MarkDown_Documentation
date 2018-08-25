### Markdown is a way to style text on the web. You control the display of the document; formatting words as **Bold** or *italic*, adding images, and creating lists are just a few of the things we can do with Markdown.
## Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like `#` or `*`.

#### Markdown is a **Text-to-HTML conversion tool** for web writers. Markdown allows  you to write using an *easy-to-read, easy-to-write plain text format, then convert it  to structurally valid XHTML (or HTML)*.

## How to Write Markdown ..??

* Go to GitHub
* Create a new repo and ask that it have a `README.md` file created.
* Edit the README.md file to contain any Markdown you want.
* Then flip over to the “Preview changes” tab
Each time you switch to that tab, Github converts the Markdown that  you wrote to HTML and displays the results.

    or
* creating the Files with the `.md or .markdown` extension .   

## Learning The Basics ..

### Headings..
* To specify that a line is a heading, start it with a hash mark `(#)`

* A heading line can start with `1 to 6 hash marks,` corresponding to HTML’s h1, h2, h3, h4, h5, and h6 tags.

```

# This is a `h1` Tag.
## This is a `h2` Tag.
### This is a `h3` Tag.
#### This is a `h4` Tag.
##### This is a `h5` Tag.
###### This is a `h6` Tag.
```
Output is shown below.

# This is a `h1` Tag.
## This is a `h2` Tag.
### This is a `h3` Tag.
#### This is a `h4` Tag.
##### This is a `h5` Tag.
###### This is a `h6` Tag.

### Horizontal line
 Using `<hr>` tag.
 ```
 `<hr>`
 ```
 <hr>

* Those who have good knowledge of Frontend (HTML,CSS) They Guys can Relate This.

### Paragraphs..

* A paragraph is one or more consecutive lines of text.
* To create a new paragraph, separate it from the previous paragraph with a blank line.
* `<p>`When converting to HTML, the paragraph is wrapped in a p tag `</p>`.

### Blockquotes

* If you need to indicate a quotation in your document, use the notation, that  has been used in plain-text e-mail since the dawn of time
that is, `start each line with a “greater than” (>) symbol`.

* Blockquotes can be nested and can contain other markdown elements

```
> # This is a heading inside of a blockquote.
>
> Here’s the text of paragraph 1 in the blockquote
>
> > Here’s a quote within a quote
>
> Here’s the text of paragraph 2 in the blockquote
```

This Output will Look Like This ,
> # This is a heading inside of a blockquote.
>
> Here’s the text of paragraph 1 in the blockquote
>
> > Here’s a quote within a quote
>
> Here’s the text of paragraph 2 in the blockquote.

### Emphasis (Bold and Italics)
* To emphasize a phrase, surround it with asterisks or underscores.

```
I am an *Italic* Text.
and , I am also an _Italic_ Text.
I am **Bold** Text .
and i am also __Bold__
But , I am _**Bold & Italic**_ Text.

<del>I am Strike Through tag</del>

```
Output will LOOk Like.

I am an *Italic* Text.

and , I am also an _Italic_ Text.

I am **Bold** Text .
and i am also __Bold__

But , I am _**Bold & Italic**_ Text.

<del>I am Strike Through tag</del>

In HTML, the former will be translated as an `em` tag; the latter as a `strong` tag.
By convention, em tags appear in `italics` while `strong` tags appear in `bold`.

### Lists
* You can create two types of lists (just like in HTML)
 * Unordered lists:- use `*, +, or -` followed by a space.
 * Ordered lists:- use numbers followed by periods and a space.


```
* This is a list
 * From here Nested List starts.
 * Items can have multiple paragraphs.
 * if you need them just indent by four spaces.

     and have blank lines between items

* Here's the end of the list

Here's the start of a new paragraph

1.  Here's an ordered list that follows
2.  with multiple items
3.  as many as you need

```
Output is as Follows.

* This is a list
 * From here Nested List starts.
 * Items can have multiple paragraphs.
 * if you need them just indent by four spaces.

     and have blank lines between items

* Here's the end of the list

Here's the start of a new paragraph

1.  Here's an ordered list that follows
2.  with multiple items
3.  as many as you need

##### Embedded Lists

* You can embed one list inside another, as many levels deep as you need  (within reason). Just prefix each level with four spaces in front of the list  marker. Level 1 is a normal list. Level 2 lists have four spaces at the start of  their lines. Level 3 lists have eight spaces at the start of their lines, etc.

```
* This is a list.
  * This is an embedded list.
     1. that is indicated by adding.
     2. four spaces in front of the list marker.
  * Go as deep as you need.
* This is the second item of the outer list.
* And this is the third item.

```
* This is a list.
  * This is an embedded list.
     1. that is indicated by adding.
     2. four spaces in front of the list marker.
  * Go as deep as you need.
* This is the second item of the outer list.
* And this is the third item.

```
Alternatively,

- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this
Check the output below.
```
Alternatively,

- Dashes work just as well
- And if you have sub points, put two spaces before the dash or star:
  - Like this
  - And this

### Code Elements and Code Blocks
* You can have “code” elements either in-line or in a stand-alone block
* In-line code is indicated by surrounding the word or phrase with backticks.

```
Be sure to call the `init()` method before you call `doMyWorkForMe()`

the ` ` is the syntax to represent a Inline code.
the ``` Insert Your Big Code here.. ``` is the syntax to represent a code Block.

Stand-alone code blocks are indicated by four spaces at the start of the line

### Syntax Highlighting

```javascript
def check(dir: Path) = {  if (!exists(dir)) {
error(s"Directory: <$dir> does not exist.")
}
}


```python
print("Hello World!!!")
name = input("Enter Your Name ")
if len(name)> 2:
  print("Hello" + name + "Welcome tO Markdown tutorial")
  exit()``
```


* the ` ` is the syntax to represent a Inline code.
* the ``` Insert Your Big Code here.. ``` is the syntax to represent a code Block.

### Syntax Highlighting

``` javascript
def check(dir: Path) = {  if (!exists(dir)) {
error(s"Directory: <$dir> does not exist.")
}
}

```

```python
print("Hello World!!!")
name = input("Enter Your Name ")
if len(name)> 2:
  print("Hello" + name + "Welcome tO Markdown tutorial")
  exit()
```


### Links
* Markdown supports two styles of links. I’ll show you the most common one.
* To create a link, you indicate the text of the link, and then the link itself
* The `text goes in square brackets [], the link goes in parentheses()`.

```
Check out My [GitHub](https://github.com/MukeshDubey1420) for a cool way to view git repos.
```
Check out My [GitHub](https://github.com/MukeshDubey1420) for a cool way to view git repos.

* You can add a `link title` if you want
```
Check out [GitHub](https://github.com/MukeshDubey1420 "It's cool!") for a cool way to view git repos.
```
Check out [GitHub](https://github.com/MukeshDubey1420 "It's cool!") for a cool way to view git repos.

* Link titles appear as a `tool-tip in web browsers when you hover over a link`.
They also increase the accessibility of your page as they can be processed  by screen readers and other similar tools.


### Link To images

* Images have a similar syntax to links.
```
![alt text](href "title")
For example
![Mukesh Dubey](https://avatars1.githubusercontent.com/u/25473584?s=460&v=4  "Mukesh Dubey")
```
![Mukesh Dubey](https://avatars1.githubusercontent.com/u/25473584?s=460&v=4  "Mukesh Dubey")


### Refer To someone By Username.

* GitHub supports many extras in Markdown that help you reference and link to people. If you ever want to direct a comment at someone, you can prefix their name with an `@` symbol: Hey   @MukeshDubey1420  — love your Documentation!
* Typing an `@` symbol, followed by a username, will notify that person to come and view the comment. This is called an `“@mention”`, because you’re mentioning the individual. You can also `@mention` teams within an organization.

### TasksList

```
- [x] This is a complete item
- [ ] This is an incomplete item
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```

- [x] This is a complete item(Task is Checked.)
- [ ] This is an incomplete item(Task is unchecked.)
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

### Tables
* You can create tables by assembling a list of words and dividing them with `hyphens -` **(for the first row)**, and then **separating each column** with a `pipe "|"` symbol:

```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
```
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column

### Emojis For Markdown.

[Click this Link to Have Aa list of Complete Cheet Sheet For Emoji's That are used in Markdown.](https://www.webfx.com/tools/emoji-cheat-sheet/ "Github Emoji Cheet Sheet")

Typing `:` will bring up a list of suggested emoji. The list will filter as you type, so once you find the emoji you're looking for, press Tab or Enter to complete the highlighted result.

```
Syntax--
Designed With :heart: by  [@MukeshDubey1420](https://mukeshdubeyportfolio.netlify.com/   "My PortFolio Link")
```

Designed With :heart: by  [@MukeshDubey1420](https://mukeshdubeyportfolio.netlify.com/   "My PortFolio Link")

### Ignoring Markdown formatting
* You can tell GitHub to ignore (or escape) Markdown formatting by using `\` before the Markdown character.

`Let's rename \*our-new-project\* to \*our-old-project\*.`

Let's rename \*our-new-project\* to \*our-old-project\*.


## Thank You ..:relaxed:
