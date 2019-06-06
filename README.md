This is a fork of [html-to-text](https://www.npmjs.com/package/html-to-text)

Only change is that you can now add ```ignoreSub``` and ```ignoreSup``` to the options object to ignore ```<sup></sup>``` and ```<sub></sub>``` tags.

**Example**
```var plainText = htmlToText.fromString(text, {
      wordwrap: 130,
      ignoreHref: true,
      ignoreImage: true,
      ignoreSub: true,
      ignoreSup: true,
    });
```
