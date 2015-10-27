# My CV


This CV is based on the template originally created by [@Adrien Friggeri](https://github.com/afriggeri),
later improved by [@Carmine Benedetto](https://github.com/neoben).

From <a href="https://no.sharelatex.com/templates/cv-or-resume/extended-fancy-cv-(carmine-benedetto)">sharelatex</a>:

> CV template created by Carmine Benedetto, based on Fancy CV template created by Adrien Friggeri.
> Some improvements have been added, in particular modern infographic-style elements.

<img src="https://raw.githubusercontent.com/martinothamar/CV-Latex-Template/master/CV.png" 
width="425" height="550">

# Mac OS X (El Capitan)

* Install [MacTex](https://tug.org/mactex/) or equivalent
* Install [TexMaker](http://www.xm1math.net/texmaker/) or equivalent
 * Note: after El Capitan, TexMaker and other GUI editors won't find MacTex anywhere due to /usr access
 * See [this article](https://tug.org/mactex/UpdatingForElCapitan.pdf) for the solution
* Open TexMaker and build with LuaLaTeX!
* For exporting pdf to png: `sips -s format png --out "CV.png" "CV.pdf"`


# Ubuntu/Mint


* Linux Mint
 * texlive-full
 * texlive-bibtex-extra
 * texlive-latex-extra
 * pgf
 * texlive-pictures
 * texlive-math-extra
 * texlive-fonts-recommended
 * texlive-xetex
 * texlive-luatex
 * lmodern
 * latex-xcolor
 * texlive-extra-utils


Ubuntu/Mint variant installation:

```sh
sudo apt-get install texlive-full texlive-bibtex-extra texlive-latex-extra pgf texlive-pictures texlive-math-extra texlive-fonts-recommended texlive-xetex texlive-luatex lmodern latex-xcolor texlive-extra-utils
```


# Howto

To build the CV, use LuaLaTeX or XeLaTeX.

* All used images are inside the /img folder
* To change the donut charts, use the programming.odg and personal.odg files (Use LibreOffice Impress).
* To change the country, I've added the Norway.xcf (Use GIMP) file as an example.
* See the classfile for commands and structural elements.


# License


Copyright (C) 2015, Martin Othamar

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software,
and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE
WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
