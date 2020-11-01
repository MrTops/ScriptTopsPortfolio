## Introduction
> Hello,
> 
> I wanted to give you a introduction before I actually get into the projects I've done, mostly for fun, and some as commissions/partnerships.
> I've been coding for 4 years, I started in 5th grade by going to [lua's demo](https://www.lua.org/demo.html) and just toying around with the language.
> Fast-forward 4 years and I've mastered Lua, Python 3, and Node JS, and learned the basics of Web Languages, C#, and Java.
> I've worked with many studios, and while not all of these partnerships resulted in a final product I learned a lot from each.
> 
> \- ScriptTops, Programmer

Discord: DevTops#9999
Twitter: [here](https://twitter.com/dev_tops)

# Projects

This is a list of projects that I've worked on in a all the coding languages I know, some are finished, some are not, but all of them made me learn.

## Free-Rice-Hack
**DOM Javascript**

I got the idea for this in school, it took 15 minutes but was the first time I tried to exploit a website.

Code!
```js
let getCard = () => {
    try {
        let solution = eval(document.getElementsByClassName("card-title")[0].innerHTML.replace("x", "*").split("=")[0]);
        let cards = document.getElementsByClassName("card-button");
        if (cards[0].innerHTML == solution) cards[0].click();
        else if (cards[1].innerHTML == solution) cards[1].click();
        else if (cards[2].innerHTML == solution) cards[2].click();
        else if (cards[3].innerHTML == solution) cards[3].click();
        else cards[0].click();
    }
    catch {
        try {
            document.getElementsByClassName("card-button")[0].click();
        }
        catch {
            alert("FATAL ERROR");
        }
    }
};
setInterval(getCard, 1000);
```

[It working!](https://i.gyazo.com/18adf1bdbc4b955dd57e2f67cbfb9877.mp4)

## Spelunkr
**Python 3**

Spelunking was a overly complicated mod, it was my first time making a program with native modding support plus exporting to .exe
This basic sounding game took a lot of my sanity but I liked the beta I got, however I cancelled the project for various reasons.
I was going to make this into a actual game using unity but this fell through aswell.

I don't have any gifs of it, but you can see the code [here](https://github.com/MrTops/Spelunkr)

## Buck Bot
**Node.JS**

Buck Bot was a small side project I was working on for about 3 days while I didn't have any work to do.
Buck Bot is a discord.js discord bot that was going to be a economy bot.

[Code](https://github.com/MrTops/BuckBotCode)
I don't have any gif of it, but if you want to join the server it's there and I can run the bot for you.

## Mang
**Python 3**

Mang was my only time trying to make a coding language, the syntax was super lax and was easy to pick up, the github has the language it's self and examples.
There isn't much about Mang but the code is bad and doesn't represent my current skills, but I felt it's a cool thing I did.

[Code](https://github.com/MrTops/Mang)
