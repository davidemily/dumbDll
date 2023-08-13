# dumbDll
This project holds a working dll in order to test attaching to a process

After building the dll, you can test it by running the following
```rundll32.exe dumbDll.dll MainDll```
This should display the following message box.

This means that it should now display the alert box any time it's successfully injected into a process.
