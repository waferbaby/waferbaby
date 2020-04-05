---
title: Magic Space Glass
summary: In which I move from a MacBook Pro to an iPad.
categories:
- tech
---

I recently picked up an 11 inch [iPad Pro](https://www.apple.com/au/ipad-pro/ "Magic space glass!") and a [Pencil](https://www.apple.com/au/apple-pencil/ "It’s just like a pencil, kinda.") (note the correct capitalisations) with the goal of getting back into drawing for real, definitely this time, you'll see, pinky swear. Instead, I've transformed it into a development machine. Like, for real. My vaguely recent [MacBook Pro](https://www.apple.com/au/macbook-pro/ "A non-touchscreen iPad with a built-in keyboard.") - yeah, the one with that shitty keyboard - now lives unpowered and unloved in my bedside drawer.

Why, exactly? I'm not *entirely* sure yet. To see if I could? As a development platform it's not quite there yet, but I also don't plan on switching back any time soon, which must count for something. It's pleasant to be feeling things out in a new setup, finding what works, and building an ever-growing list of things that makes no sense.

Look, I'm not really selling you on this. I'm not even sure if I'm trying to; it's **definitely** not for everyone.

Also, I loooooove the iPad itself - it's a great bit of magic space glass, and combined with the [Smart Keyboard Folio](https://www.apple.com/smart-keyboard/ "A bunch of keys to attach to your magic space glass.") it's got this nice little form factor. Just make sure you don't blindly buy the British English model when you wanted the US English model because that's what Apple's site defaults to and then you can't understand why the hell the tilde is way down the bottom near the shift key, and you keep typing a forward slash instead of hitting the weirdly-shaped Enter key.

On the laptop, I spent most of my time in [iTerm](https://iterm2.com/ "I wish this existed for iOS.") - tmux, neovim, git, and ruby (note the lack of capitalisation.) Mimicking that exact setup isn't actually possible on iPadOS (yet?). There's [iSH](https://ish.app/ "An Alpine Linux installation in an iOS app."), an impressive project that embeds an Alpine Linux installation inside an app, but it's emulating X86 instructions, so it's a little slow, and a lot of things understandably Just Don't Work.

I also tried a combination of [Working Copy](https://workingcopyapp.com/ "A git client for iOS.") for git (which is great) and one of the various ports of vim for iOS, but I couldn't see how to make them use my own config and plugins (have I missed something?), which is definitely a dealbreaker. I've been using neovim long enough to have built up my perfect setup, and that's hard to just throw away.

The next best thing is to use a remote server and turn the iPad into a dumb terminal, which is exactly what I've done. Thanks to the awesome Blink app and mosh, I can work on [usesthis.com](https://uses this.com/ "Out of date interviews with random people.") with the same tools as my laptop, with almost no discernible lag, despite me being in Melbourne and the server living somewhere in NYC.

<img src="/images/posts/blink-and-mail.jpg" width="800" height="558" alt="A screenshot of Blink on the left and Mail on the right."> 

It's also forced me to redo how I manage Uses This, which is not a bad thing. Previously the lists of upcoming interviews and ones I'm waiting on were kept in text files and cobbled together with various AppleScript scripts, launched via LaunchBar (which I *definitely* miss.) And it worked! But it was fussy and occasionally needed hand-holding, so this gave me a chance to rework it, and to play with Shortcuts at the same time.

<img src="/images/posts/shortcuts.jpg" width="800" height="558" alt="A screenshot of the Shortcuts app."> 

Now, a dedicated calendar is the source of truth for upcoming interviews, and a list in Reminders keeps track of the ones I'm waiting on, and it's all managed by tapping a button or two. It's real nice.

iPadOS is... look, it's fine. I like iOS, and it's basically the same thing with a(n optional) permanent home screen sidebar and an incomprehensible multi-window systems that others have already covered way better than I could.

Shortcuts is like AppleScript Lite with a GUI and a bunch of missing features:

- Why can't I delete a note?
- Why can't I pick a folder in iCloud Drive?
- Why can’t I mess around with plain files in any folder, instead of only things under the Shortcuts/ folder (unless I use the document picker)?

Weird, weird, weird.

But I'm hopeful these are things that will get addressed eventually, either by Apple or a third-party app that Apple either copies or buys. 

My biggest concern with this setup? Backups. Specifically, backing up my 40,000+ photos, which all currently live in iCloud. That's great and all, but I don't think it's possible to keep a copy synced with the NAS under the TV. My iPad is the 64 GB model, which means there's no way to store them all on the device - I have to trust Apple, and Apple alone, to look after my data. And that makes me super uncomfortable. 

Anyhow, the plan is to keep this post updated as things change, or to burn it to the ground when I inevitably cave in and go crawling back to the laptop.

Right. Back to drawing.
