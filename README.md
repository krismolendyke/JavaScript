# A JavaScript Bundle for Sublime Text 2

This bundle is a "fork" of the bundle included with [Sublime Text 2](http://sublimetext.com/2), which is itself mostly a [TextMate](http://macromates.com/) bundle.

## Notable Differences

### Language Definition
* `console` has been removed as a pattern match.  This cleans up the *Goto...* window substantially.

### Modified Snippets

#### if.sublime-snippet `if`
Removed unconditional `true` and trailing `;`.

#### for.sublime-snippet `for`
Everybody has their preferred `for` loop style.  This is mine.  For better or worse, I tend to share Douglas Crockford's [aversion to the `++` operator in JavaScript](http://javascript.crockford.com/code.html) due to its syntactical proximity to adding a coerced string to a number.

### Added Snippets
These are some snippets that I've added that I find useful.  The snippet tab trigger follows the snippet file name if one is enabled.

#### function_comment.sublime-snippet `/**`
Insert a block comment, usually used for a function or other [JavaScript annotation](http://code.google.com/closure/compiler/docs/js-for-compiler.html).

#### log.sublime-snippet `log`

Insert a `console.log();` statement.

#### logvar.sublime-snippet `logvar`

Insert a `console.log('var: ', var);` statement, where the cursor is mirrored on `var`.  This makes simple console logging of variables easy to write and read in the `console`.

#### loggroup.sublime-snippet `group`

Insert a `console.group();` and `console.groupEnd();` statement, finally placing the cursor between them.

### Removed Snippets
Some snippets I just do not find useful at all.

#### for-()-{}.sublime-snippet
This has been modified and renamed.  See *Modified Snippets* above.

#### for-()-{}-(faster).sublime-snippet
