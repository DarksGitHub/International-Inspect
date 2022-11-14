# International-Inspect

This is a version of the inspect element
that works on all devices, mobile and computer.

# Desktop Or Laptop Setup

Create a new bookmark and set it to the bookmarks bar
If it only shows on the New Tab page like in the image below on the right

![image](https://user-images.githubusercontent.com/108237499/199824930-49d13d1e-f439-4c9c-bad4-edd6c1ce81bd.png)

If you have one like the left side,
Then you will have to follow these steps, If You Have One Like The Right, Scroll Down Till You See "- People With Bookmarks Bar On Read Here"
1. Right Click/RMB/Right Mouse Button, The Bookmarks Bar.

[image](https://user-images.githubusercontent.com/108237499/199825499-16bcd92b-6640-4e39-acad-cbc12a4bcafe.png)

Then Click (Show Bookmarks Bar)

![199825499-16bcd92b-6640-4e39-acad-cbc12a4bcafe](https://user-images.githubusercontent.com/108237499/199825831-2a0a2169-a470-4209-9f87-550dbd763004.png)

Now Bookmarks Bar Shows No Matter What Tab Your on. - People With Bookmarks Bar On Read Here

Now Click The Star On This Site To Make A Bookmark

Rename The Bookmark "Universal Inspect" Without The Quotes.

For The URL Of The Bookmark You Want To Replace It With The Javascript Code Below

```
javascript:(function () {     var script =  document.createElement('script');    script.src="//https://raw.githubusercontent.com/DarksGitHub/International-Inspect/main/InternationalInspect.js";     document.body.appendChild(script);    script.onload = function () {         eruda.init()     } })();
```

Then Press The Save Button.

When You Want To Use It On A Site, Click The Bookmark, Click The Gear That Appears In The Bottom Right Corner. The Setup Is Finished. Mobile Guide Coming Soon

# Mobile Setup (Google Chrome App)
