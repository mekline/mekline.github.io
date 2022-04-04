---
layout: single
title:  "*It's a text file!"
date:   2022-04-04 17:40:44 -0400
---

Time to explain the title of my website: "It's a text file, and other secrets". 

Often, there are tiny pieces of knowledge that nobody thinks to tell you, but which are vital for getting off the ground when learning something technical. 

If you get stuck on one of these barriers, or if you're trying to learn something technical and feeling like you understand the basic concepts but not how to actually, literally, get started on your own laptop today, it's not your fault! These are things people forget to teach, because they seem "obvious." 

I wrote a twitter thread ages ago about having this experience in my very first computer science course as a freshman: 

[My strongest memory of learning to code is sitting thru my very first lecture silently panicking because while the FOR loop concept made perfect sense, I had no idea what I was supposed to do with it. I knew 'type it into Word' was wrong, but didn't know how to ask the question in a way that didn't make me sound stupid in front of my class.](https://twitter.com/melissaekline/status/1064913255498477569)

The answer to my question would have been: Open a text editor, and save the command as a text file. 

So: most files that you use when programming are text files. Unlike the files that store photos and Microsoft Office products, text files are designed to do just one thing: store a series of (basically) alphanumeric characters, spacing, and punctuation in a way that (a) a computer can interpret and (b) a person can (hypothetically) read and edit.

Many programs you've used on your computer (e.g. Word) open a specific kind of file. Underneath the hood, if you dig far enough down, it's more or less just very specifically structured text, which MS Office is able to interpret as a document with fonts, colors, paragraphs, etc. 

If you've ever opened a Word document and seen dozens of pages of weird wingdings and boxes, you are seeing a glitch where some of this text is trying and failing to come through. Files like these tend to be large, and the sense in which a human could read the underlying text is very, very, very hypothetical.

Fortunately, most of the scripts[1] you'll want to work with as a scientist will use text files which are MUCH simpler. They often have their own file extensions[2] which tell you what specific programming languages are involved, but you can also open *any of the following files* in Notepad (Microsoft) or TextEdit (Mac):

* `myfile.py`
* `myfile.html`
* `myfile.R`
* `myfile.Rmd`
* `myfile.txt`
* `myfile.md`
* `myfile.markdown`
* `myfile.json`

If you double-click on any of these, your computer may be set up to launch a specific program (like RStudio, for *.R and *.Rmd)...but it's all just text files! You could edit them, save the result with your text editor, and if there aren't any new syntax mistakes, the file will still run in whatever context it was designed to.

The internet is also mostly text files. Your browser probably has a function called "View Source" - this will often let you look at the `something.html` file that produces much of the website you see.

As a final note, you can keep on using the text editor that comes with your machine, but if you want to look like a cool hacker (and also get access to what amounts to spellcheck for your code), there is a vast world of source code editors, sometimes called [IDEs](https://en.wikipedia.org/wiki/Integrated_development_environment).  I like [SublimeText](https://www.sublimetext.com/) and [VSCode](https://code.visualstudio.com/), both of which are free to use.

---

[1] Except not matlab, or other proprietary formats. [This link](https://people.math.sc.edu/Burkardt/data/mat/lena.mat) will download an arbitrary `*.mat` file, and if you try to open that with TextEdit, you will see hot garbled nonsense. Unless you purchase a copy of Matlab software, you don't get to see the commands that you write which make up a Matlab script. Bummer!

[2] File extensions are also just text. *They really are just the characters* `.xxx` at the end of a file name, just like the letters before the dot are `myfile` or what have you.  By convention, operating systems and the people who write them follow the convention that whatever comes after the last `.` in a filename is reserved for telling the computer what kind of file it is and what kinds of programs might be able to open it.