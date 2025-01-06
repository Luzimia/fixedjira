**Welcome dear Mojira user!**
*(for people who want to git clone the repo, it's useless, just copy paste the code and read at least until the serious part)*

**Bored of this boring bug of ultimate boredomness?**

I have the cure for this!

*bip boup bip* (typing on my 12 keyboards with epik matrix effects on the screen)

Here you go!

```js
const listeners = getEventListeners(document).keydown; // Take the keydown listeners of <HTML>.
listeners.forEach(listener => { // Will execute this for each listener.
    document.removeEventListener('keydown', listener.listener); // Remove the event so you can finnaly be free from Notepad.exe.
}); 
```

**The legend say that if you can't write some characters in Mojira, you can fix this temporarily by ~~giving me your money~~ copy pasting this code into your web browser's console.**
(if this was useful for you it would be cool to let me know by adding a star for example)

**[SERIOUS PART]**

Compatibility: Blink-based web browsers. (Blink is the rendering engine of Chrome & Chromium, recent Edge is based on Chromium.)
For Firefox users: Sry, i was way too lazy to make a Firefox version, i use Firefox too, but i'm hurt and i'm very tired and busy at this moment, use chatgpt or smth.

**Warning!**

This code wasn't tested on the entire Mojira website and may break some things.
Fortunately, it works fine for me, the only known issue is from the login page, it work for the login page, but after logging in you will need to refresh the page, but it don't do it all the time.
Just, if the page is white or something is broken, reload the page and even clear the cache (with CTRL + F5), my code will be annihilated (not on your system anymore).
Sometimes, Mojira will refresh the page, if the fix don't work after changing page, you can just copy and paste it again.



**What does it do?**

If you are not capt'n obvious, the JS code just make a "listeners" variable getting the keydown events of the <HTML> document, since the issue is caused by an event in the <HTML> document, this code just get into
each listener and remove it.



**Will it make my computer go bye bye?**

No, if the computer is fine and safe from your Bowser *(same for your browser / failed joke attempt)*, you will be fine, except if your computer is programmed to explode like a creeper when some JS is approaching.



**Can i sell the code and make millions of €€€ with it?**

Yes, as long as i get da money and i get credited.



**Do you have any other info about the code?**

Yes, please keep in mind that this code is given to you by me for personnal use on the Mojira website, and that if it break your system using black magic, it's entirely your fault.
But if you want any other info, you can still ask, you can also make a Chrome extension using this code if you credit me (so i can be famous :3).



Please be careful on the internet, and always read the code first, feel free to ask our lord ~~Lord Sugar~~ ChatGPT if you need help to understand this very easy bit of code.

Happy new year and have fun testing Minecraft bugs over and over and over ... and over ...... and over ......... on Mojira until it finally get fixed thank to your contribution and some moderator magical spells!


<sub>*Blablabla this code is under the IDon'tKnowButIt'sMine license,
it can work on Jira too if it have the same issue as Mojira (the Mojang Bug Tracker, you know? for the little game that nobody know named Minecraft),
and if you don't know Lord Sugar is Alan Michael Sugar, the famous guy who made Amstrad, my best friend asked me to put an Amstrad ref here in exchange of a Super Mario clock NDS file he got from his old 3ds,
don't bother questioning me, i'm half awake and don't even know how to use github or the english language properly, have fun reading my ""funny"" readme.md so i can waste your time to compensate the time
you will gain on Mojira using my super 4 """millions""" of lines of code. Au revoir ! ^-^*</sub>
