---
layout: post
title:  "Linking to line(s) in Github"
date:   2015-11-07 07:56:00 -0500
categories: Github
---

What I've learned about linking to lines on Github.

- Github allows you to link to the location of a specific line of code (which will also be highlighted) by clicking on the **line number** on the lefthand side. When you click on the line it will add `#L<line number>` to the end of the URL. Remember to click on the line number, not anywhere on the line.

- If you wish to select multiple lines you can hold shift while clicking another line number to highlight a block of code. The end of your URL will now read `#L<first line number>-<second line number>`.

- When linking a line you should never be on the master version of your file as that may change and the line reference will become obsolete. To solve this issue you can press `y` and the URL of the page will change to reference that specific version.

    As an example, the master URL will look something like:
    <https://github.com/taylorpeat/tl-blackjack-webapp/blob/master/main.rb>

    After pressing `y` it will change to refer to a specific version:
    <https://github.com/taylorpeat/tl-blackjack-webapp/blob/3794e1c5355bea55081b5482746af2812cf9549a/main.rb>

    After pressing `y` and selecting a block of code (lines 15 to 20 in this case):
    <https://github.com/taylorpeat/tl-blackjack-webapp/blob/3794e1c5355bea55081b5482746af2812cf9549a/main.rb#L15-L20>


- Another wrinkle is that you cannot link multiple lines if you are viewing a specific commit (showing the deletions and additions). In this case you can still link to a single line which will be highlighted. This will add `L<line_number>` to the end of the URL, no hash symbol. To view the "blob" (single version) instead of the "commit" (comparison of deletions and additions) click the 'View' button at the top right corner of the code.
