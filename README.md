
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

