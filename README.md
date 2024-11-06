# Gradient Network Mass Nodes Runner

This is a tool to run nodes on your Gradient Network account in bulk without using any browser extensions.


<details>
<summary>Table of Contents</summary>

- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Requirements](#requirements)
- [FAQ](#faq)
- [Tech Stack](#tech-stack)

</details>

## Demo

![demo](./gradient-network.gif)

## Installation

1. Clone this repository

```
git clone https://github.com/decryptable/gradient-network.git
```

2. Move to repository directory

```
cd gradient-network
```

3. Install Yarn

```
npm install --global yarn
```

4. Install dependencies

```
yarn install
```

## Usage

To use this tool, simply run it:

```
node .
```

## Features

- Automatically run all nodes that are offline. When using the browser extension, you can only run 1 node. While this tool is able to run all nodes.
- You can add new nodes if desired each time you run the tool.
- Supports all platforms (Android, Windows, Linux, etc).
- Does not require any proxy settings.

## Requirements

- NodeJS installed
- Curl or wget installed
- Git installed

## FAQ

#### Does this tool have a risk of hitting the tire?

I don't know. One thing is for sure, we don't condone any cheating. By using this tool, you are aware of the risks in the future.

#### Why don't you open-source the code?

Because this will make security updates to the Gradient Network system faster when they find out where the weaknesses are in the code I created.

#### Does it contain a virus?

Silly question. I'm not interested in giving a backdoor to the tools I create. If you have doubts, there's no need to use them.

## Tech Stack

- [TypeScript](https://www.typescriptlang.org/)
- [webpack](https://github.com/webpack/webpack)
- [bytenode](https://github.com/bytenode/bytenode)
- [chalk](https://github.com/chalk/chalk)
- [inquirer.js](https://github.com/SBoudrias/Inquirer.js)
