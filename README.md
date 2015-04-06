# What is _md.js_?

_md.js_ is a JavaScript file using jQuery and pagedown to provide a simple and
clean solution for serving good looking websites.

# Why should I use _md.js_?

_md.js_'s **only** goal is to make a website readable without JavaScript.

A side-effect is that you can write beatiful websites using Markdown.

## And what happens if I use it?

Using _md.js_ has a few effects:

* a user browsing your website with a non-JS browser thinks something like

> Hey, they take care of my browser. I like them!

Note that people using either _links_, _lynx_, _NoScript_ or _NotScript_ are
usually people who can read Markdown.

* you can write a website quite quick and easy
* you do not need to worry about HTML anymore
* the sites get more small due to the missing HTML overhead

The scripts are quite small if minified so if you have much HTML it might be
worth a try. This is because the HTML is generated client-side.

* the client's browser will need to parse and convert the Markdown

Not a great disadvantage due to the fact that the rendering is way more
CPU-intensive.

**More information on everything can be found in the demo.**

# So you got me, how do I use it?

Just include the needed files (_jQuery_ `markdown-converter.js` and `md.js`) and
create a `pre` tag and set it's class to `mdconv`.

The complete tag with all attributes will be replaced by a plain `div`, so be
careful!

## Do you hav.…

Yes we have an example, it is located in the `demo` directory.

# License

MIT License.

