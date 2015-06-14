## Showdown blog (easy as sandwich) ##

{ [Example](http://showdown-blog.googlecode.com/hg/index.html) }

{ [Instructions](Instructions.md) }

Built with [Showdown](http://attacklab.net/showdown/)/[Markdown](http://daringfireball.net/projects/markdown/) and [JQuery](http://jquery.com)

  * 110.0K minified (`swblog.min.js` + `showdown.min.js` + `fdate.min.js` + `sh_main.min.js` + `jquery-1.4.3.min.js`)
  * `swblog.js` is 18.0K, `swblog.min.js` is 11.2K, `swblog.min.js.gz` is 3.1K

### Benefits ###

  * Minimal
  * No server-side. At all.
  * Posts are in Markdown syntax
  * Single post is separate xml-file
  * XML-configurable
  * CSS-stylable
  * Supports tags and tags navigation
  * Supports permalinks to the post
  * Supports mobile
  * You can use several entry-points
  * RSS-generating script/XSL included
  * SHJS-based source code highlighting for programmers (only for single posts)
  * Bonus: A sandwitch-driven [Tumblr](http://tumblr.com) [theme](http://code.google.com/p/showdown-blog/downloads/detail?name=tumblr_theme.html), with code highlighting and twitter support ([Install at Tumblr](http://www.tumblr.com/theme/18012))

### Drawbacks ###

  * No commenting support
  * Search-engines can't see us, may be we can teach them parse xml's too
  * Only for Javascript-enabled browsers
  * Javascript/JQuery takes time to render at slow network
  * Without `.htaccess`, you need to specify `index.html` part in blog URL
  * Things to optimize

### May be later ###

  * Paging support
  * Successive loading
  * Templating support
  * Better looking RSS / Automate RSS updates
  * Calendar

![http://showdown-blog.googlecode.com/hg/img/screenshot-small.png](http://showdown-blog.googlecode.com/hg/img/screenshot-small.png)
