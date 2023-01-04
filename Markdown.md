# Markdown

## Contents

1. [What is Markdown](#what-is-markdown)
2. [Headings](#headings)
3. [Text Styling](#text-styling)
4. [Block quote](#block-quote)
5. [Code Blocks](#code-blocks)
6. [Lists](#lists)
   * [Ordered Lists](#ordered-lists)
   * [Unordered Lists](#unordered-lists)
7. [Images](#images)
8. [Links](#links)
9. [Tables](#tables)
10. [Task List](#task-list)
11. [Heading IDs](#heading-ids)

<div style="page-break-after: always;"></div>

## What is Markdown

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

| Character |      Style      |   Example    |
| :-------: | :-------------: | :----------: |
|    **     |      Bold       |   **Text**   |
|     *     |     Italic      |    *Text*    |
|    ***    | Bold and Italic | *** Text *** |
|    ~~     | Strike through  |   ~~Text~~   |
|    ==     |    Highlight    |   ==Text==   |

<div style="page-break-after: always;"></div>

## Block quote

If we need a block quote is very simple, we only need to add a > before the text. 

> A block quote example

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

<div style="page-break-after: always;"></div>

## Lists

There are two types of lists in markdown.

### Ordered Lists

To create an ordered list, the numbers don't need to be in order, but the list should start with the number one.

1. First
2. Second
3. Thirty
4. Fourth

### Unordered Lists

To start an unordered list, you can use characters like -, *, and +, but for compatibility, don't mix them in the same list.

- Item
- Item
- Item
- Item

<div style="page-break-after: always;"></div>

## Images

To insert images in the Markdown file, we need to put \!\[\[path to image\]\], or we can use the image tag from HTML and \!\[alt Text\]\(path or URL\).

![Penguin](https://upload.wikimedia.org/wikipedia/commons/thumb/5/55/Tux_Enhanced.svg/154px-Tux_Enhanced.svg.png)

## Links

To add a link, we use \[Google\]\(htttp://google.com\)

My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

## Tables

To create a table, use --- three or more hyphens to make each column header and | separate each column. We can do a different type of alignment inside of the table by adding a colon (:--- ) to align left, ( :---: ) to align center, and ( ---: ) to align right. 

| Right | Center | Left |
| :---- | :----: | ---: |
| Text  |  Text  | Text |

<div style="page-break-after: always;"></div>

## Task List 

We can add checklists easily, - [ ] to make an unchecked item, - [ X ] to add a checked item.

- [ ] First Item
- [ ] Second Item
- [x] Third Item 

## Heading IDs

We can set IDs to any heading for making links. \#\#\# Heading { #custom-id }.
