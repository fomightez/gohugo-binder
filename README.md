# gohugo-binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/gohugo-binder/master?filepath=index.ipynb)

Go-based static site generator HUGO running via binder served sessions.

------


An introductory notebook that steps through a quick start with [Hugo](https://gohugo.io/) opens upon session launch.

Step through the introductory notebook to see how to use Hugo in sessions launched from here.

Technical details
-----------------

- Hugo  
	Apt install only is getting version 0.40. So don't use `apt.txt` as route to install. The `postBuild` file in this repo details the approach because the documented install presently listed for Linux isn't compatible with MyBinder/Binder. On the postive side the installation is easy once you know which route to use because the application itself is rather self-contained.   
	Installed exntended version of HUGO as [Docsy](https://themes.gohugo.io/docsy/) theme needs that. Also installed postCSS following 'Prequisites' for Docsy theme listed [here]( https://themes.gohugo.io/docsy/)


- Go  
	This repo results in a system with current version (go1.13.6 when enter `go version` in the terminal) of Go language on it. This is important because athough you can use `apt.txt` to install the go language, as based on [here](https://github.com/aborruso/bashnotebook/blob/master/binder/apt.txt), that currently is way beyond (version 1.10 something). **I didn't realize until later that you only need Go installed if you are compiling Hugo from source**, see [here](https://discourse.gohugo.io/t/quick-start-doesnt-work-on-ubuntu/14686/2). However, leaving here because nice to have installation of current Go language worked out for the MyBinder.org/Binder system, and I may think 'Go language' when I think of 'Hugo'.


----

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/gohugo-binder/master?filepath=index.ipynb)
