## dual-captions: YouTube add-on to show captions in 2 languages

![screenshot](https://github.com/mikesteele/dual-captions/blob/master/screenshot.gif)

### Intro

This project is not supported by Google and this software comes with no warranty.

As someone learning a foreign language, it is helpful for me to see both what the speaker is saying and the translation. As of July 2017, YouTube can only show captions in one language. 

This script creates a MutationObserver which waits for new caption elements to be added to the DOM. It then translates the text of these captions and adds the translated captions underneath.

### Roadmap

Open issues:

- The translation can come back too late and the caption has already been removed from the DOM. 
- Resizing the window adds duplicate caption elements to the DOM.

Future features:

- Add bookmarklet to allow for easier execution of the script.

### License

MIT