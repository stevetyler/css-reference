<a name='toc'>Table of Contents</a>
------

1. [CSS box models](#box)
1. [Visually hiding content](#hiding)
1. [Em and rem units](#em)
1. [When to use the button element](#button)
1. [CSS grid systems](#grids)
1. [Media queries & mobile specific layouts](#media)
1. [Using non-standard fonts](#fonts)
1. [Optimizing webpages for print](#print)
1. [CSS pre-processors](#preprocessors)
1. [Image replacement techniques](#ir)

<a name='box'>CSS box models<a/> 
------
There are 2 different box models:

1. In the W3C box model, the width of an element gives the width of the content of the box, excluding padding and border.

2. In the traditional box model, the width of an element gives the width between the borders of the box, including padding and border.

By default, all browsers use the W3C box model, with the exception of IE in "Quirks Mode" (IE5.5 Mode), which uses the traditional one.

The box-sizing property allows you to switch box models:

<pre><code>box-sizing: border-box
box-sizing: content-box</code></pre>

The first declaration will cause the box sizes to be applied to the border and everything inside it (traditional model), the second one will cause the box sizes to be applied to the content only (W3C model).

Mozilla supports an additional padding-box value, which will cause the sizes to be applied to the padding and content, but not the border.

Compatibility : IE8+ http://caniuse.com/#search=box-sizing

Source: http://quirksmode.org/css/user-interface/boxsizing.html
  
<a name='hiding'>Visually hiding content<a/>
------

<a name='em'>Em and rem units<a/>
------

Source: https://j.eremy.net/confused-about-rem-and-em/

<a name='button'>When to use the button element<a/>
------

Source: http://css-tricks.com/use-button-element/

<a name='grids'>CSS grid systems<a/>
------

<a name='media'>Media queries & mobile specific layouts<a/>
------

<a name='fonts'>Using non-standard fonts<a/>
------

Webfonts (font services like: Google Webfonts, Typekit etc.)

<a name='print'>Optimizing webpages for print<a/>
------

<a name='preprocessors'>CSS pre-processors<a/>
------

<a name='ir'>Image replacement techniques<a/>
------

Source: http://css-tricks.com/css-image-replacement/

