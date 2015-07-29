# Concrete Interactive Guides

### Git commit message style guide

- [How to Write a Git Commit Message](http://chris.beams.io/posts/git-commit/)

### Coding style guides:

- [The Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide)
- [Objective-C Style Guide](https://github.com/NYTimes/objective-c-style-guide)
    - **Exception:** For code, which is just for app scope, we don't use any prefix. And in Frameworks we will be using `CIN` prefix (not `CI` anymore), as 2 letter prefix are reserved by Apple.
- Lua Mini Style Guide
    - Soft tabs with 2 spaces
    - Double quoted strings
    - Always use local (stops polluting global space)
    - Surround operators with spaces, one space after coma
    - camelCase method and var names