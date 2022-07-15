# OpenGL_VSCode_Template
### Some opengl developers wanted to use opengl in Visual Studio Code instead of visual studio but find it hard to use opengl in vscode espically using source package instead of binaries package!

## If you find any bugs, error, issues, just create a New Issue in the 'Issues' tab and describe your issues

## glad version : 3.3.0
## glad profile : core

### To use this, you can clone this with this link 
### -> "https://github.com/githubcoder369/OpenGL_VSCode_Template.git"

#### This also applies if you are learning OpenGL from [Victor Gordan](https://github.com/VictorGordan/opengl-tutorials)
#### aka OpenGL course from [freeCodeCamp](https://www.youtube.com/watch?v=45MIykWJ-C4&t=287s)

#### Without having to download visual studio at all

#### All what you need is G++/Gcc or Clang/Clang++  Depends on what the main file's programming language you are going to use for OpenGL graphics programming, the default is C++ as shown in the main file

#### If you don't have any of those C++/C compilers installed in your computer/laptop, you can download from [winlibs](https://winlibs.com/) (However this only works in windows operating system) in the Release Versions -> UCRT runtime and download one of them, you can exclude clang/clang++  in the section of "without LLVM/Clang/LLD/LLDB" and if you have 7zip application installed in your computer/laptop just donwload the 7zip archive or zip archive (recommended), remember to check your based processor which is in Control Panel -> System and Security -> System

#### After the zip file is downloaded in you have to extract it and it may takes some times. When the the extracting process is done, go to the file you have extracted to, next go to mingw64/mingw32 -> bin and then copy the path of the 'bin' folder location. Finally, go to 'Edit enviroment variable for your account' -> Enviroment Variables -> Path in System Variables -> Double click or click edit -> Click New and paste the 'bin' folder location or click Browse and click on the 'bin' folder inside your extracted file in mingw64/mingw32

#### Finally you have gcc/clang/clang++/g++ installed in your computer/laptop, now if you didn't installed [C/C++ Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools), you can click that to install in your vscode or just go to extensions, search 'C/C++' Select the one made by 'Microsoft' and has verification mark -> Click install and wait for it to done, this extension will help you alot in C/C++ and your OpenGL Graphics Programming

#### If you want to compile the file with OpenGL through terminal/command prompt/powershell, you can uses one of the commands
### Clang++ : ```clang++ main/*.cpp src/glad.c -lopengl32 -lglfw3 -lgdi32```
### G++ : ```g++ -o bin/main.exe  main/*.cpp  src/glad.c -lopengl32 -lglfw3 -lgdi32``` Note: the main.exe is in the bin file of the cloned project from this repository
