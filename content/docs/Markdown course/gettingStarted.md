---
title: "Getting Started with Markdown"
description: " It covers the basics of Markdown syntax, best practices for writing clear and effective technical content, and tips for organizing and structuring your documents. Whether you're new to Markdown or looking to refine your skills, this guide will help you master the essentials and produce professional-quality documentation"
summary: " This detailed guide covers how to Set Up Markdown Tools, markdown basic syntaxes and Formatting and how to Structure Contents in Markdown."
date: 2024-07-01T07:07:07+01:00
lastmod: 2024-08-07T16:04:48+02:00
draft: false
menu:
  docs:
    parent: ""
    identifier: "introduction-6a1a6be4373e933280d78ea53de6158e"
weight: 2
toc: true
seo:
  title: " Getting Started with Markdown" # custom title (optional)
  description: It covers the basics of Markdown syntax, best practices for writing clear and effective technical content, and tips for organizing and structuring your documents. Whether you're new to Markdown or looking to refine your skills, this guide will help you master the essentials and produce professional-quality documentation # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  noindex: false # false (default) or true
---

<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-5378239849378753"
     crossorigin="anonymous"></script>

<ins class="adsbygoogle"
     style="display:block; text-align:center;"
     data-ad-layout="in-article"
     data-ad-format="fluid"
     data-ad-client="ca-pub-5378239849378753"
     data-ad-slot="8846640451"></ins>

<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>

