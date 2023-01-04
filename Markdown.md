
## Contents

1. [What is Markdown](#teste)
2. <a href="#test">aaaaaaaaa</a>
3. 



## What is Markdown { #aboutMarkdown }

Markdown is a simple markup language that converts text into HTML using only special characters to do that.

## Headings 

In markdown syntax, we have six weights of headings differentiated by the amount of # before the text.
 
# Heading 1

## Heading 2

### Heading 3 

#### Heading 4 

##### Heading 5

###### Heading 6

## Text Styling

We can style the text in different ways.

| Caracter | Style | Exemple |
| :--------------: | :--------: | :--------------: |
| ** | Bold | **Text** |
| * | Italic | *Text* |
| *** | Bold and Italic | *** Text *** |
| ~~ | Strikethrough | ~~Text~~ |
| == | Highlight | ==Text== |

## Blockquote

If we need a blockquote is very simple, we only need to add a > before the text. 

> A blockquote exemple

## Code Blocks

We can make a code block to write code in any language like Js or C#. We have code highlight.

To do this, we need to put \`\`\`\ and the name of the code language, to result in this.

```html
<html>
	<head>
		<tittle>Test</tittle>
	</head>
	
	<body>
		<h1>Hello World</h1>
	</body>
</html>
```

## Lists

There are two types of lists in markdown.

### Ordered Lists

To create an ordered list, the numbers dont need to be in order, but the list should start with the number one.

1. First
2. Second
3. Thirt
4. Fourth

### Unordered Lists

To start an unordered list, you can use characters like -, *, and +, but for compatibility, don't mix them in the same list.

- Item
- Item
- Item
- Item

## Images

To insert images in the Markdown file, we need to put \!\[\[path to image\]\], or we can use the image tag from HTML.

![[download.png]]

## Links

To add a link, we use \[google\]\(htttp://google.com\)

My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

## Tables

To create a table, use --- three or more hyphens to make each column header and | separate each column. We can do a different type of alignment inside of the table by adding a colon (:--- ) to align left, ( :---: ) to align center, and ( ---: ) to align right. 

| Right | Center | Left |
| :--- | :---: | ---: |
| Text | Text | Text |

## Task List 

We can add checklists easily, - [ ] to make an unchecked item, - [ X ] to add a checked item.

- [ ] First Item
- [ ] Second Item
- [X] Third Item 

## Heading IDs

We can set IDs to any heading for making links. \#\#\# Heading { #custom-id }.




