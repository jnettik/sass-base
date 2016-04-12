# Sass Base

This setup serves to start as a foundation to build upon for project CSS. It
includes some common layout and component styles used on the majority of
projects. These, of course, can always be altered or modified depending on
your needs. Further documentation about specific sub sections and their
intended use can be found intheir respective folders.

## Dependencies

Since tools like [http://gulpjs.com/](http://gulpjs.com/) are typically used to
compile Sass and automate other front end task, no specific compilation tools
are included. This structure does depend on Sass (obiously) and needs something
to compile that; either [Libsass](http://sass-lang.com/libsass) or Ruby Sass.
We also depend on [http://susy.oddbird.net/](Susy) (for handling grids), and
[Breakpoint](https://github.com/at-import/breakpoint) (for handling media
queries).

If your preprocess tooling doesn't include those plugins for you, you'll have
to include them into this codebase yourself.
