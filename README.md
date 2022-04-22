# GSU Dissertation

Just quick note to add \deluxtable packge to the GSU dissertation template. 

The orginal script was copied from here: https://fits.gsfc.nasa.gov/standard30/deluxetable.sty 

Although there were some issues with the table placements. So I made some changes in the code. Use the given file instead and follow the steps below.

(1) Create a /deluxetable.sty in the 'main' directory or any other directory; just give the path. and copy the whole script from the given file.

(2) Now use the packge by copying below in the main document, or in case of GSU dissertation: packages.tex

  \usepackage{deluxetable} 
  
  \def\@to{to}
  
  It should work!
