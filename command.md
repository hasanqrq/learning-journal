# What is a text editor?
** A text editor is a piece of software that you download and install on your computer, or you access online through your web browser, that allows you to write and manage text, especially the text that you write to build a web site. The text editor has to be one of the most important tools you can use as an aspiring web developer **

### the most important features are:
 1.) code completion; 
 2.) syntax highlighting; 
3.) a nice variety of themes (to reduce eye strain and fatigue); and 
4.) the ability to choose from a healthy selection of extensions available when you need them. 
You might find some other features that are must-have’s, but I think these features are a good start.

### Another nice feature is being able to write your HTML and CSS more efficiently. There is a kind of shorthand language called Emmet that can help. Emmet will speed up your code writing faster than you can imagine. Some text editors come with Emmet built right in, or Emmet can be added by the means of an extension.

### Another feature you should definitely look into is called syntax highlighting. Syntax highlighting is a feature that takes the text you type, and makes it more noticeable by colorizing the text. Attributes are a different color than elements. And elements are a different colorthan copy. This makes it so much easier when you’re looking for an error and you can’t find it. As well as making your text easier to read.

# The Command Line!

### The command line is an interesting beast, and if you've not used one before, can be a bit daunting. Don't worry, with a bit of practice you'll soon come to see it as your friend. Don't think of it as leaving the GUI behind so much as adding to it. While you can leave the GUI alltogether, most people open up a command line interface just as another window on their desktop (in fact you can have as many open as you like). This is also to our advantage as we can have several command lines open and doing different tasks in each at the same time. We can also easily jump back to the GUI when it suits us. Experiment until you find the setup that suits you best. As an example I will typically have 3 terminals open: 1 in which I do my working, another to bring up ancilliary data and a final one for viewing Manual pages (more on these later).

### A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.

### The command line typically presents you with a prompt. As you type, it will be displayed after the prompt. Most of the time you will be issuing commands. Here is an example:

#### Line 1 presents us with a prompt ( user@bash ). After that we entered a command ( ls ). Typically a command is always the first thing you type. After that we have what are referred to as command line arguments ( -l /home/ryan ). Important to note, these are separated by spaces (there must be a space between the command and the first command line argument also). The first command line argument ( -l ) is also referred to as an option. Options are typically used to modify the behaviour of the command. Options are usually listed before other arguments and typically start with a dash ( - ).
#### Lines 2 - 5 are output from running the command. Most commands produce output and it will be listed straight under the issuing of the command. Other commands just perform their task and don't display any information unless there was an error.
#### Line 6 presents us with a prompt again. After the command has run and the terminal is ready for you to enter another command the prompt will be displayed. If no prompt is displayed then the command may still be running (you will learn later how to deal with this).Your terminal probably won't have line numbers on it. I have just included them here to make it easier to refer to different parts of the material.

# Basic Navigation!

### The first command we are going to learn is pwd which stands for Print Working Directory.

## Paths

### In the previous commands we started touching on something called a path. I would like to go into more detail on them now as they are important in being proficient with Linux. Whenever we refer to either a file or directory on the command line, we are in fact referring to a path. ie. A path is a means to get to a particular file or directory on the system.

## summary

- pwd
Print Working Directory - ie. Where are we currently.
- ls
List the contents of a directory.
- cd
Change Directories - ie. move to another directory.

## More About Files!

### file : obtain information about what type of file a file or directory is.
### ls -a :List the contents of a directory, including hidden files.

### Importat concepts 

Everything is a file under Linux
Even directories.
Linux is an extensionless system
Files can have any extension they like or none at all.
Linux is case sensitive
Beware of silly typos.