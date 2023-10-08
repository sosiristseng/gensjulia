# Basic markdown syntax
> The examples below were taken from [Grav Learn](https://github.com/getgrav/grav-learn).

## Headings

Headings from `h2` through `h6` are constructed with a `#` for each level:

## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading


## Comments

Comment below should **NOT** be seen:

<!--
This is a comment
-->

## Horizontal Rules

The HTML `<hr>` element is for creating a "thematic break" between paragraph-level elements. In markdown, you can create a `<hr>` with any of the following:

* `___`: three consecutive underscores
* `---`: three consecutive dashes
* `***`: three consecutive asterisks

renders to:

___

---

***

## Body Copy

Body copy written as normal, plain text will be wrapped with `<p></p>` tags in the rendered HTML.

So this body copy:

Lorem ipsum dolor sit amet, graecis denique ei vel, at duo primis mandamus. Et legere ocurreret pri, animal tacimates complectitur ad cum. Cu eum inermis inimicus efficiendi. Labore officiis his ex, soluta officiis concludaturque ei qui, vide sensibus vim ad.

A **line break** can be done with 2 spaces followed by 1 return.

## Inline HTML

You can simply use HTML tags:

Paragraph in Markdown.

<div class="class">
    This is <b>HTML</b>
</div>

Paragraph in Markdown.

## Emphasis

**bold text**.

_italicized text_.

~~Strike through this text.~~


## Blockquotes

For quoting blocks of content from another source within your document.

Add `>` before any text you want to quote.

> **Fusion Drive** combines a hard drive with a flash storage (solid-state drive) and presents it as a single logical volume with the space of both drives combined.
and this HTML:


Blockquotes can also be nested:

> Donec massa lacus, ultricies a ullamcorper in, fermentum sed augue.
Nunc augue augue, aliquam non hendrerit ac, commodo vel nisi.
>> Sed adipiscing elit vitae augue consectetur a gravida nunc vehicula. Donec auctor
odio non est accumsan facilisis. Aliquam id turpis in dolor tincidunt mollis ac eu diam.

## Lists

### Unordered Lists

A list of items in which the order of the items does not explicitly matter.

You may use any of the following symbols: `+`, `-`, `*` to denote bullets for each list item:

+ Lorem ipsum dolor sit amet
+ Consectetur adipiscing elit
+ Integer molestie lorem at massa
+ Facilisis in pretium nisl aliquet
+ Nulla volutpat aliquam velit
  - Phasellus iaculis neque
  - Purus sodales ultricies
  - Vestibulum laoreet porttitor sem
  - Ac tristique libero volutpat at
+ Faucibus porta lacus fringilla vel
+ Aenean sit amet erat nunc
+ Eget porttitor lorem


### Ordered Lists

**TIP**: If you just use `1.` for each number, Markdown will automatically number each item. For example:

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa
4. Facilisis in pretium nisl aliquet
5. Nulla volutpat aliquam velit
6. Faucibus porta lacus fringilla vel
7. Aenean sit amet erat nunc
8. Eget porttitor lorem

## Code

### Inline code

Wrap inline snippets of code with `` ` ``.

In this example, `<section></section>` should be wrapped with **code**.


### Block code "fences"

Use "fences"  ```` ``` ```` to block in multiple lines of code with a language attribute

``` julia
using Pkg
println("Hello, Julia.")
```

## Tables

Tables are created by adding pipes as dividers between each cell, and by adding a line of dashes (also separated by bars) beneath the header. Note that the pipes do not need to be vertically aligned.

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

### Right aligned text

Adding a colon on the right side of the dashes below any heading will right align text for that column.

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

!!! tip
    See also [tables generator](https://www.tablesgenerator.com/markdown_tables) to create Markdown tables.


## Links

### Basic link

[Assemble](https://assemble.io)

### Add a title

[Upstage](https://github.com/upstage/ "Visit Upstage!")

### Named Anchors

Named anchors enable you to jump to the specified anchor point on the same page. For example, each of these chapters:

**Table of contents**

  * [Chapter 1](#chapter-1)
  * [Chapter 2](#chapter-2)
  * [Chapter 3](#chapter-3)

**NOTE** that specific placement of the anchor tag seems to be arbitrary. They are placed inline here since it seems to be unobtrusive, and it works.

## Images

Images have a similar syntax to links but include a preceding exclamation point `!`.

![Minion](https://octodex.github.com/images/minion.png)

or:

![Alt text](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")

Like links, images also have a footnote style syntax:

![Alt text][id]

With a reference later in the document defining the URL location:

[id]: https://octodex.github.com/images/dojocat.jpg  "The Dojocat"


    [id]: https://octodex.github.com/images/dojocat.jpg  "The Dojocat"