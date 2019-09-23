# Common Fund Data Ecosystem Markdown help

This style guide is intended to help contributors to the CFDE
website ([nih-cfde/public-site-mockups](https://github.com/nih-cfde/public-site-mockups))
repository, to correctly format their Markdown files fast incorporation into the
webpage.

## What is Markdown? What is Github-Flavored Markdown?

Markdown is an agreed-upon standard for indicating document formatting
using plain text symbols. Common document features like headers, links,
bullet lists, and formatted text can be added to plain text documents,
and conveniently converted to HTML or other formats.

[Github-flavored
Markdown](https://guides.github.com/features/mastering-markdown/) is a
particular *flavor* of Markdown that offers additional features for
convenience. For example, if a link like `https://example.com` is
contained in the text of the document, Markdown will not recognize that
text as a link; Markdown will only recognize a link if it is surrounded
by angle brackets, like `<https://example.com>`. Github-flavored
Markdown will detect it as a link automatically, however, and will
render it as a link when the Markdown file is viewed on Github.

The site uses Markdown, not Github-flavored Markdown. While
Github-flavored Markdown is convenient because you can be less careful,
it's good to get into the habit of writing Markdown that's universally
valid.

## Text Formatting

To format text, make it `*bold*` or `_italicized_`.

Text that is `*bold*` will be *bold*, and text that is `_italicized_`
will be *italicized*.

### More Exotic Text Formatting

Regular Markdown does not natively support any text formatting besides
bold and italic text. Github Flavored Markdown does support more
formatting markup, but to make your text formatting work when rendered
as an HTML website, you may need to use raw HTML.

To underline text, use the HTML tags for underlining text: `<u>Underline
This!</u>` becomes <u>Underline This\!</u>

You can also create strikethrough text (text with a line through it)
using the HTML tags for strikethrough text: `<s>Hey, forget about
it!</s>` becomes <s>Hey, forget about it\!</s>

## Line Breaks

Markdown only recognizes a new line as a line break on the page if there
are two line breaks, one after the other:

    All of the text
    in this block will
    be rendered as one
    single sentence
    on a single line.
    
    The text in this block
    will be rendered as another
    separate sentence on its own
    second line.

## Links

If you copy-and-paste a link into your Markdown document, it should be
surrounded with angular brackets `<>` to turn them into an active link:

    Use <http://example.com>, not http://example.com

If you want to set the link text, use the link syntax of square brackets
and parentheses:

    [link text](http://example.com)

To create a link to an email address, prefix it with `mailto:`, like
this:

    [send an email](mailto:admin@example.com)

## Lists

Make a list with asterisks:

    * simple
    * little
    * list

Looks like:

  - simple
  - little
  - list

When creating lists, include one empty line between the text and the
start of the list. For example:

    This list is going to turn out nicely:
    
    * Start a line with a star
    * Make things up as you go
    * If you have a line that gets really long,
      you can always continue it on the next line - 
      just include some space so you don't confuse
      the Markdown parser.

If you don't include a space, the entire list will run together and the
asterisks will be interpreted as text, so your \* list \* will \* look
\* like \* this.

If you see that on a page, you can fix it by adding a space between the
paragraph and the start of the list\!

You can also use dashes:

    This works nicely too:
    
    - Start with a dash
    - Add more things
    - Who knows where you'll end up

You can also create numbered lists. Conveniently, Markdown does not
actually use the numbers you specify, so you can number every item as 1
and markdown will correctly enumerate your items.

For example:

    Here is a numbered list example:
    
    1. Put your right foot in
    1. Take your right foot out
    1. Put your right foot in
    1. Shake your right foot all about
    1. Do the Hokey Pokey
    1. Turn yourself around

1.  If you forget an item in your list
2.  you can add items in later
3.  that way you don't have to renumber every item

## Checklists

Github-flavored Markdown (mentioned above) makes it possible to add
checkbox elements to documents by using a special list syntax:

    On Github, this would make a checklist with one checked item:
    
    - [x] Check trash compactor for escapees
    - [ ] Fire superlaser at Alderaan
    - [ ] Fire Stormtrooper TK-421

Unfortunately, this feature is not part of the universal Markdown
standard, so it only works on Github and does not work on the internal
website. The list is rendered correctly, but the list items are
prepended with literal `[ ]` or `[x]` text.

You can still use this syntax (we encourage you to do so\!) but know
that it will not render as checkboxes on the internal website.

## Images and Videos

If you need to add an image to the internal website, you should add
images to the `images/` directory of the respective submodule. (If there
is no `images/` directory in the submodule, create it or open file an
issue.)

Literal HTML can usually be copied and pasted directly into Markdown and
render correctly. Embedding Vimeo videos should be as simple as copying
the HTML embed code provided by Vimeo and pasting it into your Markdown
file in the appropriate location.

Include one blank line before and after the HTML.

## Headers

You can create headers at a maximum of 6 levels in the document, by
using the hash sign, a space, and the name of the header:

    # Top Level Header
    
    Include a blank line between
    the header and the text.
    
    ## Second Level Header
    
    Lorem ipsum something.

## Quotes

You can indent a quote by prefixing it with an angular bracket `>`:

    The original RFC document states:
    
    > Cut the green one.
    
    But the second draft states:
    
    > Definitely do not cut the green
    > one, that would be a very bad
    > idea.

When rendered, it looks like this:

> Definitely do not cut the green one, that would be a very bad idea.

## Indentation

You should not indent text in Markdown files, as this will cause the
text to be interpreted as code.

## Code

To include code or plain, unformatted text in a document, surround it
with three backtick symbols. Include a blank line above and below it.
For example:

```` 

    Once you have hacked the Gibson and taken control
    of the mainfrme, execute the commands to wipe the
    hard drives:

    ```
    wipe_drives()
    cover_tracks()
    ```

    Then go make yourself a sandwich.

````

## Emojis

Emojis are a feature that is only supported by Github-flavored Markdown.
You can add emoji like :camel: or :octopus: and it will be rendered on
Github Markdown pages, but not on the website.

So, don't use too many :sparkles: in your content\!
