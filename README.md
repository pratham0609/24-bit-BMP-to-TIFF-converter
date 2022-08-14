How to convert:
1. Write "make my_project". This will create executable "my_project".
2. Run command "./my_project <source_image> <destination_image>"
3. Write "make clean". This will remove the executable "my_project" and all the .o files.
4. Destination image is generated in the specified directory.

                           (or)
                           
1. Write "make source_file.o". This will create object files(.o) from source files(.c).
2. Write "make my_project". This will use all the .o files to make the executable.
3. Run command "./my_project <source_image> <destination_image>"
4. Write "make clean". This will remove the executable "my_project" and all the .o files.
5. Destination image is generated in the specified directory.
