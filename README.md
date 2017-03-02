# MsCelebFaceExtract

The code is used to extract images from MsCelebV1-Faces-Aligned.tsv which is donwloaded from [MS-Celeb-1M][1]. 

[1]: http://research.microsoft.com/en-US/projects/irc/acmmm2016.aspx


## Compile
```bash
g++ src/*.cpp -Iinc -lopencv_core -lopencv_highgui -lopencv_imgproc -o extract
g++ src/*.cpp -Iinc -lopencv_core -lopencv_highgui -lopencv_imgproc -D_OPENMP -fopenmp -o extract_mp
```
