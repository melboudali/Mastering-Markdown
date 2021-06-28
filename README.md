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
#### Italic (*, _):
*This is an italic paragraph. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Modi, illum.*

_This is an italic paragraph. Lorem ipsum dolor sit amet, consectetur adipisicing elit. Modi, illum._

#### Bold (**, __):
**This is a bold paragraph. Lorem ipsum, dolor sit amet consectetur adipisicing elit. At, voluptatem!**

__This is a bold paragraph. Lorem ipsum, dolor sit amet consectetur adipisicing elit. At, voluptatem!__

#### Blod & Italic p (_**, ***, ___):
_**This is bold and italic paragraph. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugit, mollitia.**_

***This is bold and italic paragraph. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugit, mollitia.***

___This is bold and italic paragraph. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Fugit, mollitia.___

_You **can** combine them_

### Strikethrough (~~):
~~this is a Strikethrough paragraph. Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus, mollitia?~~

# Headings
<!-- H1 -->
# h1
<!-- the other way -->
h1
=
<!-- H2 -->
## h2
<!-- the other way -->
h2
-
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
[Markdown][2] is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *.

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
[![][smallImage]][bigImage]
<!-- we can also use img tag -->
[<img src="https://images.unsplash.com/photo-1587868579905-3c9800e065da?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=400&q=80">](https://images.unsplash.com/photo-1587868579905-3c9800e065da?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=667&q=80)

# Lists
### unordered list (ul):
#### **fruits**:
<!-- we can use * or + or - -->
* Apple
* Banana
* Orange
+ Blueberry
+ Grapes
+ Lychee
- Mulberry
- Peach
- Pineapple 

### ordered list (ol):
#### **How To Make Awesome Pizza at Home**;
1. Make your own pizza dough.
2. Keep the sauce and toppings simple.
3. Bake it hot.
<!-- or best choice without md plugin-->
1. Make your own pizza dough.
1. Keep the sauce and toppings simple.
1. Bake it hot.
   
### nested list:
* **fruits**:
  * Apple
    + Blueberry
      - Grapes
  * Banana
  * Orange
* **vegetables**:
  + Spinach
    - Garlic
  + Carrots
    - Kale
      * Ginger
  + Broccoli
  
#### **How To Make Awesome Pizza at Home**;
1. Make your own pizza dough.
   * How To Make the Best Basic Pizza Dough
   * Homemade Thin-Crust Pizza
   * Quick No-Rise Pizza Dough
   * The Best Pizza Dough for Grilling
2. Keep the sauce and toppings simple.
   * How To Make Homemade Pizza Sauce
   * How To Make the Best Pesto: The Easiest, Simplest Method

<!-- Link can be at the end of the file -->
[1]: https://guides.github.com/features/mastering-markdown/#what
[2]: https://guides.github.com/features/mastering-markdown/
[github]: https://GitHub.com
<!-- images links -->
[first-image]: https://images.unsplash.com/photo-1493841160601-33a4807cb6de?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=889&q=80
[smallImage]:https://images.unsplash.com/photo-1487452066049-a710f7296400?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=200&q=80
[bigImage]: https://images.unsplash.com/photo-1487452066049-a710f7296400?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=751&q=80