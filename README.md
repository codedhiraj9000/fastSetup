# FastSetup

FastSetup is a lightweight, beginner-friendly starter framework designed to get your web project up and running quickly. It comes pre-configured with **Tailwind CSS** for styling and **jQuery** for DOM manipulation, built on top of a **TypeScript** foundation. Yet, **JavaScript** is still fully supported and optional if a developer prefers to use it instead.

## Features

* **Pre-configured:** Tailwind CSS and jQuery are already integrated.
* **TypeScript Ready:** Built with TypeScript, but it is entirely optional.
* **Flexible Development:** Write in plain JavaScript if you prefer, or use TypeScript.
* **Simple Setup:** Designed specifically for beginners with minimal configuration required.
* **Zero Dependency Bloat:** Works right out of the box without downloading massive dependency folders.

## Prerequisites

Ensure you have [Node.js](https://nodejs.org/) installed on your machine. 

**Alternative Setup:** If you do not want to use Node.js, you can simply grab the files via `git clone` and preview your site on `localhost` using an extension like **Live Server** (in VS Code) or any native hosting provider.

## Getting Started

### Installation

A major benefit of FastSetup is that it does **not** come with heavy built-in dependencies. This means **no `npm install` is needed!** You can set up the application easily using `yarn`. Run the following command in your terminal:

```bash
yarn setup

```

### Running the Application

Once the setup is complete, you can start the development server by executing:

```bash
yarn start

```

## How to use TypeScript

FastSetup supports TypeScript out of the box.

* **Writing Code:** You can write your logic in `.ts` files.
* **Compiling:** If you do not have TypeScript installed globally, you can compile your files using the local `tsc` (TypeScript Compiler) provided in the project.

*Note: You can simply use standard JavaScript files if you want to avoid the compilation step entirely.*

## License

MIT
