### What is `dc`?

From the [wikipedia][wikidc] article:

[wikidc]: http://en.wikipedia.org/wiki/Dc_(computer_program)

> `dc` is a cross-platform reverse-polish desk calculator which supports arbitrary-precision arithmetic. It is one of the oldest Unix utilities, predating even the invention of the C programming language; like other utilities of that vintage, it has a powerful set of features but an extremely terse syntax.

### What are you doing with it?

Solving [Project Euler](http://projecteuler.net/) problems.

### Is that even possible?

Maybe.  I think so.  For some of them, at least.

`dc` *is* just an old calculator, but it can evaluate named strings of commands conditionally.  That probably makes it [Turing Complete](http://en.wikipedia.org/wiki/Turing_complete) or something.

### Is this project useful?

No, not in the least.

### Um, why then?

Because there's something oddly appealing about a "language" more opaque than perl.

### What nutty conventions are you following?

The document itself follows a mostly markdown format.  This created a problem because `dc`'s `#` comments conflicted with markdown's `#` headers.  Thus we have a mixed system: `dc` code to be evaluated uses `#` comments, and all other explanatory text leads with `"`.  Lines of `dc` that are meant to be executed together are grouped together with no vertical whitespace.

### How do I run the examples?

`dc` from a terminal to start interactive mode, then just copy and paste.  (Avoid the lines leading with `"`s.)
