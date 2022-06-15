# Setup

As you might expect, the first step to getting started with any new technology is setting up a couple of tools.

We'll be using [github.dev](github.dev), a free, online code editor, for this workshop. If you've ever used [Visual Studio Code](code.visualstudio.com), this code editor may look familiar to you.

Another tool in our kit is going to be [Node.js](https://nodejs.org/en/). [Node.js](https://nodejs.org/en/) is an open-source, cross-platform, back-end JavaScript runtime environment that runs on the V8 engine and executes JavaScript code outside a web browser.

## Creating a repository and opening it in github.dev

Let's start by creating a new repository for this project on GitHub, and then opening it in github.dev.

1. If you don't have a GitHub account, go ahead and [join GitHub](https://github.com/join). Then, [create a new public repository](https://github.com/new) named **predicting-harvest-time**. If you've never made a GitHub repository before, check out the [documentation](https://docs.github.com/get-started/quickstart/create-a-repo) for more information. Make sure to select **Public** and to initialize the repository with a **README**.
1. Navigate to your new repository on GitHub.
1. Open the repository in github.dev by pressing the `.` key from the repository page, or swap `.com` with `.dev` in the URL. This will set up a [VS Code](code.visualstudio.com) environment in your browser.

## Installing Nodejs

1. You can download and install Node.js from their [official website](https://nodejs.org/en/). It is recommended to download the LTS or Long Term Service version. As of writing this, the current LTS version is **v16.15.1**.

2. You can verify installation by running the following command in your terminal.

`node -v`

## Turn on AutoSave

One of the best productivity features in github.dev and Visual Studio Code is **AutoSave**. AutoSave automatically saves changes to your files, so you don't have to worry about losing any of your work. To turn on AutoSave, select the three parallel lines icon on the left-hand side of your github.dev window in the Activity Bar. Go to **File > AutoSave**. Your AutoSave is turned on if there is a check mark next to the AutoSave menu item.

## Summary and next step

Congratulations! You have the tools you need to begin working with IoT hub. Next, let's [provision some resources](./1-provision-resources-in-azure.md).
