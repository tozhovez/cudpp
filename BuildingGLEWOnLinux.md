  1. Fetch the GLEW sources from Sourceforge. I was not able to get either the git or the zip file sources to work (I think there were line feed issues), so I used the .tgz. (glew-1.6.0.tgz)
  1. Unzip, untar, cd into the directory, make. For me this is in ~/glew; inside there's ~/glew/include and ~/glew/lib.
  1. Then there's two settings that have to be specified when you run `cmake -i`:
```
Variable Name: GLEW_INCLUDE_PATH
Description: The directory where GL/glew.h resides
Current Value: /home/username/glew
New Value (Enter to keep current value): 

Variable Name: GLEW_LIBRARY
Description: The GLEW library
Current Value: /home/username/glew/lib/libGLEW.a
New Value (Enter to keep current value): 
```