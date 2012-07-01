---
layout: post
title: "first post for testing"
date: 2012-07-01 17:39
comments: true
categories: tests
---


A First Level Header
====================

A Second Level Header
---------------------

Now is the time for all good men to come to
the aid of their country. This is just a
regular paragraph.

The quick brown fox jumped over the lazy
dog's back.

### Header 3

> This is a blockquote.
> 
> This is the second paragraph in the blockquote.
>
> ## This is an H2 in a blockquote

Some of these words *are emphasized*.
Some of these words _are emphasized also_.

Use two asterisks for **strong emphasis**.
Or, if you prefer, __use two underscores instead__.

----------------- lists -----------------------

#####Unordered (bulleted) lists use asterisks, pluses, and hyphens (*, +, and -) as list markers. These three markers are interchangable;

this:

*   Candy.
*   Gum.
*   Booze.

this:

+   Candy.
+   Gum.
+   Booze.

and this:

-   Candy.
-   Gum.
-   Booze.


#####Ordered (numbered) lists use regular numbers, followed by periods, as list markers:

1.  Red
2.  Green
3.  Blue


#####If you put blank lines between items, you'll get <p> tags for the list item text. You can create multi-paragraph list items by indenting the paragraphs by 4 spaces or 1 tab:

*   A list item.

    With multiple paragraphs.

*   Another item in the list.


----------------- links -----------------------

Markdown supports two styles for creating links: inline and reference. With both styles, you use square brackets to delimit the text you want to turn into a link.

#####Inline-style links use parentheses immediately after the link text. For example:

This is a [link to weibo](http://weibo.com/).

#####Optionally, you may include a title attribute in the parentheses:

This is a [link to weibo](http://weibo.com/ "Hey, you see, I have a title.").


Reference-style links allow you to refer to your links by names, which you define elsewhere in your document:

#####I get 10 times more traffic from [Google][1] than from [Yahoo][2] or [MSN][3].

[1]: http://google.com/        "Google"
[2]: http://search.yahoo.com/  "Yahoo Search"
[3]: http://search.msn.com/    "MSN Search"


The title attribute is optional. Link names may contain letters, numbers and spaces, but are not case sensitive:

#####I start my morning with a cup of coffee and [The New York Times][NY Times].

[NY Times]: http://www.nytimes.com/


----------------- images -----------------------

Image syntax is very much like link syntax.

#####Inline (titles are optional):

This pic was took at Auto Shanghai 2011, she was so nice smiling to me~ Look at the man behind her......

![alt text](/images/IMGP3544.jpg "This pic was took at Auto Shanghai 2011")

#####reference-style:

![alt text][id]

[id]: /images/IMGP3544.jpg "Title"


----------------- code -----------------------

#####In a regular paragraph, you can create code span by wrapping text in backtick quotes. Any ampersands (&) and angle brackets (< or >) will automatically be translated into HTML entities. This makes it easy to use Markdown to write about HTML example code:

I strongly recommend against using any `<blink>` tags.

I wish SmartyPants used named entities like `&mdash;`
instead of decimal-encoded entites like `&#8212;`.




#####If you want your page to validate under XHTML 1.0 Strict, you've got to put paragraph tags in your blockquotes:

<blockquote>
	<p>For example.</p>
</blockquote>





