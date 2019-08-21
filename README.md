Only single file assemblies are supported by CoreClr. 

Running this sample will show the following exception:

```
> exemain.exe
Unhandled exception. System.IO.FileLoadException: Could not load file or assembly 'a.netmodule'. The module cannot be loaded because only single file assemblies are supported. (0x8013101E)
File name: 'a.netmodule'
   at exemain.Program.Main(String[] args)
```