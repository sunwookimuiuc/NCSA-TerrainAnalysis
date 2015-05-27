## Terrain Analysis

To receive an image file as input from the user and to return a file of the equivalent format with values calculated by running the Evans-Young methods in parallel.

###### Running the program:
1) Run through a python file *terrainanalysis.py*:
  If number of processes or pixel size is not specified, the default values will be set to 40 and 1 respectively. 
  a) Only specify the filename.
  > python terrainanalysis.py *filename*
  
  b) Specify filename and number of processes.
  > python terrainanalysis.py *filename* -np #
  
  c) Specify filename, number of processes, and pixel size
  > python terrainanalysis.py *filename* -np # -p #

2) Run through a script for qsub, *terrainanalysis.pbs*:
> qsub terrainanalysis.pbs -v np=x,filename=y,p=z

#### For further information:
[Go to the CIGI Wiki](https://wiki.cigi.illinois.edu/display/UP/Parallel+Terrain+Analysis+on+DEMs)
