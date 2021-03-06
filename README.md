<!-- This is a comment -->

# Mastering-Markdown

Mastering Markdown w/ wesbos

<!-- Pargraph -->

## Paragraphs

### Single line p:

This is a paragraph in one line.
Lorem ipsum dolor sit amet consectetur adipisicing elit. Esse, beatae.

<!-- Paragraph with line break -->

### Multi line p:

This is a paragraph with line break.

Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia, sed.

<!-- Bold and Italic -->

### Bold & Italic:

#### Italic (\*, \_):

_This is an italic paragraph. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Modi, illum._

_This is an italic paragraph. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Modi, illum._

#### Bold (\*\*, \_\_):

**This is a bold paragraph. Lorem ipsum, dolor sit amet consectetur adipisicing elit. At, voluptatem!**

**This is a bold paragraph. Lorem ipsum, dolor sit amet consectetur adipisicing elit. At, voluptatem!**

#### Blod & Italic p (\_**, \***, \_\_\_):

_**This is bold and italic paragraph. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugit, mollitia.**_

**_This is bold and italic paragraph. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugit, mollitia._**

**_This is bold and italic paragraph. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugit, mollitia._**

_You **can** combine them_

### Strikethrough (~~):

~~this is a Strikethrough paragraph. Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus, mollitia?~~

# Headings

<!-- H1 -->

# h1

<!-- the other way -->

# h1

<!-- H2 -->

## h2

<!-- the other way -->

## h2

<!-- h3 -->

### h3

<!-- h4 -->

#### h4

# links

### normal link:

<http://elboudali.com>

### link some text:

