# TempleLUT
Lookup tables using the TempleOS colour scheme, for use in image and video processing software.

16.png is the original 16-colour scheme used in TempleOS which doesn't cover a lot of the colour spectrum, while 16d.png uses dithering to make colour approximation more accurate, but doesn't look as authentic. Pick your poison.

## Demo
![comparison](https://user-images.githubusercontent.com/43102807/128951220-dadb62bd-1f10-4e50-9f1d-9c527cd9ccdf.png)
The above image is licensed under CC-BY-SA 4.0 due to the colour wheel having the same license.
 - Colour wheel: https://commons.wikimedia.org/wiki/File:Color_circle_(RGB).svg
 - Terry Davis: https://en.wikipedia.org/wiki/File:Terry_A._Davis_(cropped).jpg

## How to use
Download the LUT you want, then import it into the software of your choice.

### OBS
Select the source you want to apply the LUT to, then select Filters. Click the + button under Effect Filters, and add an Apply LUT effect. Then, browse to where you downloaded 16.png or 16d.png. For best results, right click the source and change Scale Filtering to Point.

## How to get better results
Apply color correction to the source before the LUT, and do things that reduce the amount of colours in the image, like bumping up the contrast:![image](https://user-images.githubusercontent.com/43102807/128982124-5db9db33-3ff6-49f2-b171-13a0c5b8af0d.png)

## License
<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="https://oofdere.space">
    <span property="dct:title">oofdere</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">TempleLUT</span>.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="US" about="https://github.com/oofdere/TempleLUT">
  United States</span>.
</p>
