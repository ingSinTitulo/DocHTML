# HTML documents
A valid HTML document always starts with a `<!DOCTYPE>` tag, specifically with an `html` attribute without value and no more. Something like this: `<!DOCTYPE html>`.
Immediately after the `<!DOCTYPE>` tag must be an `<html>` with the `lang` attribute, more about this in the `<html>` element section element and can only be one `<html>` per document.
Inside the `<html>` element, must be a `<head>` element and a `<body>` element. One of each only.
Inside the `<head>` element, must be a `<meta>` element with an unique `charset` attribute specifying the encoding of the document, for us it will always be `UTF-8`. Also there must be only one `<title>` element specifying the title of the document.
In every tag documentation is specified if you can use an element made with that tag in the `<head>` element or in the `<body>` element or both.

The simplest valid HTML document for us is:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>HTML simplest document</title>
</head>
<body>
    
</body>
</html>
```