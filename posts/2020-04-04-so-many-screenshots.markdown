---
title: So Many Screenshots
summary: In which I wrangle my many video game memories
categories:
  - tech
---

<img src="/images/posts/animal-crossing.jpg" width="800" height="450" alt="A screenshot from Animal Crossing, where my character is talking to Flick the bug enthusiast.">

I love video game screenshots. Like, a _lot_. At the time of writing, I've collected over 40,000.

I don't have a problem, you have a problem.

These days I'm only playing games on the PS4 or the Switch - I don't have the time or the space for a dedicated 486DX with fancy CGA graphics, or whatever. You may not know this, or care, but grabbing screenshots from consoles is kind of a pain in the ass. The PS4 lets you copy directly to a USB drive and transfer them to your computer that way, which is easy enough. The Switch can store screenshots on a microSD card, which you can only remove once you've turned off the console, flipped open the kick stand (which is almost impossible) and popped out the card. You _could_ post your screenshots to Twitter or Facebook and grab them that way, but who hates themselves that much? Not this idiot.

While I was still in macOS, I'd use [a tiny Ruby gem](https://github.com/waferbaby/parker "My gem for organising screenshots.") I'd written specifically for this (of _course_ I did) to walk through the screenshots, clean up the file names and copy them across them into folders based on the platform and game.

Of course, now that [I'm exclusively on the iPad](/archives/2020/02/04/magic-space-glass/ "My post about switching to the iPad.") (I gave my wife the laptop, so there's no going back) I needed to work out an alternative, and I'd _hoped_ to use Shortcuts but it fell short once again - you just can't get a list of files inside a folder. Why would anyone need _that_?

Thankfully, the oh-so-very excellent [Scriptable](https://scriptable.app/ "An iOS automation app.") came to the rescue, which is just weird because I'm solving my problems with JavaScript, and I thought JavaScript only _caused_ problems (angry frontend developers, my email address is on the about page.) I'm kidding! Mostly kidding!

For the USB drive full of PS4 images, I have a handy little USB-C to USB-A dongle whatsit. Plug it all in, run the script, and off it goes throwing my neatly organised Destiny 2 screenshots (because, let's be real here) onto iCloud, eventually.

For the Switch, I've got a second script, and... this.

<img src="/images/posts/dongle-hell.jpg" width="800" height="148" alt="My ridiculous dongle setup for syncing Switch screenshots.">

This ghastly dongle hellbeast is a microSD card adapter inside a 30-pin SD card reader attached to a 30-pin to Lightning adapter, which plugs into my phone (not the iPad). Why would I put myself through this particular stupidity when I could just buy a USB-C to SD card dongle? Because it works. It's stupid, but it works, like all the good things in life. And it's kind of amusing. Except when the iPhone falls asleep and fails to recognise any of it unless you restart it.

But, y'know. Amusing.