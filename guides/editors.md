---
title: Plain Text and Text Editors
layout: default
parent: Home
nav_exclude: true
---

# Of Text Editors and Plain Text #

If you are going to work at all with texts beyond as they appear on the printed page or the screen, then you are going to have to come to grips with just what books and ebooks and web pages and other forms of transmitting texts are. 

## Choosing a Text Editor ##

My very best advice is that you find the editor that works best for you first, without regard to price. Most of these applications are modestly priced and finding the right one for you means not only you enjoying your work more -- after all, an application is part of your environment -- but also finding an application with which you will grow. E.g., many of my editor's shortcuts are now part of my muscle memory.

For Macs, I mostly recommend Microsoft’s Visual Studio Code (community edition) because it is free and much of it is open source and there is a large community building all kinds of functionality and features for it. The same is probably true for Windows, though I should note that [NotePad++](http://notepad- plus.sourceforge.net/uk/site.htm), is a perennial favorite is also free and open source. I am less familiar with the Linux world of GUI text editors. My guess is that if you are using Linux, then you already have a beloved plain text editor (and it could very well be Emacs of vi). 

No matter what the operating system, there are lots of editors at all kinds of price points from which to choose. Look around. Try a few. I can't emphasize enough the power of a good editor. So choose one that works for you: it doesn’t have to be loved by anyone else but you. 

Finally, for those of you using either a Mac or Linux machine, don't forget that you always have `vi`. The coder's mantra is that you should [learn how to use the command line editor](http://lifehacker.com/274155/learn-to-use-vi).


## Living with/in a Text Editor

It may surprise you to learn that your new best friend is capable of a great deal more than simply editing HTML, CSS, or plain text files. It is a quite capable platform for a wide variety of document production, *and* it is, for some, a way of life. Here are a few fun things to consider:

* For some, the answer to everything is a BATF. ([See Giles Turnbull's "Living in Text Files."](http://www.oreillynet.com/mac/blog/2005/08/living_in_text_files.html))
* Cory Doctorow -- and you should know who Doctorow is (Google him right now if you don't -- go ahead, I'll wait) -- posted Danny O'Brien's [lovely text file](http://www.craphound.com/lifehacks2.txt) that compiles his notes on, well, text files.
* Both Turnbull and Doctorow mention something called a `todo.txt`. There is quite a cult gathered around `todo.txt` -- indeed as there is around any organizational tool -- and someone has even written a [CLI tool](http://todotxt.com/) to interact with your todo.txt file.


### An Assignment I Sometimes Give

One of the ways to demonstrate the power of text files is to see it in action.
I am going to ask you to free write this afternoon in a text file. Somewhere
along the way, I am also going to ask you to:

  * Go to the [Markdown project page](http://daringfireball.net/projects/markdown/) and download the script.
  * Unzip the file if you need to, and then copy or move the file to this location: ~/Library/Application Support/TextWrangler/Unix Support/Unix Filters. Quit TextWrangler and then re-start it. If you click on the hash-bang menu, you should now see Markdown.pl as an option. Select some text in your document -- or all the text in your document -- and try it out.




## MarkDown Formatting ##

### Introduction

Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML) -- or even to RTF, thanks to a number of available conversion utilities. The idea is that a Markdown-formatted document should be publishable as-is, as plain text, without looking like it’s been marked up with tags or formatting instructions. Why you would want to work in plain text is for another discussion.


## Paragraphs and Line Breaks

A paragraph is simply one or more consecutive lines of text, separated by one or more blank lines. (A blank line is any line that looks like a blank line — a line containing nothing but spaces or tabs is considered blank.) Normal paragraphs should not be indented with spaces or tabs. This paragraph looks like this in plain text:

    A paragraph is simply one or more consecutive lines of text, separated by one or more blank 
    lines. (A blank line is any line that looks like a blank line — a line containing nothing but spaces 
    or tabs is considered blank.) Normal paragraphs should not be indented with spaces or tabs.

When you do want to insert a ``<br />`` break tag using Markdown -- if you are, for example, quoting lines of poetry (say, a song), you end a line with two or more spaces, then type return. You can't see the spaces in the example below, but they are there:

Good-bye, chère vieille Mom,  
Good-bye, pauvre vieux Pop,  
Good-bye, à mes frères, et mes chères petites soeurs,  
Moi, j'ai été condamné  
Pour la balance de ma vie,  
Dans les barres de la prison.  


## Headers

Markdown supports two styles of headers, Setext and atx. We are going to use atx-style headers, which use 1-6 hash characters at the start of the line, corresponding to header levels 1-6. For example:

``# This is an H1`` and it looks like this as HTML:

# This is an H1

``## This is an H2`` and it looks like this as HTML:

## This is an H2

The hash marks after a heading are not required by the way, so either ``### H3`` or ``### H3 ###`` will get you a level three heading like this:

### Third-Level Heading ###

Thus closing the atx-style headers is optional and it doesn't matter that the number of hashes after the heading are the same: only the front ones matter.


## Blockquotes

Markdown uses email-style ">" characters for blockquoting. If you’re familiar with quoting passages of text in an email message, then you know how to create a blockquote in Markdown.

Markdown allows you to be lazy and only put the > before the first line of a hard-wrapped paragraph:

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

Here's what it looked like before Markdown worked its magic:

``> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.``


## Lists

Markdown supports ordered (numbered) and unordered (bulleted) lists. Unordered lists use asterisks, pluses, and hyphens — interchangably — as list markers:

    *   Red
    *   Green
    *   Blue

becomes:

*   Red
*   Green
*   Blue

Ordered lists use numbers followed by periods:

    1.  Bird
    2.  McHale
    3.  Parish


## Links

Markdown supports two style of links: inline and reference. In both styles, the link text is delimited by [square brackets]. We are going to use the reference-style links in this project. Reference-style links use a second set of square brackets, inside which you place a label of your choosing to identify the link:

    This is [an example][id] reference-style link.

You can optionally use a space to separate the sets of brackets:

    This is [an example] [id] reference-style link.

Then, anywhere in the document, you define your link label like this, on a line by itself:

    [id]: http://example.com  "Optional Title Here"

You can put the title attribute on the next line and use extra spaces or tabs for padding, which tends to look better with longer URLs:

The implicit link name shortcut allows you to omit the name of the link, in which case the link text itself is used as the name. Just use an empty set of square brackets — e.g., to link the word “Google” to the google.com web site, you could simply write:

    [Google][]

And then define the link:

    [Google]: http://google.com/

Please note that the name of a link can have more than word within it. So `[crawfish boil][]` is a perfectly acceptable link.

This particular way of "marking up" links is useful here because as you generate links you are in fact also generating a list at the bottom of entry. As we read through each other's entries, we will be able to compile all these links into a master listing of further entries in need of composing.


## Emphasis

Markdown treats asterisks (*) and underscores (_) as indicators of emphasis. The `<em>` tag in HTML is typically rendered as italics. MarkDown treats double asterisks or underscores as strong emphasis; `<strong>` usually results in bold. We will have cause to use emphasis, to mark the titles of works, if any, but in all likelihood bolded items, such as glossary terms, will be linked and thus already marked.


## Code Spans and Code  Blocks

Finally, for the ``l33t`` among you, you can, as I have done here, have spans of code within a paragraph or as separate blocks. Code spans are delimited by  back-ticks at their beginning and end. Code blocks are formatted with at least four spaces or one tab at the beginning of each line and the use of a colon at the end of the preceding paragraph.

## Further Information

If you want to learn more about Markdown, feel free to google it and/or to check out its home website -- you can find it, I trust. It has been remarkably well-received as a standard and its use is rather wide-spread among the technorati, and since we all aspire to be technorati, you've taken another step along that path.
