## 0.7.2 (March 25, 2021)
  - removed a warning from numexpr
  - changed the way scaling is done

## 0.7.1 (December 14, 2020)


## 0.1.0 (December 14, 2020)
  - changed the range of the alpha spin box
  - replaced conversion constant for energy wavelenght conversion to pyFAI hc
  - replaced conversion constant for energy wavelenght conversion to pyFAI hc
  - added a modified version of edfimage.py from fabio to allow for saving images with z compression
  - added xy files to the gitignore
  - updated environment for python3 tested on ubuntu 18.04
  - small modifications to run with newest numpy and fabio
  - bug in the order of q,I,sig fixed which caused wrong subtration
  - corrected the units in the Parameter setup popup gui
  - small changes to print a message on std if the fit fails
  - minor bug corrected, pyFAIs ChiDiscAtZero and Pi should be selected corectly now.
  - fixed the different size of 1M and 2M detector to read in the beam center correctly
  - abs(q) vs sub added as plot
  - hot fix for bug in slider for colore scale
  - added a __init__.py in mod folder
  - modified the init parameter for ion track fitting
  - definition of beam_y changed in streak fit routine
  - masking from pyFAI integrated into the script, and version nr incremented
  - changed date
  - changed the selection of pixel below/about min/max
  - cleanup a bit
  - cleanup a bit
  - modified pyFAI-drawmask to interface with the script
  - increased version number to 0.5.0
  - Merge branch 'master' into list prepare to push changes to use pyFAI poni files to master
  - corrected a call for the matplotlib axes
  - finalizing the use of pyFAI poni and changed how y_beam cneter is defined and used
  - removed some debug prints
  - working on a change in beam_y definition
  - pyFAI poni read routine, error in energy/wavelenght corrected
  - starting to add pyFAI poni file read
  - INSTALL.txt updated and environment names changed
  - Merge pull request #2 from cnotthoff/area
  - graphical representation of intergration area added
  - ref data renamed
  - small change to the data feed to savetxt, now it seems to work in py2 and py3
  - small change
  - changed save routine back to a version which works for python 2 but not 3
  - Merge pull request #1 from cnotthoff/py3
  - env for ptyhon3 added
  - set some defaults for the ref data
  - added some reference data
  - conda env for python2 added
  - test data added
  - main.py modified to fix save routine for python 3
  - modified the save routine in the widged to run with python 3
  - some changes to get the script to work under python 3, save routine seems broken
  - Update INSTALL.txt
  - Update README.md
  - under construnction install guide
  - initial commit of v0.4.0
  - added tilde files to the ignore file
  - Initial commit

