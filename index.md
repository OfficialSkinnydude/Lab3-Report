# Exploring the Command Less

## What is the Command Less?

The command less puts the file's contents without opening the file on a text editor. What it does instead is it displays the text on the terminal for easy access.
his can be very useful when you have multiple files and just want to peek a file to see if it is the one you are looking. The command sounds very simple but it has a lot more to offer.
Navigating with the command less has useful features like looking for a specific word or setting "bookmarks". Fun fact, the name less comes from "less is more".

# Navigating Through Text Using less

To start with, to use less, you use the order `less [Option] filename`. This is the syntax. After you press enter, you will be displayed the contents of the file. 
To provide examples, I will be using the `technical` directory and open some text files. In my terminal I will type `less rr74.txt`. The output is a really long article so I 
will provide of picture of what is shown. 
![Image](http://url/a.png)	


As you can see, I get the article shown to me. Now this is where it gets cool interesting. There are a couple comands to navigate through the terminal. One pressing `Space` or `f` will scroll to the next page of the article. Really what it does is it skips through chunks of text, making it seem like you scrolled to the next page. To scroll to the previous page, press `b`. To find a specific word or pattern, you press `/` followed by the word you are looking for. For example, in this file, I want to look for the word "animal". To do this, i type `/ animal`. The output is the word you looked for being highlighted through the text. By pressing `/` + `<enter>` , it will scroll through all the findings of the word you chose to look for. Think of it as the `ctrl f` of the terminal. 
![Image](http://url/a.png)

Finally, to quit less you simply press `q`.

# Labeling each line
Using less on really large files can be overwhelming because for big articles like the one used earlier, it can be easy to get lost and sometimes you need a reference point. This is where `less -N filename` comes in. This will label each line. This is useful so you do not get lost.

![Image](http://url/a.png)	

Isn't that better?

# Setting Markers or "Bookmarks"
This feature is 
