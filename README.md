# How to C#

This repository contains my first C# project. I am more experienced with the
UNIX way of getting things done than the Windows way of gettings done, so this
project represents my first attempt to do things the Microsoft way. This
project was created in Microsoft Visual Studio.

## Getting Started

I opened Visual Studio and clicked on things to create a new project. The
template I chose to work with was ASP.net with React. I did this mainly
because I am already familiar with React, so this way, there are at least
some things to work with that aren't entirely new.

Source control started automatically, with the "Output" console in Visual
Studio informing me that a new git repository was created. A `.gitignore`
file was created automatically. However, a `README.md` file was not! So I
created this file through clicking things in the "Solution Explorer" located
to the right side of Visual Studio by default.

### First build

Before adding functionality, I wanted to see what the boiler plate code gave
out of the box. From the top menu, I selected `Build -> Build Solution`.

Doing so triggered some scripts that did things like install relevant packages
using `npm`. I already had `npm` installed on my machine. Running these
scripts took several minutes because there was a lot to download and install.

While stuff was installing, I poked around a bit, looking at what files were
automatically created when I made this project. I noticed a directory 
`ClientApp/` which contains React code like stuff I have seen before. Nice!

Okay, once `npm` finished installing stuff,  Visual Studio indicated to me
that everything had been built successfully. I clicked the green rightward
pointing arrow in the top menu bar to run my web app. Microsoft Edge opened
by defeault and lo and behold a web page loaded successfully.

> Welcome to your new single-page application, built with:
>
> - ASP.NET Core and C# for cross-platform server-side code
> - React for client-side code
> - Bootstrap for layout and styling
>

Are you telling me all of these things just... automatically work? Cool!

Closing the Edge browser window that opened up took me back to the normal
code editing screen I was on.

### Changing some things

So far, we have done... pretty much no coding. We created a new project and
took a look at many of the things Visual Studio did for us automatically.