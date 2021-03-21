# The `<!DOCTYPE>` tag

## The standard
The [official and currently valid DOCTYPE standard](https://html.spec.whatwg.org/#the-doctype) says as following:

> A DOCTYPE must consist of the following components, in this order:
> 1. A string that is an ASCII case-insensitive match for the string "<!DOCTYPE".
> 2. One or more ASCII whitespace.
> 3. A string that is an ASCII case-insensitive match for the string "html".
> 4. Optionally, a DOCTYPE legacy string.
> 5. Zero or more ASCII whitespace.
> 6. A U+003E GREATER-THAN SIGN character (>).

in other words, a valid DOCTYPE is `<!DOCTYPE html>`. This declaration is **case insensitive** but internally, we agree that this is the right notation to use in our products.
We do not use any legacy string (described in component number 4), because we do not support any non html5-compatible HTML renderer. The legacy and limited systems as old browsers and email clients will be released later. By now, this is all we must know about the DOCTYPE tag. Just write it as exactly `<!DOCTYPE html>` and you will not have any problem.