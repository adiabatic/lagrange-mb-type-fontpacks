# Lagrange fontpacks for MB Type Fonts

I wanted to use fonts from [MB Type][] in [Lagrange][]. Because I wanted better reproducibility than what I’d get from just relying on my shell’s history, I made a Makefile to capture the process, automate cleaning, and make it easier to make more than one fontpack.

Simply dig out your MB Type `.otf` font files for your favorite MB Type fonts, put them in the corresponding directory, and then run `make` at the command line to generate the `.fontpack` files. Then drag the `.fontpack` files onto your Lagrange window to install them.

I also have fontpacks for both [U.S. Graphics][] fonts and also [Atkinson Hyperlegible][].

## Obvious questions

### Where are the fonts?

They’re not free, so you’ll have to buy them on <https://mbtype.com/>. You can buy them one at a time or [get the pile in one fell swoop][buy all].

### OK, I bought some of the fonts. He gave me a lot of files. What do I do with them?

You’ll want to gather up the OTF fonts in the `+ OT Family` directory. Once you’ve located the `.otf` files for the fonts you want, copy the `.otf` files to the directory with the all-lower-cased font’s name, so the `.otf` files are alongside the `fontpack.ini` files.

### Only a few of the fonts have directories. Where are the others?

I haven’t gotten around to adding them yet.

## License

[CC0][] for my stuff. Not for the fonts themselves, obviously.

[mb type]: https://mbtype.com/
[lagrange]: https://gmi.skyjake.fi/lagrange/
[u.s. graphics]: https://github.com/adiabatic/lagrange-us-graphics-fontpacks
[atkinson hyperlegible]: https://github.com/adiabatic/lagrange-atkinson-hyperlegible-fontpack
[buy all]: https://mbtype.com/fonts/buy-all.html
[CC0]: LICENSE.md
