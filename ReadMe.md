### EDK II Project Portable

[EDK II Project(edk2-stable202305:ba91d02)](https://github.com/tianocore/edk2)

use windows vs2019 build

```
read /Env/readme.txt and set system Env.
    eg:
        CLANG_BIN=C:\Program Files (x86)\Microsoft Visual Studio\2019\Enterprise\VC\Tools\Llvm\bin
        BASE_TOOLS_PATH=H:\winedk2\BaseTools\
        CONF_PATH=H:\winedk2\Conf
        CYGWIN_HOME=H:\winedk2\Env\cygwin64
        IASL_PREFIX=H:\winedk2\Env\Tools\
        NASM_PREFIX=H:\winedk2\Env\Tools\
        PACKAGES_PATH=H:\winedk2
        PYTHON_FREEZER_PATH=H:\winedk2\Env\Python311\Scripts\
        PYTHON_HOME=H:\winedk2\Env\Python311
        VS2019_PREFIX=C:\Program Files (x86)\Microsoft Visual Studio\2019\Enterprise\VC\Tools\MSVC\14.29.30133\
        WINSDK10_PREFIX=C:\Program Files (x86)\Windows Kits\10\bin\10.0.22621.0\
run edk2.sln.
```