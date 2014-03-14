Skrx
====
Sketch Plugin, http://www.bohemiancoding.com/sketch .
Written in JSTalk ( http://jstalk.org ).

Skrx ( ~skreecks ) exports a selection of elements (for now only the rectangles) to Apache Flex MXML or FXG description, and copy it to clipboard. _WIP_

 For more informations about Sketch scripting : http://www.bohemiancoding.com/sketch/scripting

#### Example

Basic generated skins examples : http://www.rxla.bz/skrx/

![Flex button skins examples made in sketch](https://www.evernote.com/shard/s1/sh/34378239-8a53-4f28-bff6-93c84bab5555/268d101ce5aab30110c881ad6eb46906/deep/0/skrx_buttons_examples1.sketch-et-Skrx-et-Sketch-Scripting-API---MSStyleBorder.png)

_Generated MXML_

![generated MXML](https://www.evernote.com/shard/s1/sh/ba087f43-65b0-4e79-b3ed-0b07230dfd18/e9c10aec4460134fc0aa3af5dc0c16ec/deep/0/SkrxSkinTest3.mxml.png)

#### Release notes

##### » 0.1.3
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
