# CTRL/CTRL++ for Visual Studio Code

Welcome to the official Github Repository of our CTRL/CTRL++ Tools for Visual Studio Code.

Add [**here**](https://github.com/LukasSchopp/vscode-ctrlpptools/issues) your questions, issues or feature request for the CTRL/CTRL++ extension.

## Quick links
- [Bug report](https://github.com/LukasSchopp/vscode-ctrlpptools/issues/new?assignees=&labels=bug&template=bug_report.md&title=)
- [Feature request](https://github.com/LukasSchopp/vscode-ctrlpptools/issues/new?assignees=&labels=enhancement&template=feature_request.md&title=)
- [Question](https://github.com/LukasSchopp/vscode-ctrlpptools/issues/new?assignees=LukasSchopp&labels=question&template=question.md&title=)
- [Wiki](https://github.com/LukasSchopp/vscode-ctrlpptools/wiki)

------

[![Build Status](https://devops.slooptools.com/jenkins/buildStatus/icon?job=VSCodeCtrl%2Fmaster)](https://devops.slooptools.com/jenkins/view/vsCodeExtenton/job/VSCodeCtrl/job/master/)

This release of the "CTRL/CTRL++ for Visual Studio Code" extension adds language support for "SIMATIC WinCC Open Architecture" CTRL/CTRL++ to Visual Studio Code, including features such as IntelliSense, code highlighting, snippets, static code analyse (CtrlPPCheck), ...

**Supported features**
* CTRL & CTRL++ Language Highlighting
* Snippets
* Static Code Analyse - Linter (Quality checks with the tool **CtrlPPCheck**)
* IntelliSense for basic types and functions
* Hover information for basic types and functions

**Currently unsupported features**
* Debugging
* IntelliSense for custom types and functions
* Hover Information for custom types and functions

## Quick start

1A\. Install the extension

1B\. IntelliSense for functions, constants and variable types

<img src="https://github.com/LukasSchopp/vscode-ctrlpptools/blob/master/images/IntelliSense.gif?raw=true" width="70%"/>

1C\. Hover information for functions, constants and variable types

<img src="https://github.com/LukasSchopp/vscode-ctrlpptools/blob/master/images/Hover.gif?raw=true" width="100%"/>

1D\. Insert code snippets

<img src="https://github.com/LukasSchopp/vscode-ctrlpptools/blob/master/images/dpConnect.gif?raw=true" width="60%"/>

------

> **Optional**: If you want to use the CtrlPPCheck for detailed code analysis

2A\. Download & install the [Quality Check & CtrlPPCheck](https://store.slooptools.com/addon/quality-check-ctrlppcheck) from the SloopTools store.

2B\. Check CTRL/CTRL++ code

<img src="https://github.com/LukasSchopp/vscode-ctrlpptools/blob/master/images/CtrlPPCheck.gif?raw=true" width="90%"/>

2C\. Check result as hover information

<img src="https://github.com/LukasSchopp/vscode-ctrlpptools/blob/master/images/dpSubStrError.png?raw=true" width="60%"/>

2D\. Or look at the results in the problems log.

<img src="https://github.com/LukasSchopp/vscode-ctrlpptools/blob/master/images/ProblemLog.png?raw=true" width="70%"/>

------

## Questions and feedback

**[FAQs](https://github.com/LukasSchopp/vscode-ctrlpptools/wiki/FAQ)**
<br>
Check out the FAQs before submitting a question or issue.
<br>

**[Provide feedback](https://github.com/LukasSchopp/vscode-ctrlpptools/issues/new/choose)**
<br>
Submit questions, issues, or feature requests for the extension.
<br>

**[Known issues](https://github.com/LukasSchopp/vscode-ctrlpptools/issues)**
<br>
If someone has already submitted an issue that encompasses your feedback, please leave a 👍 or 👎 reaction on the issue to upvote or downvote it to help us prioritize the issues.
<br>

## Features

### Syntax highlighter

Fully integrated syntax highlighter for CTRL language.
* All basic CTRL key words
* All basic CTRL variable types
* CTRL and CTRL++ support

### Quality Checks

A collection of various Code Quality checks that are easy to use.

With the SloopTools Quality Checks, we want to improve the Code Quality of WinCC OA projects and offer a comprehensive service.

#### CtrlPPCheck

The static code analysis tool **CtrlPPCheck** is a variation of the well-known cppCheck that understands WinCC OA CTRL and CTRL++.

Included are, among many others, these checks:
* Undefined variables
* Unused variables
* Unused functions
* Dead code
* Comparison is always true / false
* Return value of a specific function is not used
  e.g. return from dpExists ()
* and other ...

CtrlPPCheck has configured all known CTRL functions and constants.
Note: The configuration was carried out with the WinCC OA version 3.16 P12. If you have any problems, please let us know and create an [issue](https://github.com/LukasSchopp/vscode-ctrlpptools/issues/new/choose).

FREE version of CtrlPPCheck included in DEMO version!
Get more information [here](https://store.slooptools.com/addon/quality-check-ctrlppcheck).

## Roadmap

**Short Term**
* "Go to" Definition
* Code Formatter

**Medium Term**
* Hover information for custom types and functions
* ColorDB editor
* Highlighting for project config files

**Long Term**
* Start CTRL script from visual studio code
* Show WinCC OA logs in visual studio code
* Start WinCC OA unit test
* SQL selector for dpQuery()

## Limitations

* Not all CTRL functions are available in detail. Full availability will follow.

## Contribution

If you want to contribute in the CTRL/CTRL++ extension, please contact us on following mail:
info@slooptools.com
