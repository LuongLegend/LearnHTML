# LearnHTML
## Study with [W3SCHOOL](https://www.w3schools.com/default.asp)
>HTML describes the structure of a Web page
>
### __HTML tags__:
>color: tomato, gray, orange, violet, lightgray, slateblue, dodgerblue, mediumseagreen
>
  * __h1-h6__: heading
  * __p__: page
    * style: change color,background-color,font-family,font-size,text-align,border...
	* title: tooltrip title
  * __a__: anchor
    * href: link
	  * "mailto:email"
	  * "phone:phonenumber"
	  * "#IDtoJump"
	* target: choose where to open the linked document
	  * _self: same page
	  * _blank: new page
	  * _parent: parent frame
	  * _top : full body of window
	* title
  * __img__: image
    * src: 
	* alt: alternate text 
	* width
	* height
	* style:
	  * float: right or left of a text
	* usemap: "#nameImageMap"
  * __map__: image map
    * name: 
  * __area__: area of image map
    * shape: rect/circle/poly/default
	* coords: position
	* alt
	* href
  * __br__<empty tag>: line break
  * __hr__<empty tag>: separate content<a line>
  * __html__
	* lang: language
  * __pre__: preserve space and line break
  * __b__: bold text
  * __strong__: important text
  * __i__: italic text
  * __em__: emphasize text
  * __mark__: mark text
  * __small__: small text
  * __del__: deleted text
  * __ins__: inserted text
  * __sub__: subcript text
  * __sup__: supercript text
  * __blockquote__: a section quoted from another source
    * cite: soure
  * __q__: "short quote". 
  * __abbr__: Abbreviations
    * title
  * __address__: italic text
  * __cite__: work title
  * __bdo__: Bi-Directional Override text
    * __dir__: direction. "rtl" or "ltr"
  * __ul__: unordered list
    * __li__: list item
	* __type__: circle/default/rect
  * __ol__: ordered list
    * __li__: list item
  * __dl__: description list
    * __dt__: define term
	* __dd__: define each term
  * __iframe__: an inline frame
    * src: source
	* title: required
	* height/width
	* name
  * __table__
    * attribute: border
	* __caption__
    * __tr__: table row
	  * __th__: table header
	  * __td__: 
  * __script__: define js
  * __code__: write computer code
  * __kbd__: define keyboard input
  * __samp__: sample out put
  * __var__: define variable mathematical
  * __article__: used for forum post, blog post, newspaper post
  * __section__: contain article, 
  * __nav__: contain navigate link 
  * __aside__: relative content like side bar
  * __figure,figcaption__: specify self-contained content like diagrams, photos, code listing, etc
* __Block-level Elements__: always start on a new line and take up full width avaiable
  * p, address, h1-h6, dl, dd, dt, hr, ul,ol,li, div, video, article,header, pre,table....
* __Inline-element__: does not start a new line and take up as much width necessary
  * span, a, button, b, i, img, strong, time, q, sub, sup, input,textarea....
* __javascript__: dynamic and interactive web page
* __head__: contain metadata: style, title, script...
  * __link__: link to external resource
    * rel
	* href
  * __meta__: SEO, specify character set, page description, keywords, author, viewport
    * name: key. || "viewport"
	* content: content to search || "width=device-width, initial-scale=1.0" display content depend on device
  * __base__: define relative URLs in a page
* __form__
  * action: file to redirect after submit
  * target: 
  * method: get | post
  * autocomplete: on | off : autocompele data entered before
  * novalidate
  * _oninput_: action caculate inputvalue. ex: x.value=parseInt(a.value)+parseInt(b.value)
* __input__
  * type: button|text|submit|checkbox|radio|range|number|reset|color|date|datetime-local|email|file|month|tel|search
  * name
  * value
  * list: a list to
  * pattern: to check input value
  * required
  * readonly
  * disable
  * placeholder
  * step: step of input type's number
  * autofocus
* __lable__
  * for: link to input's id
* __textarea__: multiple input text
  * cols: number width
  * rows: number line
* __select__
  * size: size to display
  * multiple: to select multiple
* __option__
  * selected
* __button__
* __fieldset__: group related data in a format
* __legend__: caption of a fieldset
* __datalist__: a list to choose in a input list. id=list'input
* __output__: caculate between inputs
### __NOTE__:
  * attribute always is lowercase
  * attribute must have double/single quotes around
  * class attribute can be used on __any__ HTML element
  * id attribute: be used on only one HTML element
  * <!-- this is a comment text -->
# CSS
> used to format the layout of a webpage
>
 * __How to use__
   * Inline: use style attribute inside HTML elements
   * Internal: use <style> element in the <head> section
   * External: use <link> element to link an external CSS file
 * custom tag
   * a:link/visited/hover/active
 * 1vw = 1% of viewport width
## media query
> define how the page display with changing size display
>
 