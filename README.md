# landscape_photo_guide

This repo contains an mdbook based landscape photography guide.

This repo is effectively read-only as it is currently being used as an example in
Prof. MacDonald's technical writing course at UofM-Dearborn.

## Building
To build the website on any platform on which Rust is avalible (windows 10, macos, and most linux distros):

1. Install [mdbook](https://rust-lang.github.io/mdBook/guide/installation.html).
2. Enter a terminal.
3. Run `git clone https://github.com/andyblarblar/landscape_photo_guide.git`.
4. Then `cd landscape_photo_guide`.
5. Finally`mdbook build`.
6. The website HTML is now in the 'book' directory.

## Editing
To work on the book yourself, first perform steps 1-4 in [Building](#Building). 
Next:

1. Open a terminal in the `landscape_photo_guide` directory.
2. `mdbook serve`. This will host a local web server serving the current version of the book.
3. Open a browser tab at the address printed in the terminal.
4. Now edit any of the book's pages in the `src` directory. When this file is saved, you should see the associated page update in the browser.
5. When done, kill the server with a ctrl-c in the terminal.  
