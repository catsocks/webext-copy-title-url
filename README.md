# Firefox/Chrome extension: Copy page title (or selection) and URL to clipboard via context menu

This Firefox and Chrome extension adds two options to the context menu which allows you to copy the title and the URL of the current page to the clipboard, and a text selection and the URL, if there is text selected on the page.

This is useful when emailing/sharing links or collecting citations/quotes from the web.

It should serve as a basic replacement for the fantastic [QuoteURLText](https://addons.mozilla.org/en-US/firefox/addon/quoteurltext/) extension by Jay Palat, which had more functionality but is no longer supported by Firefox.

## Requirements

Firefox (Quantum) 57 or later / Chrome 63 or later.
Developed and tested in Firefox 58 and Chrome 63.

## Download

Download for Firefox:
https://addons.mozilla.org/en-US/firefox/addon/copy-page-title-and-url/

Download for Chrome:
https://chrome.google.com/webstore/detail/copy-page-title-and-url/mcnddmglmjbomnfgkehnnblncllkaedm

## How to use

With no text selected, right-click a page and the context menu option _Copy page title and URL_ will allow you to copy the title of the current page and the URL to the clipboard.

With a text selection, right-click a page and the context menu option _Copy selection and URL_ will allow you to copy the text selection and the URL to the clipboard, with the page title included before the selected text if the <kbd>Control</kbd> or <kbd>Shift</kbd> modifier key is pressed while clicking the option.

## Version history

1.3:
- Rewritten for compatibility with Chrome. Now the same code can be used to generate the extension for both browsers.
- Added support for Ctrl key in addition to Shift key (due to an apparent bug in Chrome, which modifies selection range on Shift+right click)

1.2:
- Initial release, Firefox only

## Author and links

Marek Jedliński
marek.jedlinski@gmail.com

github:
https://github.com/marekjedlinski/webext-copy-title-url

