# Extension iframe bug

This extension demos a bug where injected iframes are not rendered.

Following steps will reproduce the issue:

1. Load the extensions
2. Go to http://www.example.com. You will find a green iframe that is added to the page
3. Click the www.example.com link in the iframe. This will open www.example.com in a new tab.

Now you can see that the iframe is added but not rendered. Even if the page is reloaded the iframe
will not render. However, switching to another tab and back to this tab will render the iframe.
