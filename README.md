# GitHub Markdown Snippets
Helpful Sublime Text snippets to get you started with GitHub flavored Markdown by letting you type the plain old HTML tag names with a prefix.

![](https://img.shields.io/badge/Version-1.1.0-brightgreen.svg)

## Installation

### Via Package Control
The easiest way is to install it via [Package Control](https://packagecontrol.io/).

- Go to **Command Palette** `Ctrl + Shift + P` or `⌘ + Shift + P`
- Select **Package Control : Install Package**
- Search for **Github Markdown Snippets**

### Manual

- Clone the repository or download the [ZIP](https://github.com/praveenpuglia/github-markdown-snippets/archive/master.zip)
- Extract the archive
- Put it in your **Packages**( `Preferences > Browse Packages...` ) directory.  

## Usage
Prefix an HTML tag you know with an **m** in your **.md** file and hit `TAB`. Examples :

- `mh1`    - for Heading 1  
- `mimg`   - for an image 
- `ma`     - for a link
- `mtable` - for a table

and so on...

Long tags like `blockquote` are shortened for power use.

##List of Tab Triggers

```
mh1     // Heading 1
mh2     // Heading 2
mh3     // Heading 3
mh4     // Heading 4
mh5     // Heading 5
mh6     // Heading 6
```
# Heading 1  
## Heading 2  
### Heading 3  
#### Heading 4  
##### Heading 5
###### Heading 6
```
mb         // Bold
mi         // Italic
mbq        // Blockquote
mstrike    // Strikeout
mhr        // Horizontal Rule, Divider
```
**Bold Text** 

*Italic Text* 

> Put a nice, beautiful
> quote here...

~~Strike Through~~ 

---

```
mcode    // Inline Code
mpre     // Code Block with language based highlighting.
```
`Inline Code Snippet`

```javascript
var message = "Code Block";
alert( message );
```

```
ma      // Anchor
mimg    // Image
```
[Link Title](Link) 

![Github Logo](https://wasin.io/wp-content/uploads/2015/05/showimage.png) 

```
mol       // Ordered List
mul       // Unordered List
mtable    // Table
```

1. First Item
2. Second Item
3. Third Item


- I
- Love
- Markdown

| Column 1 | Column 2 |
| ------------- | ------------- |
| Cell 1-1 | Cell 1-2 |
| Cell 2-1 | Cell 2-2 |







  

