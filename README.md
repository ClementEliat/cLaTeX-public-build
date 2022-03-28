# This is a cLaTeX, a custom LaTeX compilation bash script #

*Clément Eliat, 2022*

**Version 1.0**

## cLaTeX help ##

Usage : clatex [-option] {arguments}

Available options  

	-h, --help     : displays help message and exits  
	-v, --version  : displays installed version and exits  
	-i, --info     : displays time and efficiency at the end of a compilation process  
	-b, --biblio   : builds bibliography on compilation *  
	-g, --glossary : builds glossaries on compilation *  
	-o, --open     : open pdf file after compilation *  
	-w, --warnings : displays also LaTeX warning messages according to
					 specific filters you can modify yourself in the
					 cLaTeX script source code  

\* : These options are stackable on one flag (short options only).
Please make sure to use -o at the end of the options stacked sequence
(ex. clatex -bgo filename).


### /!\ WARNINGS /!\ ###
- MacOS users : This script needs gdate (coreutils) to be installed to work properly.
- Compatibility without gdate will be investigated soon.
- The overall compatibility of this script has not been extensively tested yet.
- Before using -o options, open the source code and replace **"My pdf opening command"** on **line 48** by your favourite command to open a pdf file and remove the # character (comment in *bash*). I am working on doing this automatically by scanning the system or something like this to match a proper command. THank you for your understanding.

Please contact me at clement.eliat@icloud.com or on GitLab/GitHub if you have any question/problem.

Copyright (C) 2022  Clément Eliat

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.

