# CATJ Examples

## Preface

All of these were created by `pneumerical` (@empiricist) on ModFest 1.21, for [Crimes against the JVM](https://modrinth.com/mod/crimes-against-the-jvm)
Included in this upload are the original notes; a freecam handler (two classes); and a "blink" program.

### Where are the jumps?

What's impressive is that, at the time of writing, CATJ has (had?) _no_ jump instructions.

This means no `if` statements, no `for` or `while` loops, etc.

And it means this bytecode is entirely linear, all because I never bothered to implement proper jump support. 

This is because [DataDriver](https://github.com/AutumnalModding/DataDriver) didn't, and the main logic for Crimes against the JVM was lifted from there.

### Comments

Comments take the form of `NOP` instructions, and are from the original files.

### 8.3 Footnote

For no reason in particular, all filenames are provided in an 8.3 filename convention :)
