shinyAce
==========

The `shinyAce` package enables Shiny application developers to use the 
[Ace text editor](http://ace.c9.io/#nav=about) in their applications. All
current modes (languages) and themes are supported in this package. The 
mode, theme, and current text can be defined when the element is initialized 
in `ui.R` or afterwards using the `updateAceEditor()` function. The editor
registers itself as a reactive Shiny input, so the current value of the
editor can easily be pulled from `server.R` using `input$yourEditorsName`.

![shinyAce](http://trestletech.github.io/shinyAce/images/shinyAce.png)

Or view an [interactive example](http://bit.ly/160IgdO).

Installation
------------

You can install the latest version of the code using the `devtools` R package.
This package uses a new proposed feature in Shiny which must be specifically
installed, as well.

```
# Install devtools, if you haven't already.
install.packages("devtools")

library(devtools)
install_github("shinyAce", "trestletech")
```

License
-------

The development of this project was generously sponsored by the [Institut de 
Radioprotection et de Sûreté Nucléaire](http://www.irsn.fr/EN/Pages/home.aspx) 
and performed by [Jeff Allen](http://trestletech.com). The code is
licensed under The MIT License (MIT).

Copyright (c) 2013 Institut de Radioprotection et de Sûreté Nucléaire

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
