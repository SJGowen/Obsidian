### Modern Cross Platform Development
### by Mark J. Price published by Packt

### 1: Hello, C#! Welcome, .NET!

| Step Description                                                           | Command                                         |
| -------------------------------------------------------------------------- | ----------------------------------------------- |
| 1. Create a folder for the solution.                                       | mkdir <solution_folder_name>                    |
| 2. Change to the folder.                                                   | cd <solution_folder_name>                       |
| 3. Create a solution file in the folder.                                   | dotnet new sln --name <solution_name>           |
| 4. Create a folder and project using a template.                           | dotnet new console -o <project_<br>folder_name> |
| 5. Add the folder and its project to the solution.                         | dotnet sln add <project_folder_name>            |
| 6. Repeat steps 4 and 5 to create and add any other projects.              |                                                 |
| 7. Open the current folder path (.) containing the solution using VS Code. | code .                                          |

| Visual Studio                     | dotnet new | Rider - Type                                        |
| --------------------------------- | ---------- | --------------------------------------------------- |
| Console App                       | console    | Console Application                                 |
| Class Library                     | classlib   | Class Library                                       |
| xUnit Test Project                | xunit      | Unit Test Project – xUnit                           |
| ASP.NET Core Empty                | web        | ASP.NET Core Web Application – Empty                |
| Blazor Web App                    | blazor     | ASP.NET Core Web Application – Blazor Web App       |
| ASP.NET Core Web API              | webapi     | ASP.NET Core Web Application – Web API              |
| ASP.NET Core Web API (native AOT) | webapiaot  | ASP.NET Core Web Application – Web API (native AOT) |
[cs13net9/docs/ch01-project-options.md at main · markjprice/cs13net9 · GitHub](https://github.com/markjprice/cs13net9/blob/main/docs/ch01-project-options.md)

Google Focused Query: garbage collection site:stackoverflow.com +C# -Java
Getting help on Discord and other chat forums see page 43 (64 / 829).
```cs
using static System.Console;
WriteLine("This is C# formatted code.");
```
Good Practice: After the three backticks that start a code block in Markdown, specify a language short name like cs, csharp, js, javascript, json, html, css, cpp, xml, mermaid, python, java, ruby, go, sql, bash, or shell.

https://github.com/search has an advanced search that allows a query like "email repo:dotnet/runtime language:C#" to be entered.

Official .NET blog, standups and news [.NET Blog](https://devblogs.microsoft.com/dotnet/)
Walk through of new features [.NET Community Standups | .NET Live TV](https://dotnet.microsoft.com/en-us/live/community-standup)
Computer stuff they didn't teach you [Computer Stuff They Didn't Teach You - YouTube](https://www.youtube.com/playlist?list=PL0M0zPgJ3HSesuPIObeUVQNbKqlw5U2Vr)
GitHub Copilot [GitHub Copilot · Your AI pair programmer](https://github.com/features/copilot)
JetBrains AI Assistant [AI Assistant in JetBrains IDEs | The IntelliJ IDEA Blog](https://blog.jetbrains.com/idea/2023/06/ai-assistant-in-jetbrains-ides/)

Links about using AI for coding:
* A Beginner’s Guide to Prompt Engineering with GitHub Copilot: https://dev.to/github/a-beginners-guide-to-prompt-engineering-with-github-copilot-3ibp 
* The Register article about AI: https://www.theregister.com/2024/01/27/ai_coding_automatic/ 
* StackOverflow 2024 survey – Code editor / IDE: https://survey.stackoverflow.co/2024/technology#1-integrated-development-environment 
* StackOverflow 2024 survey – AI search tools: https://survey.stackoverflow.co/2024/technology#1-ai-search-and-developer-tools

Current versions of .NET [Versions of .NET](https://versionsof.net/)
Upgrade to a new .NET version [Upgrade to a new .NET version - .NET](https://learn.microsoft.com/en-us/dotnet/core/install/upgrade)
freeCodeCamp Tutorial [(New) Foundational C# with Microsoft Certification](https://www.freecodecamp.org/learn/foundational-c-sharp-with-microsoft/)
Explore Polygot Notebooks [cs13net9/docs/polyglot-notebooks.md](https://github.com/markjprice/cs13net9/blob/main/docs/ch01-polyglot-notebooks.md) 
Polyglot Notebooks enables you to create a single notebook file that mixes "cells" of Markdown and code. It works by hosting an instance of the .NET Interactive engine.
Free Uni Course [CS50: Introduction to Computer Science | Harvard University](https://pll.harvard.edu/course/cs50-introduction-computer-science)

.NET newsletters:
* Milan Jovanovic’s The .NET Weekly: https://www.milanjovanovic.tech/blog
* C# Digest: https://csharpdigest.net/
* Alvin Ashcraft’s The Morning Dew: https://www.alvinashcraft.com/
* Mukesh’s .NET Newsletter: https://newsletter.codewithmukesh.com/ 
* JetBrains’ dotInsights: https://www.jetbrains.com/lp/dotinsights-monthly/

Summary Chapter 1: [cs13net9/docs/book-links.md at main · markjprice/cs13net9](https://github.com/markjprice/cs13net9/blob/main/docs/book-links.md#chapter-1---hello-c-welcome-net)

### 2: Speaking C# 


