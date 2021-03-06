# Introduction

## What is this book about?

Rust in the last few years has turned out to be a powerful programming language that can be used in several settings for many different tasks. In this book we will learn how to build a simple application for each of the following settings:

- CLI: Command Line Interface
- TUI: Terminal User Interface
- GUI: Graphical User Interface
- API: Application Programming Interface (REST)
- WUI: Web User Interface
- AUI: App User Interface
- PI: Physical Interface (Embedded)
- GI: Game Interface (Game Engines)
- AI: Artificial Intelligence


Before we even begin looking at the rust ecosystem, however, we will need to understand a bit about the field itself. Most of these domains rarely overlap in a person's career, for example a person involved in building web user interfaces rarely writes code for embedded applications, similarly a data scientist working on AI code wouldn't even know where to begin writing a game, (generally). So we will need context, not a lot of it, only enough to get started.

For each domain we will also provide a list of resources for further study and analysis.

Then we'll look at what is the current state of technology for each domain. What libraries are present. For each domain we'll try to do an exhaustive comparison of different crates and libraries present. Then we will proceed to select one or two and build a simple application.


## Motivation

> I don't believe that you should use the most suitable language for a specific domain or problem at all costs. I think consistency among your / company projects, productivity and simplicity should have the highest priority. And Rust is a very universal language so I think it's a good choice for almost all cases.
>
> -- [Martin Kavik](https://github.com/MartinKavik) (Creator of [MoonZoon](https://moonzoon.rs))

## Future Goal

One of the goals of this book is also to be able to build an app with fixed business logic and a changeable interface.