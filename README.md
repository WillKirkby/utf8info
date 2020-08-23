# utf8info

![CircleCI](https://circleci.com/gh/lunasorcery/utf8info.svg?style=shield)

**utf8info** is a small utility that reads UTF-8 and prints out the raw codepoint information. It's useful for seeing exactly what a string contains, and for catching things like U+202E "RIGHT-TO-LEFT OVERRIDE" and all of the different types of space (because there are [more than you might assume](https://www.cs.tut.fi/~jkorpela/chars/spaces.html)).

Options:

```
-v, --verbose   Enable verbose output. This prints the raw UTF-8 bytes next to the codepoint info.
```

![](docs/screenshot.png)
