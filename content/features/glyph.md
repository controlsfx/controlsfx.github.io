---
title: Glyph Font
---

# Glyph font

ControlsFX supports font packs. The following font packs:

* [Font Awesome](http://fontawesome.github.io/Font-Awesome/)
* [IcoMoon](http://icomoon.io/)
  
This support is not only in the form of API to render glyphs as graphics in Buttons, etc – it is also baked into our other API.
For example, the new `@ActionProxy` API can have its graphic set from a font pack in the following manner: 

```
@ActionProxy(text=”Action Text”, image=”font>FontAwesome:STAR”)
```

This feature was inspired by **Jens Deters’** [FontAwesomeFX](https://bitbucket.org/Jerady/fontawesomefx).

!["GlyphFont"](/images/features/glyphFont.png "GlyphFont")