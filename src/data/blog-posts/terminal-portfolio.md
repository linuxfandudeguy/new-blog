---
title: The Worst Blog Post Ever
publishDate: 07 Dec 2024
description: I wish I could make description unrelated but that is pretty much impossible.
---

![Screenshot 2024-10-13 10 43 37 AM](https://github.com/user-attachments/assets/e0a061ae-35de-4244-b294-6738a1a6a764)

## Introduction

I made a terminal-like portfolio website, which I recently deployed. This project was forked from satnaing, and after forking it, I added my own features.

## Tech Stack

This is an entirely frontend project with no server code involved. For the frontend, The original creator chose React over plain JavaScript and Next.js. Here’s his reasons:

> - **Declarative Code**: Writing declarative code makes managing the HTML DOM less tedious compared to imperative JavaScript.
> - **Performance and Reliability**: React is known for its speed and reliability.
> - **Simplicity**: I didn’t require extensive SEO features, routing, or image optimization that Next.js offers.
> - I opted for TypeScript for its type-checking benefits.

The original creator of the repository I forked used `styled-components` for styling his React components.

Here’s a quick recap of my tech stack:

- Frontend: [ReactJS](https://reactjs.org/ "React Website"), [TypeScript](https://www.typescriptlang.org/ "TypeScript Website")
- Styling: [Styled-Components](https://styled-components.com/ "Styled-Components Website")
- State Management: [Context API](https://reactjs.org/docs/context.html "React ContextAPI")
- Deployment: [Vercel](https://vercel.app/ "Vercel")

## Features

Here are some features of my terminal portfolio website:

### Multiple Themes

Users can switch between multiple themes. At the time of writing, there are five themes available, with plans to add more in the future. The selected theme is saved in storage, ensuring it persists after a page refresh.

### Command-line Completion

To provide a nice terminal experience, satnaing implemented a CLI completion feature that auto-completes incomplete typed commands when you press ‘Tab’ or ‘Ctrl + I’.

### Previous Commands

Users can navigate through previously typed commands using the Up and Down Arrow keys.

### View/Clear Command History

Users can view previously typed commands by typing ‘history’ in the command line. The command history and terminal screen can be cleared by typing ‘clear’ or pressing ‘Ctrl + L’.

### Theme Showcase

Here’s a video demonstrating different themes available in the terminal portfolio and me giving my opinion:

<video width="640" height="360" controls>
   <source src="/Screen recording 2024-10-13 10.50.04 AM.webm" type="video/webm" />
   Your browser does not support the video tag.
</video>

## Conclusion

This is my first time overly working with React components, and I think the website turned out great.

## Project Links

- Website: [https://lelterminal.vercel.app/](https://lelterminal.vercel.app/ "https://lelterminal.vercel.app/")
- Repo: [https://github.com/linuxfandudeguy/terminal-portfolio](https://github.com/linuxfandudeguy/terminal-portfolio "https://github.com/linuxfandudeguy/terminal-portfolio")
