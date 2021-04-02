# What is an HTML element?
An HTML document is made of HTML elements. And an HTML element is made of:
1. An opening [HTML tag](tags.md)
    - A less-than symbol (`<`)
    - The type of tag
    - An optional list of [attributes](attributes.md), each attribute being conformed by:
        - The attribute name
        - An optional value with the following notation:
            - An equals sign (`=`)
            - A value between double quotes (`"`)
    - A greater-than symbol (`>`)
2. An optional inner content, can be text or other elements
3. An optional closing HTML tag
    - A less-than symbol (`<`)
    - A slash (`/`)
    - The type of tag it is closing
    - A greater-than symbol (`>`)

Examples of completely valid HTML elements:
- `<br>` Element that only needs its opening tag
- `<input type="text" required name="username">` Element that only needs its opening tag including parameters, one of them does not need value
- `<script>alert('Hi');</script>` Element that needs opening and closing tags and has inner content
- `<span>Hi, brother</span>` an element with text inside
- `<html><head></head><body></body></html>` an element with other elements inside