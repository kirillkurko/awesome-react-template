# awesome-react-template
Create React app with TypeScript, ESLint, Prettier configured in a single command.

> **Warning**: template is in his early days, so issues and incompatibilities
> are possible. Feel free to contribute and report issues if they appear. 
> I'll do some heavy testing in next weeks to make sure that it's working 
> fine with at least most popular libraries.

## Motivation

React ecosystem is flexible. And that's great, because you can configure only the 
tools, you need for your current project. You don't always need styled-components, 
MUI or react-query and many other libraries. But there are some tools, that you want 
to have in every React project. These tools are Typescipt, ESlint and Prettier, and they 
are really important for code quality. And it becomes weird when you configure them from project 
to project. This template is created to solve this problem - scaffold your next React 
project with Typescript, ESlint and Prettier configured in just a single command.

## Getting Started

To create a new project based on this template, run:

```bash
npx degit kirillkurko/awesome-react-template my-app
```

That's it - you can now start with development!

`.nvmrc` file is available. Current node version is `v14.19.3`, but it works fine with
higher versions. Node version will be increased in the future.

## Tools and libraries
[Vite](https://vitejs.dev/) is used for builds because of its speed. 

ESLint and Prettier configurations are opinionated, but they are based on best practices and this
is what I see in almost every project, so I feel that we're moving to kinda industry-wide 
standard config. Better description of present config is coming soon.

Dependabot is used to keep dependencies up to date. If you don't need it or if your 
repository is not hosted on GitHub, you can remove `.github` folder.
