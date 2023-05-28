# The New Sanghelios Alliance Description

This git repository is dedicated to updating the description of the alliance page, and providing a central location for hosting the "true" version.

You can preview the current main branch version of the description [here](https://cikmo.github.io/Alliance-Page/alliance_preview_page.html).

## Instructions

To update the description, edit the file `description.html`.

The file `alliance_preview_page.html` is used to preview the actual look of the description on the alliance page. This file includes scripts and stylesheets that exist on the real politicsandwar page, to accurately preview the description. Opening just the `description.html` file will not show the description correctly.

To preview, you need to host a local web server. The easiest way to do this is to install the VSCode extension [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer). Once installed, right click on the `alliance_preview_page.html` file and select "Open with Live Server".

Using the Live Server extension, you can preview the description in real time as you edit it, no need to refresh the page.

## Upload to game
1. Remove extra spaces and newlines from the html. You may use https://codebeautify.org/remove-extra-spaces for this.
2. Disable javascript in your browser. To do this open dev tools, use `ctrl + shift + P`, and search for "javascript", and disable it.
3. Go to https://politicsandwar.com/alliance/edit/id=xxxxx, and simply paste in the de-whitespaced html.
