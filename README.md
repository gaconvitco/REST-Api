# REST-Api
RESTfull api with C# and Visual studio Codefirst

# C# Coding Conventions
The main purpose is to define the general guidelines to enforce consistent coding styles and formatting that can be useful for developers to avoid common mistakes they do while development of software applications using C#. This post covers naming conventions, coding styles and some architecture level suggestions. To understand better I have colored C# keywords in BLUE. The information provided in this document is compiled from the coding standard and best practices published in various blogs, articles and my previous 8+ Years extensive experience in .NET technology. I have also referred to the [C# Coding Conventions](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/inside-a-program/coding-conventions) provided by Microsoft.
## Purpose of coding standard and best practices to do it
Coding standards are a set of guidelines used for programming language that recommends programming style and best practices to achieve it. The coding standards generally covers indentation, comments, naming conventions, programming practices, file structure within project, architectural best practices etc. Software developers are highly recommended to follow these guidelines. The coding guidelines have following advantages.
1. Increases the readability of source code written.

2. Will contain less bugs and works more efficiently.

3. Requires less maintenance.

4. Easier for old and new developers to maintain and modify the code.

5.  Leads to increase in productivity of developers.

6.  Reduces the overall cost for software development.

7.  Make the difference between a successful project and a project that is, at worst, dead on delivery.
## How to follow coding standards in your teams
1.       Make your own coding standard document as per industry standards by sitting together in a team and share across the team.

2.       Look at the existing code and decide what you want in yours.

3.       Assign someone to do the frequent code review and peers reviews.

4.       Involve seniors and get some inspiration from their previous experience.

5.       Whenever new fresh guy arrives, introduce projects or products codebase to him or her. Educate that guy to follow coding standards.

## Naming Conventions
There are three type of naming conventions generally used while doing C# programming

1. Pascal Convention – First character of all word are in upper case and other characters are in lower case.
```
Example: HelloWorld
```
2. Camel Case Convention – The first character of all words, except the first word, is upper case and other characters are lower case.
```
Example: helloWorld
```
3. Hungarian Case Convention – The data type as prefix is used to define the variable by developers long ago. This convention is not used anywhere now a day’s except local variable declaration.
```
Example: 
string m_sName;
string strName;
int iAge;
```
Let’s generalize the module with correct and incorrect naming conventions.
|Sr. No | Module  | Description | Correct | Wrong|
|-------|---------|-------------|---------|------|
|1. | Class   |Use Pascal conventions for defining class name| public class HelloWorld

{

}| public classhelloWorld
{

}
|
