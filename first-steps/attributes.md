# What is an HTML attribute?
This: `attribute="value"`, and its description goes like this:

An extra configuration for an element that changes the final behaviour of the element it is in.

## The parts of an attribute
1. An attribute name
2. An optional value with the following notation:
    - an equals sign (`=`)
    - an attribute value between double quotes (`"`). Yes, always double quotes. That is the standard in our products

A common attribute is something like this `name="userMail"`. In this case it is an attribute called name which is equals to userMail.

## Attributes in an HTML element
HTML elements can be created without attributes at all like this fictional element: `<element></element>`. Also can contain one attribute like `<element attribute="value"></value>` or multiple attributes like `<element attribute1="value1" attribute2="attribute2" [more attributes] attributen="valuen"></element>`.

## Attributes without a value
There are some attributes that do not need an explicit value to work, because any empty attribute will be evaluated by the renderer as having the value `"true"`. A real example of this is the `required` attribute, which will not let the user leave an input to be empty. It look like this: `<input type="text" required>`. And yes, attributes with and without a value can be mixed and be arranged in any way. Here an example: `<element attribute1="value1" attribute2 attribute3="value3" attribute4></element>`