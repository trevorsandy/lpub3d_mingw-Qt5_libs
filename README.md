# lpub3d_windows_3rdparty
LPub3D Windows pre-compiled libraries and binaries 

This repositoy stores pre-compiled applications needed to compile the LPub3D application suite.

LDView build command:
````
> git clone https://github.com/trevorsandy/lpub3d_linux_3rdparty.git
> git clone https://github.com/trevorsandy/ldview.git
> cd ldview
> build [options]
````
Note: Not using QtCreator shadow build  


LDGLite build command:
````
> git clone https://github.com/trevorsandy/lpub3d_windows_3rdparty.git
> git clone https://github.com/trevorsandy/ldglite.git
> cd ldglite
> qmake.exe ldglite.pro -spec win32-g++ CONFIG+=3RD_PARTY_INSTALL=../lpub3d_windows_3rdparty 
> <path to mingw make>/mingw32-make.exe
> <path to mingw make>/mingw32-make.exe
````
Note: LDGlite qmake uses shadow build
Note: If `CONFIG+=3RD_PARTY_INSTALL` is ommitted the build check test will be automatically executed.


LPub3D-Trace (POV-Ray) build command:
````
> git clone https://github.com/trevorsandy/lpub3d_windows_3rdparty.git
> git clone https://github.com/trevorsandy/povray.git
> cd povray/windows/vs2015
> autobuild [options]
````

