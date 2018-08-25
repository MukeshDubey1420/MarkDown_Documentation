## Markdown is a way to style text on the web. You control the display of the document; formatting words as **bold** or *italic*, adding images, and creating lists are just a few of the things we can do with Markdown.
## Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like `#` or `*`.
### Markdown is a **Text-to-HTML conversion tool** for web writers. Markdown allows  you to write using an *easy-to-read, easy-to-write plain text format, then convert it  to structurally valid XHTML (or HTML)*.

## How to Write Markdown ..??

* Go to GitHub
* Create a new repo and ask that it have a `README.md` file created.
* Edit the README.md file to contain any Markdown you want.
* Then flip over to the “Preview changes” tab
Each time you switch to that tab, Github converts the Markdown that  you wrote to HTML and displays the results.

## Learning The Basics ..

### Headings..
* To specify that a line is a heading, start it with a hash mark `(#)`

* A heading line can start with `1 to 6 hash marks,` corresponding to HTML’s h1, h2, h3, h4, h5, and h6 tags.


# This is a `h1` Tag.
## This is a `h2` Tag.
### This is a `h3` Tag.
#### This is a `h4` Tag.
##### This is a `h5` Tag.
###### This is a `h6` Tag.
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
But , I am _**Bold & Italic**_ Text.

```
Output will LOOk Like.

I am an *Italic* Text.

and , I am also an _Italic_ Text.

I am **Bold** Text .

But , I am _**Bold & Italic**_ Text.

In HTML, the former will be translated as an `em` tag; the latter as a `strong` tag.
By convention, em tags appear in `italics` while `strong` tags appear in `bold`.

### Lists
* You can create two types of lists (just like in HTML)
 * Unordered lists:- use `*, +, or -` followed by a space.
 * Ordered lists:- use numbers followed by periods and a space.
