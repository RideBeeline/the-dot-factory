# The Dot Factory
Generates fonts for dot matrix displays. Read more and download binaries [here](http://www.eran.io/the-dot-factory-an-lcd-font-and-image-generator/).

### Modifications
This version of TheDotFactory fixes a bug in the generation of the character descriptor array - the generated code will often feature a backslash character in a comment. The compiler interprets this as a single comment which runs over multiple lines. This causes the next character in the table to be omitted. In place of the symbol itself, the text "backslash" is substituted for this character.


### Contributing
TDF is currently stable, unmaintained and not accepting PRs (as I don't have the time to thoroughly test contributions). 
If your fork has a working, substantial feature - kindly submit a PR to the README with a short description and link.
