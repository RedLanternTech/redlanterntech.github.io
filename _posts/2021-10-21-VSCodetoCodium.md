---
layout: post
title:  Switching from VS Code to VS Codium
---

So here is a late post and one right after my one from yesterday.  I've always been a big fan of VSCode from Microsoft.  It still boggles my mind that Microsoft not only 
released a program that runs on Linux (along with Powershell and Microsoft Edge) but made it open source.  However, these still do get a lot of criticism, especially 
those who are proponents of free and open source software.  I firmly follow the belief of using what works.  For me, VS Code works.  I did flirt with the idea of
updating this blog in Emacs or VIM, but honestly, I find myself coming back to VS Code.  Throw on a spell checker and the VIM addon and it just works for me.

Because of VS Codes open nature, a spinoff project exists that takes VSCode and re-releases it without the telemetry turned on (or existing) named VSCodium.  I get why Microsoft and other
vendors do telemetry, it can help with crash data, give Microsoft an idea of its install base, and how people are using VSCode.  However, I am in the middle of trying 
to reduce how much telemetry companies do get off of me.  For example at home I am mostly on Linux (Linux Mint and Kubuntu) and with plans on taking my next smartphone to 
GrapheneOS in the near future, its probably best to say I'm up for anything that doesn't do any telemetry data.

So I have played with VSCodium in the past.  When I was shopping around Linux Distributions, I came across ParrotOS.  More well known for their security distribution,
they also release a home version of it.  That came with VSCodium.  I played with it, but I didn't like the lack of addons, so I avoided it.

Well this evening, after the aforementioned flirting with Doom Emacs (which is nice and if it works for you, awesome), I threw back on VSCodium to see if I could make it work.  It was then I discovered, you can just add in the VS Code Marketplace by adding in a file under ~/.config/VSCodium named product.json.  
Add in the following lines of code

```
{
  "extensionsGallery": {
    "serviceUrl": "https://marketplace.visualstudio.com/_apis/public/gallery",
    "cacheUrl": "https://vscode.blob.core.windows.net/gallery/index",
    "itemUrl": "https://marketplace.visualstudio.com/items",
    "controlUrl": "",
    "recommendationsUrl": ""
  }
}
```

and boom, now I have all the addons I like in VSCodium.  I did learn something, next time check out the [Blog on GitHub](https://github.com/VSCodium/vscodium/blob/master/DOCS.md#extensions-marketplace) as that is where I found the magic sauce to make it work.  

Lets see how this goes.  I will have to swap things out on my desktop tomorrow.  

73's and Take Care