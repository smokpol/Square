# Square
Square is an open source graphic library for C++

Its goal is to be somewhat simple yet very customizable, allowing for disabling, switching or modifying behavior of classes.

To ensure its modifiability it is a group of DLL files.

# Authors
It is **Not** developed or in any other way related to Square Open Source company,
it is developed by me Smokpol (for now because any pull requests would be apreciated), 
and I didn't know about existance of Square Open Source before googling the name of this library.

# Why this name?
For two reason

  The First one (being the quick one), the squares are simple and hopefully this library be simple, and also they symbolize honesty and stabillity

  The Second one (being the true one), It is a project in which I hope to learn a little bit more about using low level graphics API and creating them in general, why would I want that useless knowladge? Well I plan to use it to create a fully open source 3D Game Engine that would be both quick and powerfull and whats more that is customizable The Tesseract, I've decided to name and create Tesseract before Square but when I was developing a game (I'm a solo game dev) that pretty much requires mod support I've developed a lot of tools that would make process of adding items to that game a lot easier I've decided to create square. But why not cube and why tesseract? Well when one big company decided that it will be charging for each download of programs made with their engine, I've come up with a dream of an **Fully Open Source and Free** game engine and it being name as a whole open source dimmension more than the enigne of that company it was named Tesseract. (I'm sorry if you don't know what company I'm talking about but I don't want any risk of me or The Tesseract being sued)

# Why not SFML?
I feel like sfml lacks the customizability (I know the source is available and I could recompile it but tesseract). 

If you searching for easy to use graphic library go check https://www.sfml-dev.org/

# Why DLLs instead of something else?
Dlls allow for increadible customizability while being almost as quick as static libraries. Except when they are intilizated than they are **painfully** slow. 

But I do not care that much about intialization time, and static libraries lack abillity to customize something on runtime without checking some sort of resource every time function is called or it uses virtual functions which works much better than DLLs but than they're not as modular (at least I think so) but due to slight performance loss for DLLs Tesseract, to allow customizabillity in terms of diffrent and weird boot options it will be able to use JIT compillation somewhat easly. (JIT compillation is compilling parts of the code at runtime) 
