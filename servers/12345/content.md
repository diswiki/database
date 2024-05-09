# Markdown syntax guide, thanks markdownlivepreview.com

## Headers

# This is a Heading h1
This is normal text.
## This is a Heading h2
*This is italic text.*
###### This is a Heading h6
**This is bold text.**

## Emphasis

*This text will be italic*  
_This will also be italic_

**This text will be bold**  
__This will also be bold__

_You **can** combine them_

## Lists

### Unordered

* Item 1
* Item 2
* Item 2a
* Item 2b

### Ordered

1. Item 1
2. Item 2
3. Item 3
    1. Item 3a
    2. Item 3b

## Images

![This is an alt text.](https://raw.githubusercontent.com/diswiki/resources/main/assets/loading.gif "This is a native markdown sample image.")

## Links

You may be using [Markdown Live Preview](https://markdownlivepreview.com/).

## Blockquotes

> Markdown is a lightweight markup language with plain-text-formatting syntax, created in 2004 by John Gruber with Aaron Swartz.
>
>> Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.

## Tables

| Left columns  | Right columns |
| ------------- |:-------------:|
| left foo      | right foo     |
| left bar      | right bar     |
| left baz      | right baz     |

## Blocks of code

```
let message = 'Hello world';
alert(message);
```

## Inline code

This web site is using `markedjs/marked`.

# DisWiki implementations
<br/>

### Image
Custom image implementation sample: <br/>
<wiki-image file="terry-davis-wobble.gif" placement="break" size="200">Terry A. Davis got them moves!</wiki-image>
<br/>

### Users and Channels
**User:** <wiki-user>username</wiki-user> <br/>
**Channel:** <wiki-channel>channel-name</wiki-channel>
<br/>

### HTML Table
<table>
    <tr>
        <th><wiki-user>Yendy</wiki-user></th>
        <td>Server Owner</td>
    </tr>
    <tr>
        <th><wiki-user>Maximum Trollage</wiki-user></th>
        <td>Admin</td>
    </tr>
    <tr>
        <th><wiki-user>Jarvis</wiki-user></th>
        <td>MVP</td>
    </tr>
</table>
<br/>

### Markdown Table
| User    | Desc. |
| -------- | ------- |
| <wiki-user>Yendy</wiki-user>  | Server Owner    |
| <wiki-user>Maximum Trollage</wiki-user> | Admin  |
| <wiki-user>Jarvis</wiki-user>    | MVP    |

<br/>
<br/>
**With breaks:** <br/>
| User    | Desc. | <br/>
| -------- | ------- | <br/>
| <wiki-user>Yendy</wiki-user>  | Server Owner    | <br/>
| <wiki-user>Maximum Trollage</wiki-user> | Admin  | <br/>
| <wiki-user>Jarvis</wiki-user>    | MVP    |
