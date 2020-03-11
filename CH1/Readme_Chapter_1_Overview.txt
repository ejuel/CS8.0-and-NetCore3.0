Overview:
    - Ch 1 goes over the major changes since .NET Core began in 2015 and the history of it's development.
    - The chapter goes on to initialize Visual Studio Code and a simple hellow world tutorial
    - In the next chapter we will learn to speak C#

Exercise 1.1 Test your knowledge:
    Note: These answers may be wrong, I'd be happy to receive feedback
    1. Why can a programmer use different languages, for example, C# and F#, to write pplications that run on .NET Core?
        .NET Core includes programming language runtimes for C# and F#, so when compiling code the software puts it in an intermeditate language (DLL or EXE) to execute at runtime.
    2. What do you type at the prompt to create a console app?
        dotnet new console
    3. What do you type at the promt to build and execute C# source code?
        dotnet run
    4. What is the Visual Studio Code keyboard shortcut to view Terminal?
        Ctrl+Shift+`
    5. Is Visual Studio 2019 better than Visual Studio Code?
        2019 is a full IDE, however VS Code is more like a text editor with integration for community extensions like the Atom editor 
    6. Is .NET Core better than .NET Framework?
        .NET Core is open source, free, cross platform (OSX, Windows, Linux), and has forks to support mobile, web, and desktop applications. 
        .NET Framework shares the same API as .NET Core, however it's closed source and lacks cross platform support. 
    7.  What is .NET Standard and why is it important?
        A specification for set of APIs that all .NET platforms can implement to indicate their level of compatibility.
    8. What is the name of the entry point method of a .NET console application and how should it be declared?
        The "Main" method is the entry point of a C# application:
            class TestClass
            {
                static void Main(string[] args)
                {
                    // Display the number of command line arguments.
                    Console.WriteLine(args.Length);
                }
            }
    9. Where would you look for help about a C# keyword?
        Probably Google with an inclusion tag such as "+C#"
    10. Where would you look for solutions to common programming problems?
        Stack Overflow is a good resource, but probably search it via Google with the tag "site:stackoverflow.com"
        Alternatively use DuckDuckGo.com and include "!so" at the beginning of the search (I think "so"="Stack Overflow")

Exercise 1.2 - Practice C# anywhere
    See https://online.visualstudio.com/ or https://dotnetfiddle.net/
    I think it works on chrome books, but don't have one to try with.

Exercise 1.3 Explore topics
    Note: I'm not going to include all of them (too much typing), but here's a few:
    - Welcome to .NET Core: https://dotnet.github.io
    - .NET Core Command-Line Interface (CLI) tool: https://aka.ms/dotnet-cli-docs
    - .NET Core runtime, CoreCLR: https://github.com/dotnet/coreclr/
    - .NET Core Roadmap:
    - .NET Standard FAQ:
    - Stack Overflow:
    - Google Advanced Search:
    - Microsoft Virtual Acedemy:
    - Microsoft Channel 9: Developer Videos: https://channel9.msdn.com/

