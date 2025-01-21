### Modern Cross Platform Development
### by Mark J. Price 

| Step Description                                                           | Command                                         |
| -------------------------------------------------------------------------- | ----------------------------------------------- |
| 1. Create a folder for the solution.                                       | mkdir <solution_folder_name>                    |
| 2. Change to the folder.                                                   | cd <solution_folder_name>                       |
| 3. Create a solution file in the folder.                                   | dotnet new sln --name <solution_name>           |
| 4. Create a folder and project using a template.                           | dotnet new console -o <project_<br>folder_name> |
| 5. Add the folder and its project to the solution.                         | dotnet sln add <project_folder_name>            |
| 6. Repeat steps 4 and 5 to create and add any other projects.              |                                                 |
| 7. Open the current folder path (.) containing the solution using VS Code. | code .                                          |

| Visual Studio | dotnet new | Rider - Type |
| --- | --- | --- |
| Console App | console | Console Application |
| Class Library | classlib | Class Library |
| xUnit Test Project | xunit | Unit Test Project – xUnit |
| ASP.NET Core Empty | web | ASP.NET Core Web Application – Empty |
| Blazor Web App | blazor | ASP.NET Core Web Application – Blazor Web App |
| ASP.NET Core Web API | webapi | ASP.NET Core Web Application – Web API |
| ASP.NET Core Web API (native AOT) | webapiaot | ASP.NET Core Web Application – Web API (native AOT) |
[cs13net9/docs/ch01-project-options.md at main · markjprice/cs13net9 · GitHub](https://github.com/markjprice/cs13net9/blob/main/docs/ch01-project-options.md)

Google Focused Query: garbage collection site:stackoverflow.com +C# -Java
Getting help on Discord and other chat forums see page 43 (64 / 829).
```cs
using static System.Console;
WriteLine("This is C# formatted code.");
```
Good Practice: After the three backticks that start a code block in Markdown, specify a language short name like cs, csharp, js, javascript, json, html, css, cpp, xml, mermaid, python, java, ruby, go, sql, bash, or shell.