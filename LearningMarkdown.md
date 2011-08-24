Emphasis: 

*emphasis*  **strong**

Escaping & and <: 

AT&T, 4 < 5

Titles:
	
# H1 title
## H2 title
### H3 title

Block quote:

> Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

Horizontal rule: 

---

Bullet list:

* Red
* Green
* Blue

Numbered list:

1.  This is a list item with two paragraphs. Lorem ipsum dolor
    sit amet, consectetuer adipiscing elit. Aliquam hendrerit
    mi posuere lectus.

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet
    vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
    sit amet velit.
	
2. This is the second list item

        code

Code:

    code
	
``` ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
		
Use the `printf()` function.

Links: 

This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.

Images:
    
![Alt text](http://www.google.com/logos/2011/granados11-hp.jpg)

![Alt text](http://www.google.com/logos/2011/granados11-hp.jpg "Optional title")

A HTML table:

<table>
    <tr>
        <td>Foo</td>
    </tr>
</table>