From the previous lesson, you’ve learnt what Markdown is, its Importance, its advantages, and its comparisons to [WYSIWYG](https://en.wikipedia.org/wiki/WYSIWYG) Editors.

Here is saying “*The best way to learn is to practice*” This way you will be able to identify common errors and avoid them in your next project. In this lesson, you will be doing a lot of practicals and getting your hands dirty in markdown.

In the lesson, you will be learning:

- How to Set Up Markdown Tools.
- Markdown basic syntaxes and Formatting.
- How to Structure Contents in Markdown.

## Let's Get the ball Rolling.

You must have got used to downloading and installing packages before you can use certain tools or software on your computers. In this case, you won’t need that at all, as some applications already support writing in Markdown such as Code editors like [VScode](http://code.visualstudio.com) for `Read.md` **files, Blog sites like [Hashnode](http://hashnode.com), [Dev.to](http://dev.to), social apps like [Discord](http://discord.com), [Slack](http://slack.com), [Whatsapp](http://web.whatsapp.com) etc.

Aside from these, there are Markdown editors the same way there are Code editors. Markdown editors are **simple, lightweight tools for converting text to HTML. They can be used to format lists, headers, and importantly, to add images, videos, and links**.

In simple terms, these editors allow writers to create markdown documents like how code editors enable developers to write code. They use shorthand syntax to format text, which is then converted into a readable format.

Here are some Markdown editors you can use to try writing in Markdown:

1. [StackEdit](https://stackedit.io/)
2. [Dillinger](http://dillinger.io/)
3. [Typora](https://typora.io/)
4. [Markdown Journal](https://markdownjournal.com/)
5. [Dingus](http://daringfireball.net/projects/markdown/dingus)
6. [GhostWriter](https://wereturtle.github.io/ghostwriter/)
7. [Wri.pe](https://wri.pe/)

----------
## Setting Up Markdown Tools

For this lesson, you will be using StackEdit. StackEdit is a free online Markdown editor with a visual toolbar for formatting (bold, emphasis, lists, etc.). It can sync with cloud storage services such as Dropbox and Google Drive, and import files from a URL or your computer's hard drive.

1. Visit [StackEdit](https://stackedit.io/).
2. Click on `**Start Writing**` at the top of the page.

![start writing](https://paper-attachments.dropboxusercontent.com/s_700DE6F6C75E69B3D2CC7C7B9276E5C990376BF0759DB928E701B03B106CFA37_1722448619181_annotely_image.png)

You will see a welcome file that contains various Mardown syntax and its usage together with the Outcome on the right hand.

![welcome file](https://paper-attachments.dropboxusercontent.com/s_700DE6F6C75E69B3D2CC7C7B9276E5C990376BF0759DB928E701B03B106CFA37_1721998465426_Screenshot+2024-07-26+at+13.54.15.png)

3.Click on the Folder icon at the left side of the Nav bar.
![folder icon](https://paper-attachments.dropboxusercontent.com/s_700DE6F6C75E69B3D2CC7C7B9276E5C990376BF0759DB928E701B03B106CFA37_1721998655118_Screenshot+2024-07-26+at+13.57.21.png)

4.Create a New File or Folder depending on your choice and name it.
![create a new file or folder](https://paper-attachments.dropboxusercontent.com/s_700DE6F6C75E69B3D2CC7C7B9276E5C990376BF0759DB928E701B03B106CFA37_1723832455840_aaaa.png)

This is where You will be carrying out all your practicals.

----------
## Basic Syntax and Formatting

In this section, you will learn the basic syntax in Markdown

### 1. **Headers**

`#` is used to create a heading in Markdown. The number of # signs at the beginning of a line determines the heading level. For example, one # creates the largest heading, while six # creates the smallest.

 There are six levels of heading as seen below:

##### Syntax:

```markdown
# Heading One (H1)
## Heading Two (H2)
### Heading Three (H3)
#### Heading Four (H4)
##### Heading Five (H5)
###### Heading Six (H6)
```

##### Result:
# Heading One (H1)
## Heading Two (H2)
### Heading Three (H3)
#### Heading Four (H4)
##### Heading Five (H5)
###### Heading Six (H6)

> Take note of the space between the ‘#’ tag and the text or phrase
| Right ✅                                            | Result                                              | Wrong ❌                                       |
| -------------------------------------------------- | --------------------------------------------------- | --------------------------------------------- |
| ## Technical Writing                               | <h2>Technical Writing</h2>                          | ##Technical writing                           |
| ## Technical Writing<br><br>Technical Writing is … | <h2>Technical Writing</h2><br><br>Technical Writing is … | ##Technical Writing<br>Technical writing is … |

### 2.**Emphasis (Bold, Italics)**

You can add emphasis in markdown either as a **Bold text** or *Italic text*. This can be achieved using **asterisk(s).**

- **Bold:  U**se two asterisks before the text and after the text (**).

- I*talic*:  Use one asterisk or underscore before the text and after the text. (*/ _).

Check the usage ⬇️
##### Syntax:

``` markdown
**Bold text**
*Italic text*
```

##### Result:

**Bold text**
*Italic text*

### 3.**Lists (Ordered and Unordered)**

You can itemize as an Ordered or Unordered list.

#### - **Ordered**
Add numbers followed by content, as seen below ⬇️

| Syntax ✅                                                                 | Result ✅                                                                 |
| ------------------------------------------------------------------------ | ------------------------------------------------------------------------ |
| <pre>1. Writing<br>2. Documentation<br>3. Technical Writing<br>4. Training<br>&nbsp;&nbsp;&nbsp;&nbsp;1. Training 1<br>&nbsp;&nbsp;&nbsp;&nbsp;2. Training 2<br>&nbsp;&nbsp;&nbsp;&nbsp;3. Training 3<br>5. Troubleshooting</pre> | 1. Writing<br>2. Documentation<br>3. Technical Writing<br>4. Training<br>&nbsp;&nbsp;&nbsp;&nbsp;1. Training 1<br>&nbsp;&nbsp;&nbsp;&nbsp;2. Training 2<br>&nbsp;&nbsp;&nbsp;&nbsp;3. Training 3<br>5. Troubleshooting |

#### - **Unordered**
Add dashes (`-`), asterisks (`*`), or plus signs (`+`) in front as seen below ⬇️

##### Syntax:

``` markdown
- First item
- Second item
- Third item
  - Indented item
  - Indented item
    - Extra item
- Fourth ite
```

##### Result:

- First item
- Second item
- Third item
  - Indented item
  - Indented item
    - Extra item
- Fourth item

> Note: for nested listing either as an ordered or unordered list, maintain the same syntax and add extra spacing before nest items e.g Press the space bar four times before you begin the nest list

| Right ✅                                                                                                                                             | Wrong ❌                                                                                                                              |
| --------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| - First item<br>- Second item<br>- Third item<br>&nbsp;&nbsp;&nbsp;&nbsp;- Indented item<br>&nbsp;&nbsp;&nbsp;&nbsp;- Indented item<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Extra item<br>- Fourth item                | - First item<br>- Second item<br>- Third item<br>&nbsp;&nbsp;- Indented item<br>&nbsp;&nbsp;- Indented item<br>&nbsp;&nbsp;&nbsp;&nbsp;- Extra item<br>- Fourth item         |
| - First item<br>- Second item<br>- Third item<br>&nbsp;&nbsp;&nbsp;&nbsp;- Indented item<br>&nbsp;&nbsp;&nbsp;&nbsp;- Indented item<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Extra item<br>- Fourth item                | - First item<br>- Second item<br>- Third item<br>&nbsp;&nbsp;&nbsp;&nbsp;+ Indented item<br>&nbsp;&nbsp;&nbsp;&nbsp;* Indented item<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Extra item<br>- Fourth item |
| 1. First item<br>2. Second item<br>3. Third item<br>&nbsp;&nbsp;&nbsp;&nbsp;1. Indented item<br>&nbsp;&nbsp;&nbsp;&nbsp;2. Indented item<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1. Extra item<br>4. Fourth item | 1) First item<br>2) Second item<br>3) Third item<br>&nbsp;&nbsp;&nbsp;&nbsp;1) Indented item<br>&nbsp;&nbsp;&nbsp;&nbsp;2) Indented item<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1) Extra item<br>4) Fourth item |

### 4.**Links and Images**

- **Links:** To create a link, enclose the link text in brackets and then follow it immediately with the URL in parentheses e.g `[Google](https://www.google.com)`

 <u><b>The outcome is [Google](http://www.google.com)
</b></u>

- **Image:** To add an image, add an exclamation mark (`!`), followed by alt text in brackets, and the path or URL to the image asset in parentheses.

```markdown
![Stellar Bridge illustration\](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/x32gn1w21u095qfkw3ie.png 'stellar')
```

The output will look like this ⬇️

![Stellar Bridge illustration](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/x32gn1w21u095qfkw3ie.png)

## Structuring Content

In this section, you will learn how to structure your content in an organised and readable manner through **Headings** and **Subheadings**, **Tables** and **Blockquotes**.

### 1. **Headings and Subheadings**

This is an important aspect of structuring content in markdown. Headings and subheadings help the readers quickly scan the content, understand its structure, and easily locate specific information.

- **Ideally, H1 are best suitable for Title or Main Heading.** This is the most prominent heading level and should be used sparingly, typically once per page.

- **H2:** Used for primary section headings. These are subheadings under the main topic.
      - Example: Introduction, Methods, Results, Conclusion.

- **H3:** Used for subheadings within sections. They provide further structure and organization.
      - Example: Study Participants, Data Collection, Data Analysis

- **H4, H5, H6:** These lower-level headings can be used for smaller subsections or to emphasize specific points within the content.
      - Example: Demographics, Instrumentation, Statistical Analysis

##### Syntax

```markdown
# H1: Main Title or Page Heading

This is the most important heading on the page. It should clearly and concisely convey the main topic of the content.

## H2: Primary Section Heading

-   **Section 1**
-   **Section 2**
-   **Section 3**

### H3: Subheading within a Section

#### Section 1

-   Subtopic A
-   Subtopic B

#### Section 2

-   Subtopic C
-   Subtopic D

##### H5: Lower-level Heading (Optional)

This level of heading is used less frequently, but can be useful for providing additional structure within a subsection.

###### H6: Even Lower-level Headings (Rarely Used)

These headings are typically not necessary for most content, but can be used in very complex documents with multiple layers of organization.
```

##### Result⬇️

# H1: Main Title or Page Heading
This is the most important heading on the page. It should clearly and concisely convey the main topic of the content.

## H2: Primary Section Heading

- **Section 1**
- **Section 2**
- **Section 3**

### H3: Subheading within a Section

#### Section 1

- Subtopic A
- Subtopic B

#### Section 2

- Subtopic C
- Subtopic D

##### H5: Lower-level Heading (Optional)

This level of heading is used less frequently, but can be useful for providing additional structure within a subsection.

###### H6: Even Lower-level Headings (Rarely Used)

These headings are typically not necessary for most content, but can be used in very complex documents with multiple layers of organization.

### 2. **Creating Tables**

To create a table,

1. start by adding pipes `|` before and after the table heading to create rows.
2. use three or more hyphens (`---`) to create each column’s header.
3. use pipes (`|`) to separate each column.

For compatibility, you should also add a pipe on either end of the row.

4.Add the table data on a new line
> don’t add space between the column

##### Syntax

```markdown
| Frontend | Backend | Smart contract|
|---|---|---|
| Html | Python | Solidity |
| Css | Node.js | Rust |
| Javascript | PhP | Vyper |
```

##### Result

| Frontend | Backend | Smart contract|
|---|---|---|
| Html | Python | Solidity |
| Css | Node.js | Rust |
| Javascript | PhP | Vyper |

##### Comparison

```markdown
    Right ✅
    | Frontend | Backend | Smart contract|
    |:---|:---|:---|
    | Html | Python | Solidity |
    | Css | Node.js | Rust |
    | Javascript | PhP | Vyper |
```

```markdown
    Wrong ❌
    | Frontend | Backend | Smart contract|
    
    |:---|:---|:---|
    
    | Html | Python | Solidity |
    
    | Css | Node.js | Rust |
    
    | Javascript | PhP | Vyper |
```

#### **Alignment**

 You can align text in the columns to the left, right, or centre.

- **Right:** add `:`  the right side of the hyphens within the header row.
- **Left:**  add `:` to the left side of the hyphens within the header row.
- **Center:** add `:` on both sides of the hyphens within the header row.

##### Syntax For Center Alignment

```markdown
| Frontend | Backend | Smart contract|
|:---:|:---:|:---:|
| Html | Python | Solidity |
| Css | Node.js | Rust |
| Javascript | PhP | Vyper |
```

##### Result For Center Alignment
| Frontend | Backend | Smart contract|
|:---:|:---:|:---:|
| Html | Python | Solidity |
| Css | Node.js | Rust |
| Javascript | PhP | Vyper |

##### Syntax For Right Alignment

```markdown
| Frontend | Backend | Smart contract|
|---:|---:|---:|
| Html | Python | Solidity |
| Css | Node.js | Rust |
| Javascript | PhP | Vyper |
```

##### Result For Right Alignment
| Frontend | Backend | Smart contract|
|---:|---:|---:|
| Html | Python | Solidity |
| Css | Node.js | Rust |
| Javascript | PhP | Vyper |

##### Syntax For Left Alignment

```markdown
| Frontend | Backend | Smart contract|
|:---:|:---:|:---:|
| Html | Python | Solidity |
| Css | Node.js | Rust |
| Javascript | PhP | Vyper |
```

##### Result For Left Alignment
| Frontend | Backend | Smart contract|
|:---|:---|:---|
| Html | Python | Solidity |
| Css | Node.js | Rust |
| Javascript | PhP | Vyper |

### 3.**Using Blockquotes for Text Formatting**

Blockquotes are used to set off long quotations from other sources. To create a blockquote, add the **greater than sign** `>` in the font of the paragraph.

```markdown
> Here is saying  “_The_ _best way to learn is to practice_” This way you will be able to identify common errors and avoid them in your next project. 
```

For multiple paragraphs, add `>` before the next paragraph to create a space between them.

```markdown
> Here is saying  "_The_ _best way to learn is to practice_" This way you will be able to identify common errors and avoid them in your next project.
> 
> In simple terms, these editors allow writers to create markdown documents like how code editors enable developers to write code.
```

You can also create a nested blockquote by adding `>>` or more in front of the paragraph you want to nest.

```markdown
    > In this lesson, you will be doing a lot of practicals and getting your hands dirty in markdown.
    > > In the lesson, you will be learning:
    >> + How to Set Up Markdown Tools.
    >> + Markdown basic syntaxes and Formatting.
    >> + How to Structure Contents in Markdown.
         >>>+ kkkkkkkkkkkkk
         >>>>+ kkkkkkkkk
```

Check the output below ⬇️

> In this lesson, you will be doing a lot of practicals and getting your hands dirty in markdown.
>
> In the lesson, you will be learning:
>> - How to Set Up Markdown Tools.
>> - Markdown basic syntaxes and Formatting.
>> - How to Structure Contents in Markdown.
>>> - Additional nested item
>>>> - Further nested item

The best way to learn markdown is to use it at all times e.g. after this lesson, write an article in StackEdit.

See you in the next lesson.
