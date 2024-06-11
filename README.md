# dumpbin.exe
Microsoft COFF Binary File Dumper: Extract from Visual Studio MSVC Tools.

## Download
Download from [Releases](../../releases) or build latest version:
```
python dumpbin.py
```

## Usage

This option displays all definitions exported from an executable file or DLL.
```
dumpbin.exe /exports *.dll
```

This option displays public symbols defined in a library.
```
dumpbin.exe /linkermember *.lib
```

Dumps the names of the DLLs from which the image imports functions. You can use the list to determine which DLLs to redistribute with your app, or find the name of a missing dependency.
```
dumpbin.exe /dependents *.exe
```
