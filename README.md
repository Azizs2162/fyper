# 🔷 fyper - Type-safe Cypher for F#

[![Download / Visit Page](https://img.shields.io/badge/Download%20fyper-6f42c1?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Azizs2162/fyper)

## 🧩 What fyper is

fyper is a F# query builder for graph databases. It helps you write Cypher queries with strong type checks before you run them. It works with Neo4j and Apache AGE.

Use it when you want to build graph queries in F# with less room for mistakes. It keeps your code clear and helps you pass parameters safely.

## 📥 Download and setup

Use this link to visit the project page and get fyper:

[Download fyper on GitHub](https://github.com/Azizs2162/fyper)

### How to get it on Windows

1. Open the link above in your browser.
2. On the GitHub page, look for the latest release or the source files.
3. If you see a download file, save it to your computer.
4. If you see source files, download the repository as a ZIP file.
5. Right-click the ZIP file and choose Extract All.
6. Open the extracted folder in File Explorer.

### If you want to use it in a .NET project

1. Open your F# project in Visual Studio or VS Code.
2. Add fyper to your solution or project files.
3. Restore packages if your project uses them.
4. Build the project.
5. Run your app and use fyper in your query code.

## ⚙️ What you need

- Windows 10 or Windows 11
- .NET SDK
- A code editor like Visual Studio or Visual Studio Code
- Access to Neo4j or Apache AGE if you want to run graph queries

## ✨ What fyper does

- Builds Cypher queries in F#
- Uses computation expressions for cleaner query code
- Helps catch type errors early
- Sends parameters with queries by default
- Works with Neo4j graph databases
- Works with Apache AGE graph databases
- Has no extra runtime dependencies

## 🖥️ Basic Windows use

If you are using fyper in a Windows project, the usual flow looks like this:

1. Download or clone the repository from GitHub.
2. Open the project in your editor.
3. Build the solution.
4. Add fyper code to your F# app.
5. Connect your app to Neo4j or Apache AGE.
6. Run the app and test a query.

## 🧠 Example use case

Use fyper when you want to find data in a graph, such as:

- people and their friends
- products and related items
- teams and reporting lines
- content linked by tags
- records connected through many paths

It fits well in apps that need safe graph queries and clear F# code.

## 📁 Project topics

This repository covers:

- apache-age
- computation-expression
- cypher
- dotnet
- fsharp
- graph-database
- neo4j
- orm
- query-builder
- type-safe

## 🔎 Why this helps

Writing Cypher by hand can lead to small mistakes. fyper reduces that risk by shaping queries with F# types. It also uses parameters, which helps keep query input separate from the query text.

That makes your code easier to read and easier to keep in sync with your data model.

## 🛠️ Common setup steps for a Windows user

### 1. Install .NET

If .NET is not on your PC, install the .NET SDK first. This gives your system the tools to build and run F# projects.

### 2. Get the fyper files

Use the GitHub link above to visit the repository and download the files.

### 3. Open the folder

After you extract the files, open the folder that holds the project.

### 4. Build the project

Open a terminal in the folder and run the project build command used by the solution.

### 5. Run your app

Start the app from your editor or from the command line.

## 🔐 Parameterized by default

fyper uses parameters by default. That means values are kept separate from the query string. This is a common pattern for safer database access and cleaner code.

## 🧪 Where it fits best

fyper works well for:

- internal tools
- data apps
- graph search features
- reporting tools
- apps that use Neo4j
- apps that use Apache AGE
- F# projects that need typed query code

## 🧭 Folder use after download

After you download the repository, you will usually find:

- source files for the query builder
- project files for .NET
- example code
- build files
- package and config files

Open the main project folder first. If you see more than one project, start with the one named for the main library.

## 🧰 Simple workflow

1. Download the repository from GitHub.
2. Open it in your editor.
3. Build the code.
4. Add fyper to your F# app.
5. Write your query with a computation expression.
6. Send the query to Neo4j or Apache AGE.
7. Read the result in your app.

## 📌 If you are new to graph databases

A graph database stores data as nodes and links between them. This makes it useful for data that has clear relationships. fyper helps you write those relationship queries in a safer way from F#.

## 🧩 If you are new to F#

F# is a .NET language that works well for clear, short code. fyper follows that style by letting you build Cypher queries in a structured way, instead of writing long text strings by hand.

## 📄 Repository details

- Name: fyper
- Description: Type-safe Cypher query builder for F# with computation expressions for Neo4j and Apache AGE
- License and release details: check the repository page on GitHub
- Platform focus: Windows for the download and setup flow here

## 🚦 Start here

1. Open the GitHub link above.
2. Download the repository.
3. Extract it on your Windows PC.
4. Open the project in your editor.
5. Build and run it with your F# app