graphite-templates
==================

A collection of themes for Graphite's [graphTemplates.conf](https://github.com/graphite-project/graphite-web/blob/master/conf/graphTemplates.conf.example).

Each theme lives in a directory with an image example.

## `graphTemplates.conf` usage

Based on [the Graphite docs for rendering](http://graphite.readthedocs.org/en/latest/render_api.html), valid variables are:
* [bgcolor](http://graphite.readthedocs.org/en/latest/render_api.html#bgcolor)
* [colorList](http://graphite.readthedocs.org/en/latest/render_api.html#colorlist)
* [fgcolor](http://graphite.readthedocs.org/en/latest/render_api.html#fgcolor)
* [fontBold](http://graphite.readthedocs.org/en/latest/render_api.html#fontbold)
* [fontItalic](http://graphite.readthedocs.org/en/latest/render_api.html#fontitalic)
* [fontName](http://graphite.readthedocs.org/en/latest/render_api.html#fontname)
* [fontSize](http://graphite.readthedocs.org/en/latest/render_api.html#fontsize)
* [majorGridLineColor](http://graphite.readthedocs.org/en/latest/render_api.html#majorgridlinecolor)
* [minorGridLineColor](http://graphite.readthedocs.org/en/latest/render_api.html#minorgridlinecolor)

For example, the default theme is
```
[default]
background = white
foreground = black
minorLine = grey
majorLine = rose
lineColors = blue,green,red,purple,brown,yellow,aqua,grey,magenta,pink,gold,rose
fontName = Sans
fontSize = 10
fontBold = False
fontItalic = False
```

## Contributing

1. Fork it ( https://github.com/phillbaker/graphite-templates/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
