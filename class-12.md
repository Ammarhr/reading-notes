
## canvas:
### the different between  ```<canvas>``` and  ```<img>```:
```<canvas>``` is somehow similar to ```<img>``` wlwmwnt, but ``<canvas>`` doesn't have the src and alt attributes.  ``<canvas>`` have only two attributes wich are: **width** and **height**.

like for ``<video>``, ``<audio>``, or ``<picture>`` elements,The ``<canvas>`` element differs from an  easy to define some fallback content, to be displayed in older browsers not supporting it,

unlike the ``<img>`` element, the ``<canvas>`` element requires the closing tag ``</canvas>``. If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed.

### normal styling:
you can style ``<canvas>`` elements with **css** like any other elements.
`````
canvas{
    color: ####;
    etc
}
`````

#### canvas fallback:
If fallback content is not needed, a simple <canvas id="foo" ...></canvas> is fully compatible with all browsers that support canvas at all.

#### Checking for support
The fallback content is displayed in browsers which do not support <canvas>. Scripts can also check for support programmatically by simply testing for the presence of the getContext() method

## Canvas Vs SVG:
The HTML <svg> element is a container for SVG graphics. SVG stands for Scalable Vector Graphics. SVG and useful for defining graphics such as boxes, circles, text, etc. SVG stands for Scalable Vector Graphics and is a language for describing 2D-graphics and graphical applications in XML and the XML is then rendered by an SVG viewer. Most of the web browsers can display SVG just like they can display PNG, GIF, and JPG.

The HTML <canvas> element is used to draw graphics, via JavaScript. The<canvas> element is a container for graphics.