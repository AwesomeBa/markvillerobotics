Here are markdown guidelines specific to our website.

You start with a YAML front matter, which begins with three dashes "---"
There you can set variables, such as "layout:" and "title:"
We only use "layout:", "title:", "categories:" and "summary:"
End the front matter with another three dashes
Here is an example:

```
---
layout: post
title: How To Install ROBOTC
categories: resources
summary: "Click some buttons"
---
```

Also, there are only 3 categories: announcments, resources, and lessons. You can only use 1 of them in one post.

Then you write actual content. Markdown is nice and works like word in the sense that it keeps line breaks.

So if I write:
```
p
otato
```

It will come out as:
```
P
otato
```
To format italic, surround the italisized text with *
To format bold, surround the bolded text with **
To format underline, surround the underlined text with __
To create a link, first put the link text in square brackets, then put the link right after in parentheses.
For example: ```[this is a link](www.link.link.link.ca)```

To create a code-block, surround with three pointy things: \`\`\`
For example: 
> \`\`\`

> System.out.println("hi");

> \`\`\`

To create a syntax-highlighted code-block, add a language after the first set of pointy things.
For example: 
> \`\`\`java

> System.out.println("hi");

> \`\`\`

To format a header, add a number sign. Add more to make smaller headers:
```
# Header 1
## Header 2
### Header 3 
#### Header 4 
##### Header 5 
###### Header 6 
```
To format a list, use numbers and dots or dashes:
```
1. One
2. Two
- Dash
- Dash
```

To nest the list, add spaces to match the number of characters in the list:
```
1. one
2. two
   a. aye
```
