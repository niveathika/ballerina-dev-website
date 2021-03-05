---
layout: ballerina-tooling-guide-left-nav-pages-swanlake
title: Installing VS Code
permalink: /learn/tooling-guide/vs-code-extension/installing-vs-code/
active: installing-vs-code
intro: The VS Code Ballerina extension provides the Ballerina development capabilities in VS Code. The below sections include instructions on how to download, install, and use the features of the VS Code extension.
redirect_from:
  - /learn/tools-ides/vscode-plugin
  - /learn/tools-ides/vscode-plugin/
  - /learn/vscode-plugin
  - /learn/vscode-plugin/
  - /learn/tools-ides/setting-up-visual-studio-code
  - /learn/tools-ides/setting-up-visual-studio-code/
  - /learn/setting-up-visual-studio-code
  - /learn/setting-up-visual-studio-code/
  - /swan-lake/learn/getting-started/setting-up-visual-studio-code/
  - /swan-lake/learn/getting-started/setting-up-visual-studio-code
  - /learn/setting-up-visual-studio-code
  - /learn/tooling-guide/
  - /learn/tooling-guide
  - /learn/tooling-guide/vs-code-extension/installing-vs-code
---

## Downloading VS Code 

Download the [Visual Studio Code editor](https://code.visualstudio.com/download).


## Installing the Extension

>**Tip:** If you installed a new Ballerina version recently, you might need to restart the VS Code Editor to pick the new Ballerina version. If you are using macOS, press `Command+Q` keys to quit the app and reopen it.

Follow the steps below to download and install the Ballerina VS Code extension.

1. Download the [Visual Studio Code Ballerina Extension](/downloads).

2. Follow either of the below approaches to install the extension.
    - [Using the VS Code editor](#using-the-vs-code-editor)
    - [Using the Command Line](#using-the-command-line)

### Installing via the VS Code Editor

1. Click **View** in the top menu of the editor and click **Command Palette**.
2. In the search bar, type "vsix" and click **Extensions: Install from VSIX...**.
3. Browse and select the VSIX file of the extension you downloaded.

![Install using the Command Palette of the editor](/learn/images/install-via-palette.gif)

### Installing via the Command Line
In a new Command Line tab, execute the below command.
```bash
$ code --install-extension <BALLERINA-EXTENSION-DIRECTORY>
```
> **Tip**: In the above command, `<BALLERINA_EXTENSION-DIRECTORY>` refers to the path of the Ballerina extension directory (i.e., the VSIX file) you downloaded.








