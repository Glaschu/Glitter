HI This GP3 cw
To install you download it 
using cmake open folder with cmaketext in it
then in cmake create a build folder at the same place 
open the glitter sln

to add the resouces to the build move the res folder from the glitter folder with the headers and sources folders and move it to the build folder

adding irrkang libs 
to add irrkang in the project right click on project then go to properties then linker gerneral and select additional libary directories and find the libs for irrkang in \Vendor\irrKlang\lib\Win32-visualStudio/
we then have to add the dll to the glitter release 
the dll can be found in Glitter\Vendor\irrKlang\bin\win32-visualStudio

any other problems let me know but this should work fine now

James Glasgow