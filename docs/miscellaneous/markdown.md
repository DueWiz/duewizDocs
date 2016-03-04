## Markdown Guide

Those md files in mkdocs will be compiled to html. There are some basic tutorials.

For inserting images or videos, take a look at the official guide.

### Heading tags
Basically, a `#` means h1 tag in html. So if you use `#` in front of a line of title, the title will be marked with h1 tag in html.

`##` for h2 and `###` for h3 etc..

### Links

Syntax for link is like

`[link name](href)`

For example,

Our github repo link is

`[https://github.com/DueWiz/Student_Organizer](https://github.com/DueWiz/Student_Organizer)`

### Code blocks

Use

<pre><code>&lt;pre&gt;&lt;code&gt;&lt;/code&gt;&lt;/pre&gt;</code></pre>

for code blocks.

To use inline block use ` `` ` which the quote mark is the key on left side of `1`

Remind that html literals should be used inside the code tag. So we need to change our original code html literals.

If you use atom, I have built a atom package wrapping the pre code tag for you.

[https://atom.io/packages/atom-code2html](https://atom.io/packages/atom-code2html)

The package name is `atom-code2html`
