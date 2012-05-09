## LaTeX Resume

These directories present a CV template made with LaTeX.

* cv-semk-xetex/: TeX sources, compile using xetex (recommended), requires Adobe Garamond Pro font (best results). The target PDF files are already compiled for you if you don't have this font installed.
			
* cv-semk-latex/: If you are unable to get the Adobe Garamond Pro font, then use latex to compile with the default cmr10 font.

## Installing LaTeX

On Ubuntu

	sudo apt-get install texlive texlive-xetex

On Mac

	wget -c http://mirror.ctan.org/systems/mac/mactex/mactex-basic.pkg.zip

You can install additional packages also

	wget -c http://mirror.ctan.org/systems/mac/mactex/mactex-additions.mpkg.zip

For complete TeX distribution (1.8GB)

	wget -c http://mirror.ctan.org/systems/mac/mactex/MacTeX.mpkg.zip

## Compiling

Just go to `cv-semk-latex/` or `cv-semk-latex/` and run

	make

## Templates by

Nicolas Favre-Felix (n.favrefelix@gmail.com)
	
			
