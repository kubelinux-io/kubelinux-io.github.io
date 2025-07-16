---
    title: Documentation Formatting
---

# Betterem Plugin

## Code
```markdown
This * won't emphasize *

This *will emphasize*

***I'm italic and bold* I am just bold.**

***I'm bold and italic!** I am just italic.*

*I'm italic. **I'm bold and italic.** I'm also just italic.*

___A lot of underscores____________is okay___

__This will all be bold __because of the placement of the center underscores.__

__This will all be bold __ because of the placement of the center underscores.__

__This will NOT all be bold__ because of the placement of the center underscores.__

__This will all be bold_ because of the token is less than that of the surrounding.__

*All will * be italic*

*All will *be italic*

*All will not* be italic*

*All will not ** be italic*

**All will * be bold**

**All will *be bold**

**All will not*** be bold**

**All will not *** be bold**
```

## Example
This * won't emphasize *

This *will emphasize*

***I'm italic and bold* I am just bold.**

***I'm bold and italic!** I am just italic.*

*I'm italic. **I'm bold and italic.** I'm also just italic.*

___A lot of underscores____________is okay___

__This will all be bold __because of the placement of the center underscores.__

__This will all be bold __ because of the placement of the center underscores.__

__This will NOT all be bold__ because of the placement of the center underscores.__

__This will all be bold_ because of the token is less than that of the surrounding.__

*All will * be italic*

*All will *be italic*

*All will not* be italic*

*All will not ** be italic*

**All will * be bold**

**All will *be bold**

**All will not*** be bold**

**All will not *** be bold**

# Caret

## Code
```markdown
^^Insert me^^

H^2^0

text^a\ superscript^
```

## Example
^^Insert me^^

H^2^0

text^a\ superscript^

# Critic

## Code
```markdown
Here is some {--*incorrect*--} Markdown.  I am adding this{++ here++}.  Here is some more {--text
 that I am removing--}text.  And here is even more {++text that I 
 am ++}adding.{~~

~>  ~~}Paragraph was deleted and replaced with some spaces.{~~  ~>

~~}Spaces were removed and a paragraph was added.

And here is a comment on {==some
 text==}{>>This works quite well. I just wanted to comment on it.<<}. Substitutions {~~is~>are~~} great!

General block handling.

{--

* test remove
* test remove
* test remove
    * test remove
* test remove

--}

{++

* test add
* test add
* test add
    * test add
* test add

++}
```

## Example
Here is some {--*incorrect*--} Markdown.  I am adding this{++ here++}.  Here is some more {--text
 that I am removing--}text.  And here is even more {++text that I 
 am ++}adding.{~~

~>  ~~}Paragraph was deleted and replaced with some spaces.{~~  ~>

~~}Spaces were removed and a paragraph was added.

And here is a comment on {==some
 text==}{>>This works quite well. I just wanted to comment on it.<<}. Substitutions {~~is~>are~~} great!

General block handling.

{--

* test remove
* test remove
* test remove
    * test remove
* test remove

--}

{++

* test add
* test add
* test add
    * test add
* test add

++}

# Details

## Code
```markdown
???+ note "Open styled details"

    ??? danger "Nested details!"
        And more content again.


??? success
   Content.

??? warning classes
   Content.
```

## Example
???+ note "Open styled details"

    ??? danger "Nested details!"
        And more content again.


??? success
   Content.

??? warning classes
   Content.

# Emojii

## Code
```markdown
:smile: :heart: :thumbsup:
```

## Example
:smile: :heart: :thumbsup:

# Highlight

## Code
```markdown
`#!php-inline $a = array("foo" => 0, "bar" => 1);`

Here is some code: `#!py3 import pymdownx; pymdownx.__version__`.

The mock shebang will be treated like text here: ` #!js var test = 0; `.
```

## Example
`#!php-inline $a = array("foo" => 0, "bar" => 1);`

Here is some code: `#!py3 import pymdownx; pymdownx.__version__`.

The mock shebang will be treated like text here: ` #!js var test = 0; `.