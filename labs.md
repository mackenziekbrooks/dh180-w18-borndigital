# Labs

## Lab 1 // Environment setup // January 9

### Box
Did you know that W&L offers unlimited cloud storage while you're a student? We will use http://box.wlu.edu/ for assignment delivery and other course materials. Please take some time to familiarize yourself with the platform.

The easiest way to use Box is to download Box Drive. This makes your Box folders act like another folder on your computer. Download here: https://www.box.com/resources/downloads/drive

### Text editors
Microsoft Word or Google Drive are great apps for writing papers. They make it easy to style and present a document. However, to work with text in a programmatic way, or to write code, we need a different app. MS Word adds a lot of hidden styling and other baggage that we don't need. One of the best features of text editors is that they can detect what language you're writing in and highlight the elements in different colors.

There are a lot of [options](http://lifehacker.com/five-best-text-editors-1564907215) for text editors. You're welcome to try on a few before choosing. I use [Atom](http://atom.io/) and [Sublime Text](https://www.sublimetext.com/), so I recommend you install it for consistency.

### Hypothes.is
[Hypothes.is](https://hypothes.is/) is a new framework for open annotation of the web. It operates via a Chrome extension allowing you to make private and public comments on websites. I have set up a private group for our course as there will be some readings that we annotate as a group.

### Zotero
[Zotero](https://www.zotero.org/) is a citation manager. It operates via a browser plugin so you can capture citation information directly from the web. There is also a standalone desktop app ([and text mining possibilities!](http://papermachines.org/)) as well. There's even a plug-in for MS Word that will automatically generate your bibliography.

### Lab Report
I'll verify the completion 

## Lab 2 // HTML + CSS // January 9
For these exercises, you will need to a text editor and a brower other than Safari. 

### HTML
HTML, or Hypertext Markup Language, is one of the basic building blocks of the web. HTML is a set of tags that add structure to documents. When you write a document, you rely on style to indicate something about the text. You might put the title in a bigger font or break up paragraphs with tabs or new lines. Markup languages do this by adding tags around the content you wish to set apart. For example: ```<title>The Lord of the Rings</title>``` or ```<p>This is a whole paragraph.</p>``` Your human eyes and brain can infer things based on visual appear that computers need to be told explicitly. That's why we need semantic markup.

Documentation for HTML lives [here at the W3 Schools](http://www.w3schools.com/html/).

1. Open your favorite text editor and using the W3 Schools as a guide, write your own HTML document.
2. Save the file as index.html in your Box folder in a separate folder titled: Lab2. 
3. To view your page in the browswer, open index.html in your browser, usually with the key commands Ctrl + o
4. You should include the basic set of tags: <html> <head> <title> <body>
5. Add five additional types of tags to the body of your HTML document, including a table.
6. Add an additional HTML page and link the two pages.


### CSS 
Our next building block of the web is CSS, or Cascading Style Sheets. HTML structures your webpage, but you need something else to add the pretty colors and images. CSS has a different syntax than HTML. First you identify the HTML tag, then you declare the styles you wish to apply. ```title {color: red;}```

See some basic CSS at the [W3 Schools CSS tutorial](http://www.w3schools.com/css/default.asp).

1. Create a separate CSS document and save it as style.css in the same folder you created for the HTML activity.
2. Link the style.css file to your HTML document. Consult the W3 Schools to figure out how to do this.
3. Add a background color.
4. Change the border on your table.
5. Add style to your links when you hover over them.

### Lab Report
All your HTML and CSS documents should be saved to Box by class time on Thursday the 11th. 

## Lab 3: Command line 
Most of us interact with our computers or phones through highly visual interfaces. We know what button to press because of the stylized image representing it. We understand what it means when a website has a blue "f" or when a friend sends a thumbs-up emoji. Your computer, regardless of operating system, wants to interact with you via visual cues. We call these Graphical User Interfaces aka GUI (pronounced gooey).

But there's another way. You can interact with your computer entirely via text commands through something called a Command Line Interface or CLI. When you see a hacker typing green text into a black box in a movie, they're using the command line. But the command line isn't just for hacking.

**Why then?**
* The command line gives you power. It frees you from a lot of clicking and lets you inhabit a world where your computer does exactly what you say.
* The command line lets you script and automate tasks and processes. It lets you perform the same set of actions on a one file or on many files many times over.
* The command line is often used for installing and running DH tools.
* The command line is a helpful tool for inspecting and altering data.

**How:**

If you're on a Mac, search for an app called Terminal.

If you're on Windows, open cmd.exe or Powershell.

https://xkcd.com/934/

**Learn:**

There are a lot of resources for learning the command line. We'll be using [The Command Line Crash Course](https://learnrubythehardway.org/book/appendixa.html) in this class.

Programming Historian offers [Intro to the Bash Command Line](http://programminghistorian.org/lessons/intro-to-bash) and [Intro to Powershell](http://programminghistorian.org/lessons/intro-to-powershell).

Scholars' Lab has a great [tutorial](http://praxis.scholarslab.org/resources/bash/).

### Lab Report
1. Type ```history``` in the command line. 
2. Copy and paste the results to a text file.
3. Save as lab3.txt in Box.


## Lab 4 
Time to practice writing metadata! I will bring a selection of physical and digital objects for you to describe. 

1. Open this [form](https://docs.google.com/forms/d/e/1FAIpQLSfKjQnI9kcDheU7-d7kDV2Hf_scm6KrUkiNP59ykD8oqlgz_A/viewform?usp=sf_link). 
2. Select an item. When you're finished, move on to another.
3. Work individually to fill out one form entry for each item. You may have to do some research to find out more information. Pay attention to the kinds of searches or words you use and note that in the form.
4. Include your initials to receive credit for this lab.
 
 
 ### Dublin Core 
* Item number - the number I've written on a slip of paper to identify the item.
* Title - A name given to the resource.
* Creator - An entity primarily responsible for making the resource. 
* Subject - The topic of the resource. 
* Description - A summary or accounty of the resource.
* Publisher - entity responsible for making the resource available.
* Contributor - An entity responsible for making contributions to the resource. 
* Date - when the item was created/published
* Type - the nature or genre
* Format - details about the physical/digital format
* Identifier - is there a unique identifier?
* Source - did this resource come from somewhere?
* Language - Primary language of the material.
* Relation - are there related resources?
* Coverage - spatial or temporal
* Rights - Information about rights held in and over the resource, usually copyright.