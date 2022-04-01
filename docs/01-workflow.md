# Advanced workflows and tools {#intro}

::: { .alert .alert-warning}
Hi there, this course is still under
construction, so everything is subject
to change and there are no videos, yet.
:::

## Preamble: Sharpening the axe

There is this great quote attributed to Abraham Lincoln:

> *"Give me six hours to chop down a tree and I will spend the first four sharpening the axe."* --- Abraham Lincoln

And while I did not verify that he actually said that, the message really resonates with me.
To me, are actually two parts to this.
The first part is the more obvious one.
If you really know your tools well and take care of them, you save time in the long run.
Chopping down a tree is simply faster with a well-sharpened axe, even with the initial time lost to sharpening taken into account.
There is even an xkcd comic you can uses as a table to evaluate if you save more time on a task in the long run by automating it depending on how long it takes to build the automation:

![Source: <https://xkcd.com/1205/>](https://imgs.xkcd.com/comics/is_it_worth_the_time.png)

The same can be applied to learning a tool or mastering a skill.
But only looking at tips and tricks and tool mastery in terms of the time saved leaves out the most important aspect!
I argue that most often, even though mastery of a certain tool might not save you any time in the long run, there is still a huge benefit to it.

This benefit has to do with cognition, the way our brains work.
As it stands, our working memory is tiny.
I mean really, really tiny.
The number 7 is often floated around as a ballpark for the number of chunks we can actively hold in memory to work with at the same time [@MagicalNumberSevena] and it seems to be largely correct.
How then can we think more complex thoughts, you might ask?
Surely even the sentence before this one had more than seven words, let alone individual characters!
The trick lies in chunking and encoding information in such a way that multiple individual pieces of information are stored as just one chunk.
When you read a word you already know, you don't have to actively think about individual letters anymore, you can rely on your long term memory to store a reference to that word, or even the concept that the word entails.
The more you know about something the more you can rely on that.
This frees up your mind to think about other things or the bigger picture.

To come back to the tree-chopping-analogy:

> If you practice chopping a tree such that you don't have to think about individual motions anymore, and your axe is so sharp that you can cut down a tree in a single swing, then your mind will be free to think about the entire forest.

And the same goes for learning your tools for data analysis as well.
If you practice these skills and master theses tools, I guarantee that you are going to have ideas and insights you are only able to find because the details are muscle memory.
So without further ado, here are my top recommendations for mastery:

## Tools and mastery

### Touch typing

Of all of theses this is the single most versatile and useful skill.
Since the keyboard is -- and will be for the foreseeable future -- the primary input method for interacting with a computer in a fast and efficient way, mastering your keyboard will go a long way.
This will not only help you in writing code and talking to R more fluently, it will also help you bring your thoughts to the screen faster.
Think about the possibilities of typing near the speed of thought!
Here are two websites for deliberately practicing touch typing:

-   <https://www.keybr.com/>
-   <https://monkeytype.com/>

I recommend to start with keybr to practice individual motions and combinations and move to monkeytype later when you want to work on real words.

### Your text editor and ide

In our case, this is of course RStudio, the IDE for R (Integrated Development Environment).

<!-- TODO -->

### Your operating system

<!-- TODO -->

## A personal note

Of course, there is such a thing as too much optimization.
I myself am prone to sharpening the axe so much that I eventually forget to actually do some chopping.
In fact, this is part of why I am so excited to teach these courses.
Because I spend so much time learning the intricacies of the tools I am using and the mental models required to teach them,

<!-- todo -->

## Goals for today

-   learn to fully utilize this course material
-   engage with the R community
-   find resources and help faster
-   improve your workflow

## Keep track of your code: version management with git

## Share code and help others on github

## Re-use functions with a personal package

-   write a personal package that contains a custom `ggplot2` theme
-   publish your package on GitHub

## Install packages from different sources: cran, github and bioconductor

-   `remotes`/`devtools`
-   `renv`

## Get help faster with reproducible examples: `reprex`

## Resources

-   <https://git-scm.com/>
-   <https://github.com/hits-mbm-dev/git-intro>
-   <https://r-pkgs.org/>
-   <https://reprex.tidyverse.org/>

## Exercises

### Make it your own!

In the [introductory course](https://jmbuhr.de/dataintro) last semester we talked about different ways of expressing the spread measurements around their mean.
In the process we found that while there is a function in R for the standard deviation (`sd`), there is no such built-in function for the standard error of the mean.
So we wrote our own tiny function called `sem`, which calculates just that.
But if would be annoying if we had to put this function in every one of our analysis scripts!

Write a small package, which exports the `sem` function and publish it on GitHub.
Make sure that you are able to install your very own package from there as well.
As your exercise submission for this week, simply send me a link to your repository.
Remember to ask questions in our discord server if you get stuck!

**Bonus Tasks**:

- Write documentation for your `sem` function with `roxygen` and experience the joy of seeing your very own words on a help page.
- Extend your package with a custom ggplot theme function.

