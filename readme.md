# Gimli – Your Minimalist Startpage for your Server

![[Pasted image 20221016193651.png]]
## Description
Gimli is a static, minimal startpage for your homeserver. It's generated through [Jekyll](https://jekyllrb.com/). It's thoughtfully designed and easy to set-up.

## Features and Customisability
- Static HTML and CSS (no need for databases)
- Easily find your bookmark by pressing '/', then hit 'enter' to open it
- Bookmarks show in a responsive grid
- Easily set icons with your bookmarks (Google's Material Symbols)
- Set your own background image
- Change the hue (colours) of the page
- Automatic light and dark theme switching

## Setup
1. Install all of [Jekyll's prerequisites](https://jekyllrb.com/docs/installation/). 
2. Copy Gimli's repository to your local machine.
3. Change directory to Gimli's
4. Install the Jekyll and bundler [gems](https://jekyllrb.com/docs/ruby-101/#gems).
5. Modify \_config.yml to your liking (maybe experiment with the \_sass files too)
6. Enter the command ```jekyll build``` to build \_site.
7. Host those static pages somewhere (on your server?)

## Future ideas
- Use Docker to setup a lightweight HTTP server for an easy install on our homelabs
- Weather widget
- Time and date
- Simpler website quick bookmarks
- Better mobile support for the filter