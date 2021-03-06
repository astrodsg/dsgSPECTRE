# dsgSPECTRE
------------

[quote:](http://www.as.utexas.edu/~chris/spectre.html)
"The interactive spectrum analysis code SPECTRE grew out of codes written in the 1970's by Alan Uomoto and Peter Cottrell. SPECTRE's chief purpose is the manipulation of single-order spectra, and it performs many of the tasks contained in such IRAF routines as "splot" and "rv". It is not meant to replace the much more general capabilities of IRAF, but does some functions in a manner that are convenient for me and that others might find useful. A brief list of SPECTRE tasks are:

* spectrum smoothing
* equivalent width calculation
* continuum rectification, noise spike excision
* spectrum comparison

SPECTRE was written to manipulate coude spectra, and thus is probably most useful for working on high dispersion spectra. I typically gather echelle spectra at various observatories, and reduce the raw data frames to singly-dimensioned spectra using IRAF. Then these spectra are written out as FITS files, and become thus accessible to SPECTRE.

The code is written in standard FORTRAN77, and instructions for obtaining SPECTRE and implementing it are given below. There is no instruction manual, but on-line help commands are part of the SPECTRE code. Three different spectra may be manipulated and displayed simultaneously. In the figure below (click on image to see a clearer version of it) a typical spectrum plotting window is shown. There are short spectral regions of three red giant stars in the globular cluster M13 displayed. Arrows point to the most interesting features in the plot: these are two lines of Na I and one line of Fe II. 
" <br><br>


<b>SPECTRE</b> has been updated to <b>dsgSPECTRE</b> by Dylan Gregersen. These updates include more features during the data reduction to make the process more efficient for the user. The most powerful rountines are the equivalent width finding and performing operations on many files (such as dumping to text).
<br>
<br>

## INSTALLING
---------
In a shell you try running
    
	make

This will show you some more information about the which make file to use. Then run. You may need to edit paths to libraries and executables within the desired make file. Then

    make -f Makefile.?

Where ? is replaced with the correct choice for you system. The systems which have been tested are MacOSX and Redhat. Others come with no gaurentee but hopefully some guidelines. If you fix things to make it work let me know.

<br>

### CONTACT INFORMATION
----------------------
With questions or concerns please email:

Dylan Gregersen  
The University of Utah  
Department of Physics and Astronomy  
gregersen.dylan at gmail.com  


