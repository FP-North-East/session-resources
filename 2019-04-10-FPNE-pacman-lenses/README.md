# Presentation: Immutable Data, Lenses, and Pac-man

Using Lenses to implement a Text based Pacman Game.  Haskell presents some
challenges as data structures are immutable.  Pac-man, like most games, has
lots of state that changes as game play evolves.  Lenses provide an
ergonomically friendly way of using immutable data structures in a seemingly
object-orientated way.  But how they work is facinating.  This talk will show
how they are used, and then, assuming I can understand them, delve into how
they work!

(Note, I didn't quite get to the "how they work" bit!

## Building the presentation

The presentation is a single Markdown file which is build with [pandoc][1]
and uses [Reveal.js][2].  The `make.sh` shell script builds the presentation into
the Presentation [`pacman.html`][3] file.

The presentation uses my Text User Interface (TUI) Haskell version of
Pac-man at: https://github.com/ajkavanagh/pacman

## References

1. [Pandoc][1], swiss army knife for document conversions.
2. [Reveal.js][2], JavaScript framework for building presentations.

[1]: https://pandoc.org/
[2]: https://revealjs.com/#/
[3]: ./pacman.html

## License

The presentation is CC as below and RevealJS has it's own license as
indicated in the distribution.

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Various Presentations</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/ajkavanagh/Presentations" property="cc:attributionName" rel="cc:attributionURL">Alex Kavanagh</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
