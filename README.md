# Excel-based simple ray tracer

I wrote this back in late 2004 or so, when I was doing a bunch of
spreadsheet work. It's a simple (fixed scene) ray tracer, with those
most traditional of items, a mirrored sphere and a checkerboard plane.

It's written purely in function mode, with no Visual Basic involved,
so that the scene is created by fill down and fill right of the
ray-tracing formulae, spread over a number of tabs. Part of that
means, of course, that there's no recursion, hence it being rather
specialised for this particular scene.

The display is generated using conditional formatting on the values in
the cells. Since the number of conditional formats is small, extra
gradation is produced using a form of dithering.

While dropping big lumps of binary into GitHub is probably not really
the way to go, especially ones representing ancient projects, this is
My First GitHub Repo, so I thought I'd start with something I had
lying around!

*Simon Frankau*
