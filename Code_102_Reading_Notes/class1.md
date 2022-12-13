# Class 1 reading files

Markdown is essentially HTML without the HTML. Markdown is an easy way to code a simple site with easy to read information. 

# PHILOSOPHY
Markdown is intended to be as easy-to-read and easy-to-write as is feasible.

Readability, however, is emphasized above all else. A Markdown-formatted document should be publishable as-is, as plain text, without looking like it’s been marked up with tags or formatting instructions. While Markdown’s syntax has been influenced by several existing text-to-HTML filters — including Setext, atx, Textile, reStructuredText, Grutatext, and EtText — the single biggest source of inspiration for Markdown’s syntax is the format of plain text email. 

To this end, Markdown’s syntax is comprised entirely of punctuation characters, which punctuation characters have been carefully chosen so as to look like what they mean. E.g., asterisks around a word actually look like *emphasis*. Markdown lists look like, well, lists. Even blockquotes look like quoted passages of text, assuming you’ve ever used email[^1]. 

# INLINE HTML

Markdown’s syntax is intended for one purpose: to be used as a format for writing for the web.

Markdown is not a replacement for HTML, or even close to it. Its syntax is very small, corresponding only to a very small subset of HTML tags. The idea is not to create a syntax that makes it easier to insert HTML tags. In my opinion, HTML tags are already easy to insert. The idea for Markdown is to make it easy to read, write, and edit prose. HTML is a publishing format; Markdown is a writing format. Thus, Markdown’s formatting syntax only addresses issues that can be conveyed in plain text.

For any markup that is not covered by Markdown’s syntax, you simply use HTML itself. There’s no need to preface it or delimit it to indicate that you’re switching from Markdown to HTML; you just use the tags[^2].

[^1]: [daringfireball](https://daringfireball.net/projects/markdown/syntax)  
[^2]: [daringfireball](https://daringfireball.net/projects/markdown/syntax)


## Markdown
| Syntax | Description |
| ----------- | ----------- |
|Heading|	# H1 ## H2 ### H3 |
|Bold|	** bold text ** |
|Italic|	* italicized text * |
|Blockquote|	> blockquote |
|Ordered List|	1. First item 2. Second item 3. Third item |
|Unordered List|	- First item - Second item - Third item |
|Code|\`code`|
|Horizontal Rule|	--- |
|Link|	[title] (https://www.example.com) |
|Image|	![alt text] (image.jpg) |

## Things I want to know more about
