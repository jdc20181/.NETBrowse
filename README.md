# Project Overview

Does anyone remember NetScape? It was the pre-dawn of what is now Mozilla FireFox - an open source browser built for those who like a open, secure world wide web. Sometime ago they decided to offer a way to run FireFox with .NET instead of the over hydrated full fledged browser we know as FireFox - this simmered down project was named GeckoFX and was supported for many years. Unfortunately a drawback is that it is now just as old as .NET itself and its not a pretty or fast solution for browsing needs. So in general this project will take some modern approaches to the very old simmered down GeckoFX and turn it into a concept. This is not intended for production for now at least. 

# Using the project

The project is not designed for production use unless you like to live on the edge... no pun intended. It is primarily designed to be a concept project for my upcoming college years - this project is a spin off of 2x previous attempts, one was BeffsBrowser (No idea how I got that name btw) and Krypto (which ended up morphing into its own project that has since stopped for some reason or another). 

Primarily I have a few thoughts in mind in this adoption of the new project:

- Clean up interface
- Upgrade the Engine to something more modern (and get it out of being just a concept!!)
- Rewrite the code base to be readible, and maintainable.
- Adopt stricter coding
- Integrate more cloud services
- Update Datastore systems that are used (Sadly, I originally used XML/Txt files which are well lets just say they work but not quite a standard for those to be used for databases solely anymore) 

# Current Progress

As you can tell its pretty empty in here, that isn't by mistake - I privatized my previous versions of the project and am swiftly typing away at the rewrite. 

# What is available

So, to keep things clean and precise I am including only the source code elements - there will be NO designer code present in this - instead in the releases tab you can download the latest "SourceCode" Release in relation to the current installable release! 

# Code Signing, Defects, Bugs, Missing Features, other misc issues. 

I am aware that the application is not signed by a fancy smancy certificate that most applications have, with me also being the little guy I can't just flip a switch and make one for myself either - I am exploring a solution to this (which will be added to an issue btw if you wanna help me out)

I am aware of defects with the use of CefSharp the good news is I included Gecko as well it is just really OLLLLLLLLLLLLLD like FF Version 45 old (and the project was abandonded for .net) (Cef Sharp may not initally be available, eventually Gecko will be excluded)

A few bugs with the tab browsing experience are known, and there is also some issues with updating to the latest version which has to do with the code signing fiasco. 


