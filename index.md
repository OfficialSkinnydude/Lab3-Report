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


Another Example of this feature
![Image](http://url/a.png)	

Isn't that better?

# Setting Markers or "Bookmarks"
This feature is very useful since naviagting through big text files can be easy to get lost. One way to help with this was labeling each line. That is a nice solution, but that requires you to manually look at what line you are on and remembering what line you are on. Wouldn't it be nice if there is something that can act like a bookmark and take you there whenever you want and wherever you are at. Well, good news for you, we have something called a marker. the way it works is that you press `m` followed by any letter you want. Lets use `a` as an example. In the bottom left corner, you will see `set mark:` After that, you can scroll down and if you want to go back to the place where you placed your marker, you press `'` + `[letter chosen]`. When you press `'`, at the bottom left corner, there will be an output saying `goto mark:`.

**Setting the mark**

![Image](http://url/a.png)	


**Going to the mark**

![Image](http://url/a.png)	

# Showing Information About The File.
Finally, to show important information about the file, we can press `g` + `ctrl g` and we will get an output which shows file name, byte postion, lines you are on, total lines, and the percentage on the file you are on. For example, in the article we were on earlier, if we do this command, we will get an output saying `rr74.txt lines 1-36/426 byte 1971/22290 9%  (press RETURN)`. As you can see, it shows the information I mentioned. This is useful to know where you are at in the file. 

![Image](http://url/a.png)


**Same Command in Different File and Position**

![Image](http://url/a.png)

# Conclusion
The command less is a really helpful command. You are able to output the contents without actually opening the file. Navigating through the files with the commands that less has is really useful. So next time you have to access multiple files, use less for a easier, faster, and better experience. 

