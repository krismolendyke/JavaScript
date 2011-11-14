# A JavaScript Bundle for Sublime Text 2

This bundle is a "fork" of the bundle included with [Sublime Text 2](http://sublimetext.com/2), which is itself mostly a [TextMate](http://macromates.com/) bundle.

## Notable Differences

### Language Definition
* `console` has been removed as a pattern match.  This cleans up the *Goto...* window substantially.

### Added Snippets
These are some snippets that I've added that I find useful.  The snippet tab trigger follows the snippet file name if one is enabled.

#### function_comment.sublime-snippet `/**`
Insert a block comment, usually used for a function or other [JavaScript annotation](http://code.google.com/closure/compiler/docs/js-for-compiler.html).


#### googdomquery.sublime-snippet `goog`

Insert and walk through a [`goog.dom.query()`](http://closure-library.googlecode.com/svn/docs/closure_third_party_closure_goog_dojo_dom_query.js.html) statement.

#### log.sublime-snippet `log`

Insert a `console.log();` statement.

#### logvar.sublime-snippet `logvar`

Insert a `console.log('var: ', var);` statement, where the cursor is mirrored on `var`.  This makes simple console logging of variables easy to write and read in the `console`.

#### loggroup.sublime-snippet `group`

Insert a `console.group();` and `console.groupEnd();` statement, finally placing the cursor between them.
