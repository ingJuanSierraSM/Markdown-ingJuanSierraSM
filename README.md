
Markdown Learning
=================
Copyright (c) 2023 Juan Sierra | ing.juan.sierra.sm@gmail.com

What is Markdown?
-----------------

-----------------

Markdown is one of the world's most popular ___lightweight markup languages___:

- Created by __John Gruber__ in 2004.
- Use __Markdown's syntax__ to define the format of the text.
- Markdown's syntax __is as readable as possible__, and we can read it even if it isn't rendered.
- It can be used to create ___websites, documents, notes, books, presentations, email messages,___ and ___technical documentation___.
- It is __portable__ because it is a simple text file and is supported and used by many websites like __Reddit__ and __GitHub__.

Markdown's syntax
=================

Headings
--------

--------

- Add from 1 to 6 (#) (depending on the heading level) before the words that compose it.
    - Always put a space after the number signs (#).
    - Put blank lines before and after a Heading.
- There is an alternative syntax for heading levels 1 and 2, on the line below the text, add any number of:
    - == characters for heading level 1
    - -- characters for heading level 2.
    
    <br>

    ```markdown
    # h1: Heading Level 1
    ```
    
    ```markdown
    h1: Heading Level 1
    =====
    ```

    # h1: Heading Level 1
    
    <br>

    ```markdown
    ## h2: Heading Level 2
    ```
    
    ```markdown
    h2: Heading Level 2
    ------------
    ```
    ## h2: Heading Level 2
    
    <br>

    ```markdown
    ### h3: Heading Level 3
    #### h4: Heading Level 4
    ##### h5: Heading Level 5
    ###### h6: Heading Level 6
    ```
    
    ### h3: Heading Level 3
    #### h4: Heading Level 4
    ##### h5: Heading Level 5
    ###### h6: Heading Level 6

<br>

Paragraphs
----------

----------

Separate with a __blank line__ (Type Enter) 2 paragraphs or lines of text.

```markdown
Paragraph 1.

Paragraph 2.
```

Paragraph 1.

Paragraph 2.

<br>

Line Breaks
-----------

-----------

- Add 2 or more spaces after the line text (trailing whitespace) and type Enter.
- You can use the `<br>` HTML tag as alternative.

    ```markdown
    Line text.  
    Other line text.<br>
    Other line text.
    ```

    Line text.  
    Other line text.<br>
    Other line text.

<br>

Emphasis
--------

--------

We can emphazise a text using **bold** or _italic_.

<br>

### __Bold:__

Add **two underscores or asterisks** before and after the text to be emphasized. 

```markdown
text to be __emphasized with bold__  
text to be **emphasized with bold**
```

text to be __emphasized with bold__  
text to be **emphasized with bold**

<br>

### __Italic:__  

Add **one underscores or asterisks** before and after the text to be emphasized.

```markdown
text to be _emphasized with italic_  
text to be *emphasized with italic*
```

text to be _emphasized with italic_  
text to be *emphasized with italic*

<br>

### __Bold and Italic:__  

Add **three underscores or asterisks or a combination of them** before and after the text to be emphasized.

```markdown
text to be ___emphasized with italic and bold___  
text to be ***emphasized with italic and bold***

text to be **_emphasized with italic and bold_**  
text to be __*emphasized with italic and bold*__    
```

text to be ___emphasized with italic and bold___  
text to be ***emphasized with italic and bold***  

text to be **_emphasized with italic and bold_**  
text to be __*emphasized with italic and bold*__  

<br>

- ***If you need to emphasize letters within a word, just use asterisks.***

    ```markdown
    the*word*emphasized
    the**word**emphasized
    the***word***emphasized
    ```

    the*word*emphasized  
    the**word**emphasized  
    the***word***emphasized  

<br>

Blockquotes
-----------

-----------

A __Blockquote is used to write an exact paragraph or quote__ so that it can be distinguished from the rest of the text.

- Add a __(>) before the quote or paragraph__.
- To separate paragraphs, add a __blank line by adding a (>) and typing enter__.
- Add __(>>) or more before a nested Blockquote__.
- Put blank lines __before and after Blockquote__.

    ```markdown
    > This is an exact paragraph or exact quote.
    >
    > Add a blank line between paragraphs.
    >> Nested Blockquote.
    >>> Other nested Blockquote.
    ```

    > This is an exact paragraph or exact quote.  
    > Second line.
    >
    > Add a blank line between paragraphs.
    >> Nested Blockquote.
    >>> Other nested Blockquote.

- Blockquotes __can use the most of Markdown formatted elements__ (not all).

    ```markdown
    > # Blockquote.  
    > Second line.
    > -------------
    > Add a blank line between paragraphs.
    >> - Nested Blockquote.
    >> - Nested Blockquote.
    ```

    > # Blockquote.  
    > Second line.
    > -------------
    > Add a blank line between paragraphs.
    >> - Nested Blockquote.
    >> - Nested Blockquote.

<br>

Lists
----

----

We can create ___ordered___ and ___unordered___ lists.

### __Ordered lists:__

- Add Ordered list items with __integer numbers followed by period and space__.
- The list __have to start with number__ one after, don't worry about the numerical order.

    ```markdown
    1. one item
    1. two item
    3. three item
    15321. four item
    ```
    
1. one item
1. two item
3. three item
15321. four item

<br>

### __Unordered lists:__

- Add Unordered list items with a __dash (-), asterisk (*), or plus sign (+)__ followed by a space.
- As a good practice, __only use one type of sign__ for the entire list.

    ```markdown
    + item
    + other item
    + other item
    ```

    + item
    + other item
    + other item

<br>

___* You can add another list or Markdown element to a list just by indenting it into one of its items.___

```markdown
1. one item ordered list
2. second item: add unordered list
    + item
    + other item
    + add a Blockquote
        > Blockquote
3. third item
```

1. one item ordered list
2. second item: add unordered list
    + item
    + other item
    + add a Blockquote
        > Blockquote
3. third item

<br>

Links
-----

-----

We can create a link to go to an __external website__ or a __specific section__ of the document.

- A link is made up of a ___link text___ enclosed in square brackets and the ___url___ enclosed in parentheses.
- __Optionally__, you can add a ___Title___ by enclosing in (" ") and placing it right next to the URL. This is displayed when the mouse hovers over the link.

    ```markdown
    [This is a link](https://www.markdownguide.org)  
    [This is a link](https://www.markdownguide.org "Optional Title")
    ```

    [This is a link](https://www.markdownguide.org)  
    [This is a link](https://www.markdownguide.org "Optional Title")

- A __section is a document__ ___heading___. You can use a link to go to a specific section in your document or inside an external website.
- Place the __section name__ in _lowercase_ instead of the _URL_ immediately after a __(#)__ omitting the special characters and replacing the spaces with dashes. 


    ```markdown
    # The Example: Link $ #Secti0ns

    [link to section](#the-example-link--secti0ns "Go to section")  
    [Heading IDs](https://www.markdownguide.org/extended-syntax#heading-ids)
    ```
    
    # The Example: Link $ #Secti0ns

    [link to section](#the-example-link--secti0ns "Go to section")  
    [Heading IDs](https://www.markdownguide.org/extended-syntax#heading-ids)

\* When you have links within a text it can make it difficult to read, to solve this you can use the ___Reference-style Links___ that divide the link into two parts.

- __First part:__ You put _this part in the text_. It consists of 2 sets of brackets. Inside the _first set of brackets, you put the link text_, and inside the _second set of brackets (it's not case-sensitive) you put a tag_, which is basically a text that serves as a reference to join the first part to the second part.
- __Second part:__ You can put _this part anywhere in the document_, it consists of 2 mandatory attributes and one optional:
    1. __The tag__ enclosed in square brackets followed by a colon and at least one space.
    2. __The URL__ optionally enclosed in angle brackets (< >).
    3. __(Optional)__ The Title for the link can be enclosed in double quotes (" "), single quotes (' '), or parentheses.

    ```markdown
    <!-- Readable text -->
    This is text, and you can place one or more [Reference-style Links][tag] like [link 1][1] and [link 2][Not Case-sensitive] that help us not to affect the readability of the text.

    <!-- Tags with URL: They are not rendered. -->
    [tag]: https://www.markdownguide.org/basic-syntax/#formatting-the-second-part-of-the-link "Go to Reference-style Link"
    [1]: <#links> 
    [not case-Sensitive]: #links (Go to links)
    ```

    This is text, and you can place one or more [Reference-style Links][tag] like [link 1][1] and [link 2][Not Case-sensitive] that help us not to affect the readability of the text.

    [tag]: https://www.markdownguide.org/basic-syntax/#formatting-the-second-part-of-the-link "Go to Reference-style Link"
    [1]: <#links> 
    [not case-Sensitive]: #links (Go to links)



### __URLs and Email Addresses:__ 

You should __enclose the URL or email in angle brackets (<>)__; however, if you don't, they may be _automatically converted to links_ if your Markdown processor supports it. 

```markdown
<https://www.markdownguide.org>  
https://www.markdownguide.org   
<email@example.com>

```

<https://www.markdownguide.org>  
https://www.markdownguide.org   
<email@example.com>

___\* You can indicate the URL or email as [Inline code][u1] by enclosing it in backticks ( ` ). If you don't want a URL to be linked automatically.___

[u1]: <#inline-code>

```markdown
https://www.markdownguide.org   
`https://www.markdownguide.org`
```

https://www.markdownguide.org   
`https://www.markdownguide.org`


<br>

Images
------

------

The syntax for adding images is very similar to the link syntax, just add a sign (!) at the beginning.

- An Image is made up of an ___Alternative text___ (Text to display in case the image fails to render.) enclosed in square brackets and the ___image URL___ enclosed in parentheses.
- __Optionally__, you can add a ___Title___ by enclosing in (" ") and placing it right next to the URL. This is displayed when the mouse hovers over the image.

```markdown
![My alternative text](broken_url "Markdown icon!")

![My alternative text](https://icon-library.com/images/markdown-icon/markdown-icon-4.jpg "Markdown icon!")
```

![My alternative text](broken_url "Markdown icon!")

![My alternative text](https://icon-library.com/images/markdown-icon/markdown-icon-4.jpg "Markdown icon!")

### Linked images:

To add a link to an image, __enclose the image syntax__ within brackets, and then add the __URL__ within parentheses.

```markdown
[![My alternative text](https://icon-library.com/images/markdown-icon/markdown-icon-4.jpg "Image title")](https://icon-library.com/images/markdown-icon/markdown-icon-4.jpg)

```

[![My alternative text](https://icon-library.com/images/markdown-icon/markdown-icon-4.jpg "Image title")](https://icon-library.com/images/markdown-icon/markdown-icon-4.jpg)

<br>

Code
----

----

We can create ___inline code___ or ___code blocks___.
<br>

### __Inline code:__

Enclose the phrase or code in __backticks (\`)__. If the code includes one or more backticks, use __double backticks (\``)__.

```markdown
This is a text that has a `<code>`.  
This is a text that has `` a `<code>` with backticks inside``.
```

This is a text that has a `<code>`.  
This is a text that has `` a `<code>` with backticks inside``.

<br>

### __Code blocks:__

When we have __more than one line of code__, we use __code blocks__, There are _two options_ to create a code block:


1. __Indenting:__ Indent all the lines of code.
2. __Fenced:__ Depending on your Markdown processor or editor, add ___three backticks (\```)___ or ___three tildes (\~~~)___ on the __lines before and after__ the code block. __Optionally__, you can also add ___syntax highlighting___, specifying a _language next to the backticks_ before the fenced code block.

```` markdown
``` 
<code>
    <span>code block</span>
</code>
```

``` html
<code>
    <span>fenced code block</span>
</code>
```
````

``` 
<code>
    <span>code block</span>
</code>
```

``` html
<code>
    <span>fenced code block</span>
</code>
```

<br>

Tables
------

------

To create a table, in the __first step__ is _mandatory_ to define the _table header_, whose syntax consists of _two lines_:
- On the __first line__, you must place the _column headers_, separated by a vertical pipe ( \| ).
- On the __second line__, you must place _three or more hyphens under each column header__ and separate each group of hyphens with a pipe ( \| ).

The ___second step___ is to create each of the rows, where the content of each of the columns is separated by a pipe. You can add links, inline code (not code blocks), and emphasis.

\* ___You must put a pipe ( \| ) at the beginning and end of each of the lines of the table.___

```
| column header 1   | Column header 2|
|-------------------|----------------|
| _row 1.1_         | ___row 1.2___  |  
| [row 2.1](#tables)| `row 2.2`      |

|column header 1|Column header 2|
|-----|---|
|_row 1.1_|___row 1.2___|  
|[row 2.1](#tables)|`row 2.2`|
```

| column header 1   | Column header 2|
|-------------------|----------------|
| _row 1.1_         | ___row 1.2___  |  
| [row 2.1](#tables)| `row 2.2`      |

|column header 1|Column header 2|
|-----|---|
|_row 1.1_|___row 1.2___|  
|[row 2.1](#tables)|`row 2.2`|

### __Alignment:__
You can align the content of each of the columns to the left, right, or center by adding a colon ( : ) to the left, right, or on both side of the hyphens within the second line of the table header.

```
|left alignment     |Center alignment |right alignment |
|:------------------|:---------------:|---------------:|
| _row 1.1_         | ___row 1.2___   | row 1.3        |   
| [row 2.1](#tables)| `row 2.2`       | row 2.3        |
```

|left alignment     |Center alignment |right alignment |
|:------------------|:---------------:|---------------:|
| _row 1.1_         | ___row 1.2___   | row 1.3        |   
| [row 2.1](#tables)| `row 2.2`       | row 2.3        |

<br>

Horizontal Rules
-----------------

-----------------

On a line, add only __three or more__ asterisks (***), hyphens (---), or underscores (___). Add a blank line before and after a horizontal rule.

```markdown

---

******
__________

```

---

******
__________

<br>

Additional syntax
=================

You can use additional syntax if your Markdown editor or processor supports it, such as [GitHub][g1].

[g1]: <https://github.com/> (GitHub)

<br>

Strikethrough
-------------

-------------

You can strike through multiple words by enclosing them in __two tilde symbols (~~)__ to indicate that _these words are in error or should be removed from the document_.

```markdown
these ~~words should be removed~~ from the document
```

these ~~words should be removed~~ from the document

<br>

Task Lists
----------

----------

You can create a task list with checkboxes you have to define _three parts separated by a space_:

1. __A hyphen__ (Indicates the beginning of a list item).
2. __The checkbox__ that is created with a pair of brackets that enclose an `x` if ___it is selected___ or a `space` if ___it is not___.
3. The __list item__.

```markdown
- [x] item selected
- [ ] item not selected
- [x] item selected
```

- [x] item selected
- [ ] item not selected
- [x] item selected

<br>

Emojis
------

------

You can add emojis by copying them from a source like [Emojipedia][Em1] and pasting them into the Markdown text, or you can also use [Emoji Shortcodes][Em2] which enclose the names of the emojis (spaces are replaced by an underscore) in ( : ).

[Em1]: <https://emojipedia.org/> (Banco de emojis)
[Em2]: <https://gist.github.com/rxaviers/7360908> (Banco de emoji shortcodes)

```markdown
this is an emoji copied 😉  
this is an emogi shortcode :wink:
```

this is an emoji copied 😉  
this is an emogi shortcode :wink:

-----------------------------------------------------------------
-----------------------------------------------------------------
-----------------------------------------------------------------