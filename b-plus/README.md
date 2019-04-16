# OOPS.. You've got yourself a better Raspberry Pi! It's B+!

It happens to be, that fellows from Raspberry managed to update their Raspberry Pi 3B controller up to Model B+ and we somehow missed it. It means that our book — the one you've found in the box, is somewhat obsolete.

Sorry for that.   
:flushed:

But it's no big deal!    
This patch is made precisely to fix this.   
Here you can find up to date instructions to all chapters which have to be modified.

Check up the list of the pages where the difference between models 3B and 3B+ appears.   
When you get to the listed page in the book, just look up this instruction to fix your code.

Let's get to it.

## Page 4. RASPBERRY PI
Obviuosly, Raspberry Pi 3B+ looks different:

![Image](/b-plus/images/b+_sketch.png)

## Page 7.
Shift+alt no longer switches the language. Pity.

## Page 8. WI-FI
Nothing wrong with this one.    
Just it says that it is possible to set up Wi-Fi via SSH and doesn't say how.   
Actually SSH instruction is there, in the book on page 56. Just FYI.

## Page 25. BLINK
Step 3 instruction tells the way of saving the file using graphical user interface `File -> Save As`.   
![Image](/b-plus/images/p25-1.png)   
But most likely you don't see theese menus in Thonny.   
If this problem appears, follow this sequence:   
![Image](/b-plus/images/p25-2.png)   

## Page 41. LANDING PAGE

















## Page 18. AN INTRODUCTION TO PYTHON
New Raspberry — new Python.    
Python2 still works, but not anywhere.   
Developers all over the world have been updating their programs to Python3 for a while.    
In order to avoid future compability trouble, we also decided to update ourselves to P3.   

In step 2 enter 'python3' command instead of 'python'    
That's it. The rest of the chapter is the same.


Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/nkrkv/raspberry-kit/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
