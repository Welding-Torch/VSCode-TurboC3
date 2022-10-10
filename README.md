# Borland C README 


- In order to easily build projects in the Borland C31 environment in vscode 
- for C class design 
- Come on, class design!  
  
# Features 

- 1. Support activating DOSBOX 
- 2. Support activating BC 
- 3. Support single file compilation in Borland C environment
- 4. Support multi-file project construction in Borland C environment 
- 5. Support opening Borland C and direct positioning To the current project   

# How to use 


*** It is recommended that before using the extension, first understand the basic usage of vscode, you can first try to use vscode and mingw64 to build a C/C++ development environment*** 

** First, please use VScode to open the DISK_C file Folder (File -> Open Folder)** 

- Function 1. Support to activate DOSBOX easily 
  + Scope: Anywhere in DISK_C folder 
  + How to use: After pressing "ctrl+shift+p", type "start dosbox" And press Enter to start dosbox 

- Function 2. Support to easily activate BC 
  + Scope: anywhere in the DISK_C folder 
  + How to use: After pressing "ctrl+shift+p", type "Start Borland C(BC)" And press Enter to start bc 

- Function 3. Support single file compilation 
  + scope in Borland C environment: In the DISK_C folder, please open the *.c file that needs to be compiled
  + How to use: After pressing "ctrl+shift+p", type "BC single file compilation" and press Enter to compile and run 

    Note: This function is only applicable to single file compilation, you can use the graphics library, the generated exe and obj are in In the same directory 


- Function 4. Support multi-file project construction in Borland C environment 
  + Scope: In the DISK_C folder, please open the *.prj file to be built 

  + How to use: After pressing "ctrl+shift+p", Type "BC build project" and press Enter to build and run 

- Function 5. Support multi-file project construction in Borland C environment 
  + scope: In the DISK_C folder, please open the *.prj file to be built 

  + usage: After pressing "ctrl+shift+p", type "BC to open the project" and press Enter 

    . Note: The prj file is generated by the project created by bc, so please open the bc to add the project file (*.c) before use. 

# Requirement 

* comes from ` bc31 of HUST AIA` 

* Please make sure that there are no illegal characters in the path where bc31 is located (such as Chinese characters, brackets, etc.)   

# Configuration- 

`prj_out_dir` (optional): used to set the output directory of the project, if not set, the default is ` *.prj` file in the same directory 


# Changelog 

- 1.0.0 

- Implemented basic bc compilation and build functions 


- 1.0.1 

- Fixed several bugs 


- 1.0.2 

- Added "prj_out_dir" property 


- 1.0.4

- Updated README because someone downloaded it 


- 1.0.5 

- Fixed some bugs 


- 1.0.6 

- Added new features, support to open the project directly with bc 


- 1.0.9 

- Updated ReadMe.md 


# More 

* source code Download[https://github.com/Inso-13/vscode-BC](https://github.com/Inso-13/vscode-BC) 

* IMouse source code and sample download[https://github.com/ Inso-13/BC-IMouse](https://github.com/Inso-13/BC-IMouse)

------

## HUST AIA's resources(You can find how he set up his configutration of TurboC from here)
https://github-com.translate.goog/mfp0610/HUST-AIA-Courses-Resource?_x_tr_sl=auto&_x_tr_tl=en&_x_tr_hl=en&_x_tr_pto=wapp
