Skrx
====
[Sketch](https://www.sketchapp.com) Plugin, written in JSTalk ( http://jstalk.org ).

Skrx ( ~skreecks ) exports a selection of elements (for now only the rectangles) to Apache Flex MXML or FXG description, and copy it to clipboard.

 [Learn more about Sketch extensions/scripting](http://developer.sketchapp.com)

#### Example

Basic generated skins examples : http://www.rxla.bz/skrx/

![Flex button skins examples made in sketch](https://www.evernote.com/shard/s1/sh/95ab113d-6519-45c1-bd64-aa3113c0f748/914343535bd3811f7e27ff21635ad57f/deep/0/skrx_buttons_examples1.sketch.png)

_Generated MXML_

![generated MXML](https://www.evernote.com/shard/s1/sh/4917067b-f20e-491a-aeb1-6c74b5b431f5/46ed3fbd5bad4e59aab10aaa745fcdb4/deep/0/SkrxSkinTest3.mxml.png)

#### Release notes

##### » 0.1.4
- multi states fills and strokes export ( default / .over / .down / .disabled )

##### 0.1.3
- export FXG
- strokes thickness
- strokes pixelHinting
- gradient angle
- shadows , innerShadows (blur, color, alpha, strength)
- spread / strength conversion ( = spread + 1 )
- tabs fixes

##### 0.1.2
- local relative coordinates
- linearGradient Strokes 
- multiple rectangles
- Completed Alert
- Radial gradient colors ( fixme : focalCenter )
- refactoring

##### 0.1.1
- clipboard
- setLocalPositionAlert
- setLocalPosition ( base x y position on selection area top left point )
- linearGradient fill

##### 0.1
-  coordinates
-  fill and stroke