[This is my website.](https://elboudali.com)

### link with title:

[This is my github.](https://github.com/melboudali "This is where you can find all my projects.")

### link with key:

<!-- if we have lonk link that will make out text hard to read.-->

make sute to visit this [link][1] for more informations.

_**Example:**_

<!-- we can use number or text -->

[Markdown][2] is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or \*.

[GitHub][github] uses its own version of the [Markdown][2] syntax that provides an additional set of useful features, many of which make it easier to work with content on [GitHub][github].

# Images

### normal image:

<!-- alt text for search engines and screen readers (you can leave it empty)-->

![alt text](https://images.unsplash.com/photo-1523554888454-84137e72c3ce?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80)

### image with tooltip/title:

![V](https://images.unsplash.com/photo-1490535004195-099bc723fa1f?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=880&q=80 "V")

### image with key:

![Bearded man portrait and lamp][first-image]

### image inside link:

<!-- show small image but link to a bigger image -->

[![](https://images.unsplash.com/photo-1598775764807-f8ea9b3b3966?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=200&q=80)](https://images.unsplash.com/photo-1598775764807-f8ea9b3b3966?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80)
[![][smallimage]][bigimage]

<!-- we can also use img tag -->

[<img src="https://images.unsplash.com/photo-1587868579905-3c9800e065da?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=400&q=80">](https://images.unsplash.com/photo-1587868579905-3c9800e065da?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=667&q=80)

# Lists

### unordered list (ul):

#### **fruits**:

<!-- we can use * or + or - -->

- Apple
- Banana
- Orange

* Blueberry
* Grapes
* Lychee

- Mulberry
- Peach
- Pineapple

### ordered list (ol):

#### **How To Make Awesome Pizza at Home**;

1. Make your own pizza dough.
2. Keep the sauce and toppings simple.
3. Bake it hot.
<!-- or best choice without md plugin-->
4. Make your own pizza dough.
5. Keep the sauce and toppings simple.
6. Bake it hot.

### nested list:

- **fruits**:
  - Apple
    - Blueberry
      - Grapes
  - Banana
  - Orange
- **vegetables**:
  - Spinach
    - Garlic
  - Carrots
    - Kale
      - Ginger
  - Broccoli

#### **How To Make Awesome Pizza at Home**:

1. Make your own pizza dough.
   - How To Make the Best Basic Pizza Dough
   - Homemade Thin-Crust Pizza
   - Quick No-Rise Pizza Dough
   - The Best Pizza Dough for Grilling
2. Keep the sauce and toppings simple.
   - How To Make Homemade Pizza Sauce
   - How To Make the Best Pesto: The Easiest, Simplest Method

#### **Example**:

1. First Article:

   - Title:

     Lorem ipsum dolor sit amet.

   - Image:

     ![V](https://images.unsplash.com/photo-1490535004195-099bc723fa1f?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=880&q=80 "V")

   - Body:

     Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti laudantium id temporibus, rerum dolore aliquid enim sequi voluptas repellat cum! Doloremque blanditiis est omnis dolorem sequi similique, corporis atque officia? Molestiae est unde ad dignissimos omnis odio aliquid, sit debitis.

     Lorem ipsum dolor sit amet consectetur, adipisicing elit. Atque, dolore! Magnam doloremque dolor eveniet illum, itaque obcaecati praesentium beatae animi aut earum nostrum dolorum dolorem ratione sapiente cumque totam quas saepe voluptatum repellat, a ad? Pariatur placeat rem laborum dolore enim nobis, ullam, sit, eveniet aspernatur minima doloribus nisi! Culpa?

   - Links:
     1. [Github][github].
     2. [My Website](elboudali.com).
        - [Home](elboudali.com)
        - [Blog](elboudali.com/blog)
        - [Projects](elboudali.com/projects)
          - [Instagram Clone](instagram.elboudali.com)
        - [Contact](elboudali.com/contact)

# Line Breaks

### full line break

**empty line**:

line 1

line 2

**br tag**:
<br>line 1
<br>line2

# Horizontal Rules

<!-- 3 - or _, need line break before hr-->

Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sed, tempora?

---

---

# Block Quotes

> "The way to get started is to quit talking and begin doing."
>
> -_**Walt Disney**_

# Code Blocks

## inline code blocks

Hey, did you try `const x = y + 1;`?

## Git diff

```diff
-const x = y + 50;
+const x = y - 50;
```

## full code blocks

<!-- you can choose lang ex: js or javascript -->

### JavaScript

```js
const a = Math.floor(Math.random() * (10 - 1)) + 1;
console.log(`Random value between 1 and 10 is ${a}`);
```

### CSS

```css
* {
	box-sizing: border-box;
	margin: 0;
	padding: 0;
}

html {
	position: relative;
	overflow-y: auto;
}

body {
	font-size: 1rem;
	line-height: normal;
	font-weight: 400;
}

a,
a:visited {
	text-decoration: none;
}

button {
	border: none;
	outline: none;
	background: none;
	cursor: pointer;
}
```

### HTML

```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0" />
		<title>React Doc</title>
		<link rel="stylesheet" href="style.css" />
	</head>
	<body>
		<header id="header-container">
			<div id="logo">
				<img
					src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9Ii0xMS41IC0xMC4yMzE3NCAyMyAyMC40NjM0OCI+CiAgPHRpdGxlPlJlYWN0IExvZ288L3RpdGxlPgogIDxjaXJjbGUgY3g9IjAiIGN5PSIwIiByPSIyLjA1IiBmaWxsPSIjNjFkYWZiIi8+CiAgPGcgc3Ryb2tlPSIjNjFkYWZiIiBzdHJva2Utd2lkdGg9IjEiIGZpbGw9Im5vbmUiPgogICAgPGVsbGlwc2Ugcng9IjExIiByeT0iNC4yIi8+CiAgICA8ZWxsaXBzZSByeD0iMTEiIHJ5PSI0LjIiIHRyYW5zZm9ybT0icm90YXRlKDYwKSIvPgogICAgPGVsbGlwc2Ugcng9IjExIiByeT0iNC4yIiB0cmFuc2Zvcm09InJvdGF0ZSgxMjApIi8+CiAgPC9nPgo8L3N2Zz4K"
					alt="React Logo"
				/>
				<h1>React</h1>
			</div>
			<button id="hamberger-menu">
				<svg viewBox="0 0 100 80" width="40" height="40">
					<rect width="100" height="20"></rect>
					<rect y="30" width="100" height="20"></rect>
					<rect y="60" width="100" height="20"></rect>
				</svg>
			</button>
		</header>
		<nav id="navbar">
			<header>
				<h1 id="menu-title">Main Concepts</h1>
			</header>
			<a href="#hello_world" class="nav-link">Hello World</a>
			<a href="#introducing_jsx" class="nav-link">Introducing JSX</a>
			<a href="#rendering_elements" class="nav-link">Rendering Elements</a>
			<a href="#components_and_props" class="nav-link">Components and Props</a>
			<a href="#state_and_lifecycle" class="nav-link">State and Lifecycle</a>
			<a href="#composition_vs_inheritance" class="nav-link">Composition vs Inheritance</a>
		</nav>

		<main id="main-doc">
			<section class="main-section" id="hello_world">
				<header>
					<h1>Hello World</h1>
				</header>
				<p class="sub-title">The smallest React example looks like this:</p>
				<code>
					ReactDOM<span class="function-name">.render</span><span class="other">(</span>
					<br />
					<span class="other margin-left-20"><</span><span class="html-element">h1</span><span class="other">></span>Hello, world!<span
						class="other"
						><</span
					><span class="other">/</span><span class="html-element">h1</span><span class="other">>,<br /></span
					><span class="margin-left-20">document</span><span class="function-name">.getElementById</span><span class="other">(</span
					><span class="arg">'root'</span><span class="other">)</span><br /><span class="other">);</span></code
				>
				<p>It displays a heading saying ???Hello, world!??? on the page.</p>
				<a class="codepen-anchor" target="_blank" href="https://reactjs.org/redirect-to-codepen/hello-world">Try it on CodePen</a>
				<p>
					Click the link above to open an online editor. Feel free to make some changes, and see how they affect the output. Most pages in this
					guide will have editable examples like this one.
				</p>
				<hr />
				<h2 class="read-more">Read More:</h2>
				<ul>
					<li>
						<a target="_blank" href="https://reactjs.org/docs/hello-world.html#how-to-read-this-guide">How to Read This Guide</a>
					</li>
					<li>
						<a target="_blank" href="https://reactjs.org/docs/hello-world.html#knowledge-level-assumptions">Knowledge Level Assumptions</a>
					</li>
				</ul>
			</section>
		</main>
	</body>
</html>
```

**Example**

Change md preview background from Dark to light on vscode

1. go to Pereferences > Settings
2. Search for **markdow style**
3. add

```json
https://cdn.jsdelivr.net/gh/dhdhagar/vscode-md-preview-light/style.min.css
```

**or**

- In **VSCode**, just edit the **Markdown: Styles** configuration or add the following line to `settings.json`

```json
"markdown.styles": ["https://cdn.jsdelivr.net/gh/dhdhagar/vscode-md-preview-light/style.min.css"]
```

# Tables

### table text deriections:

| value | direction |
| :---- | :-------- |
| :---- | Left      |
| :---: | Center    |
| ----: | Right     |

**Align Center**:

|          key           |         value          |
| :--------------------: | :--------------------: |
| Lorem ipsum dolor sit. | Lorem ipsum dolor sit. |

**Align Left**:

| key                    | value                  |
| :--------------------- | :--------------------- |
| Lorem ipsum dolor sit. | Lorem ipsum dolor sit. |

**Align Right**:

|                    key |                  value |
| ---------------------: | ---------------------: |
| Lorem ipsum dolor sit. | Lorem ipsum dolor sit. |

**Example**:

Markdown All in One Keyboard Shortcuts:

| Key              | Command                      |
| :--------------- | :--------------------------- |
| Ctrl + B         | Toggle bold                  |
| Ctrl + I         | Toggle italic                |
| Ctrl + Shift + ] | Toggle heading (uplevel)     |
| Ctrl + Shift + [ | Toggle heading (downlevel)   |
| Ctrl + M         | Toggle math environment      |
| Alt + C          | Check/Uncheck task list item |
| Ctrl + Shift + V | Toggle preview               |
| Ctrl + K V       | Toggle preview to side       |

# Checkbox

**Shopping List**:

- [x] Apples
- [ ] Bananas
- [ ] Bread
- [x] Muffins

# Directory & file structures

```
project
???   README.md
???   file001.txt
???
????????????folder1
???   ???   file011.txt
???   ???   file012.txt
???   ???
???   ????????????subfolder1
???       ???   file111.txt
???       ???   file112.txt
???       ???   ...
???
????????????folder2
    ???   file021.txt
    ???   file022.txt
```

**Other example**

_**???? What's inside?**_

A quick look at the top-level files and directories you'll see in a Gatsby project.

    .
    ????????? node_modules
    ????????? src
    ????????? .gitignore
    ????????? .prettierrc
    ????????? gatsby-browser.js
    ????????? gatsby-config.js
    ????????? gatsby-node.js
    ????????? gatsby-ssr.js
    ????????? LICENSE
    ????????? package-lock.json
    ????????? package.json
    ????????? README.md

<!-- Link can be at the end of the file -->

[1]: https://guides.github.com/features/mastering-markdown/#what
[2]: https://guides.github.com/features/mastering-markdown/
[github]: https://GitHub.com

<!-- images links -->

[first-image]: https://images.unsplash.com/photo-1493841160601-33a4807cb6de?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=889&q=80
[smallimage]: https://images.unsplash.com/photo-1487452066049-a710f7296400?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=200&q=80
[bigimage]: https://images.unsplash.com/photo-1487452066049-a710f7296400?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=751&q=80
