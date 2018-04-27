# Latex beamer themes for presentations

## Current themes
Themes are in respective folders together with sample files showing usage:

- JUB - I used this while I was with [Jacobs University](http://www.jacobs-university.de)
- ALUF - For my current affiliation, [University of Freiburg](http://srl.informatik.uni-freiburg.de). Still a work in progress

These themes were adapted from the [Gelugor theme](https://github.com/liantze/beamer-gelugor) by LianTze Lim, which were in turn styled after [Universiti Sains Malaysia's](http://www.usm.my) [Powerpoint style](http://tex.my/gelugor-a-usm-beamer-theme/).

## Usage
* Clone the repo
```
git clone https://github.com/makokal/beamer-themes.git
```
* Put the chosen style file in your path and (customize as needed; logos, colors etc)
* Use it in your beamer as follows
```
\documentclass{beamer}
\usetheme{ALUF} % or whatever name you change it to
...

\begin{frame}
    \frametitle{Measure Theoretic Foundations of ML}

    \begin{definition}[$\sigma$ Algebra]
        Consider $(\Omega, F)$ ...
    \end{definition}
\end{frame}

```
* Enjoy


## Bonus
Use the ``` Makefile ``` provided for compilation. Set you pdf viewer to auto-refresh and you never have to run compile with latex again (including bibtex!!!). On a Mac I recommend Skim. On Ubuntu with Evince, add a ```~/.latexmkrc``` file with [these contents](https://gist.github.com/makokal/6626722)

## Contributing
Pull requests are always welcome.




## Licence

Copyright (c) 2011-2014, Billy Okal
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:
* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
* Neither the name of the <organization> nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL <COPYRIGHT HOLDER> BE LIABLE FOR ANY
DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
