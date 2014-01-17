#### Wat.

Setting up some test files for exercising browser profiler tools.

#### Table of contents

Some things we can play around with:
* create a ton of DOM nodes: [so-many-nodes](http://6a68.net/profiler-exploration/so-many-nodes.html)
* add a ton of listeners to DOM nodes
* parse a ton of JSON
* be stupid about repainting as much as possible
* do stupid recursion (might crash the browser too quickly though)
* throw lots and lots of uncaught Exceptions
* console.log LIKE A BAWS

#### Contributing

Have ideas for ways to (gradually, reproducibly) crash your browser? Pull requests welcome. *Bonus points for skipping libraries and writing code that works with older browsers like IE8 or android 2.3.*

#### Note to self: regenerating github pages files

1. install bluecloth gem (or other markdown-to-html converter)
2. `bluecloth README.md > index.html` creates the homepage from the markdown.
3. `git push 6a68 HEAD:gh-pages` wootsy
4. :beers:

### License

Everything in here is Apache 2 licensed, have fun.
