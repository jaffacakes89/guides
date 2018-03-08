# Markdown Guide

Thanks to this useful cheat sheet from [GitHub](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf).

## Editors

Editors such as VS Code and Atom support Markdown out of the box. Just create a new file with a .md extension.

You can toggle the visualization of the editor between the code and the preview of the Markdown file. To switch between views, press Ctrl+Shift+V in the editor. You can view the preview side-by-side (Ctrl+K V) with the file you are editing and see changes reflected in real-time as you edit. Easy :-)

## Headers

# This is a \<h1> tag
## This is a \<h2> tag
#### This is a \<h4> tag

## LISTS
* Item 1
* Item 2
  * Item 2a
  * Item 2b

1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b

## Images

![Me](/images/me.jpg)

You can also use HTML anywhere you like

<img src="images/me.jpg" width="50">

## Links
[My GitHub](https://github.com/jaffacakes89)

## Emphasis

*This text will be italic*

_This will also be italic_

**This text will be bold**

__This will also be bold__

*You **can** combine them*

## Block Quotes

> "You can’t stop things like Bitcoin. It will be everywhere and the world will have to readjust. World governments will have to readjust” – John McAfee, Founder of McAfee

## Backslash Escapes
\*literal asterisks\*

## Tables
You can create tables by assembling a list of words and dividing them with hyphens    
\- \(for the first row), and then separating each column with a pipe | 

First Header | Second Header
------------ | -------------
Content cell 1 | Content cell 2
Content column 1 | Content column

## Code Blocks
```javascript
calculateHash(index, previousHash, timestamp, data) { 
  return SHA256(index + previousHash + timestamp + JSON.stringify(data)).toString(); 
}
```