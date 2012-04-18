Designing a XAML layout in Fireworks
====================================

First off, I'm not a graphic artist or especially skilled as a WPF designer. I'm first and foremost a coder. And primarily a WinForms coder, with the odd foray into ASP.NET and (gasp) PHP.

I do have some small ability with Fireworks, mostly either creating basic websites and illustrations, or cutting up designs from designers into websites.

A few years ago I tried making a WPF application for internal use at work. I was greeted with an ugly, generic, white window. I struggled through, copy and pasted in something that made a gradient, fudged my way through the painful designer, and couldn't get my head around MVVM. After all this I managed to make something relatively useable, that was never actually used and has since been forgotten in the sands of time.

I went back to WinForms with pleasure, hoping that either the WPF fuss would die down, or that we would start writing UIs in JavaScript. Turns out the last one was closer to the mark than I would ever have guessed, but I still had some work to do.

I got interested in MarkPad, both because I wanted a good Markdown editor with a HTML preview, and because the Metro interface looked so cool. I jumped in, managed to find a bug in the XAML pretty easily, and managed to fix it. This was also my first accepted pull request, so suddenly I was an OSS developer.

I ended up using [MahApps.Metro](http://mahapps.com/MahApps.Metro/) (a Metro UI library that MarkPad uses) in another internal project. Armed with my new-found MVVM skills (thanks to [Caliburn.Micro](http://caliburnmicro.codeplex.com/), another MarkPad dependency), I quickly had a much better looking (and successful) result that I could be proud of.

Anyway, this all got me interested in how you get from a graphic design to a usable XAML file. This post documents that journey.


## Setting up Fireworks

There is a Fireworks CS4 plugin developed by [Grant Hinkson](http://www.granthinkson.com) that exports to XAML, so we'll use that to get a headstart. You can download it from [here](http://www.granthinkson.com/tools/fireworks/), open the ZIP and double-click the single file. The extension manager will open up and install the extension. I use CS5 but the plugin installed smoothly.

When the extension is loaded, open (or reload) Fireworks, and go to Window -> XAML Suite -> FW to XAML. The extension's window will open, just dock it in the toolbar for now.


## Graphic design
... basic graphic design.

## Exporting to XAML

## Open in Visual Studio

## Clean up

## Move resources out

## Tidy up our layout

## Done

## Resources
- http://www.adobe.com/devnet/fireworks/articles/fw_xaml_panel.html
- http://www.slideshare.net/guest83d3e0/how-to-express-your-creative-self-with-windows-presentation-foundation-and-silverlight
- http://www.granthinkson.com/tools/fireworks/
- http://www.riagenic.com/archives/568
- http://stackoverflow.com/questions/6853784/wpf-designers-what-is-your-design-process

