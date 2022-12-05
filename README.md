# KarmysCppBuildSystem
Why learn cmake when you can make the whole buildsystem on your own... hah..

### For single-file command to make projects check [[single-file] branch](https://github.com/KarmyDev/KarmysCppBuildSystem/tree/single_file)

## Usage: 
`./build <linux|win64>`<br>
`./run` - only for linux<br>
`./project <add|remove> [<sdl2>]` - add or remove packages (currently only `sdl2` is avaliable)<br>
`./snapshot <purge|revert> [<NUMBER>]` - manage snapshots<br>
<br>
`./make_cpp_proj <project_name> [<executable_name>]` - make entire new project folder
## SDL2 missing:
You need to download the [latest mingw version of sdl2](https://github.com/libsdl-org/SDL/releases).<br>
and put mingw 64 files in the mingw-sdl2 folder in `.project/include/`.
