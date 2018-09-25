# Last Week's Accomplishments

Last week I was able to create a floating window where the user can open a Twitch stream and watch it in a pip style window. I was also able to make the window resizable using the keyboard shortcuts 'ctrl +' and 'ctrl -'. The reason why I chose to go with keyboard shortcuts instead of a drag handle is because I wanted to be able to constrain the window to a 16:9 aspect ratio. I tried to do this with a drag handle but I wasn't able to figure it out. From what I found online it seems like window resizing is controlled by the operating system and not the application itself so I don't think there is much I can do here.

I created a [project](https://github.com/fcusano9/FloatingTwitch/projects/1) on github and filled it with issues and features that I plan on implementing throughout the semester.

I also wrote an initial blog post [here](https://rcos.io/projects/fcusano9/floatingtwitch/blog) on observatory that goes into more detail about my project and what I have accomplished so far. From now on all updates will be in this github repository.

# This Week's Plan

This week I plan on implementing the [always-on-top](https://github.com/fcusano9/FloatingTwitch/projects/1#card-13107056) feature that will allow the window to remain positioned above all other windows on the screen. I also plan on fixing some other bugs that I have found.

# Anything Blocking?

Right now I am developing FloatingTwitch as a Chrome application but apparently Chrome is disabling Chrome applications for all operating systems except Chrome OS. However, so far I haven't had an issues and my application has been working fine.

I would like to figure out another way to make this app however I don't really know what to do. I need to something that will allow me to create a frameless window which a chrome extension does not allow. I think I will eventually go to other people to see what they suggest.
