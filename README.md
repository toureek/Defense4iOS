# Defense4iOS
Attack and Defense solutions for iOS. (This README.md file will be updated soon.)

* Attack App in dynamic-framework hacked in swizzling method(RunTime)
* Attack App in dynamic-framework hacked in fishhook (Demo)
* Checking dynamic-libs on WhiteList or not (Demo)
* Prevent Attaching-Debug in Mach-O with RESTRICT_SEGMENT_INFO
![](./Images/MachO-RESTRICT_SEG.png)
* Prevent Attaching-Debug in ptrace
* Prevent Attaching-Debug in dlopen
* Prevent fishhook from hooking system-core methods
* Clang sanitizer for binary-reSort and global-methods-hook(AssemblyLevel) 
![](./Images/Clang-PC-Trace.png)
![](./Images/Before-BinSort.png)
![](./Images/After-BinSort.png)  
* ReSignature for dumped-ipa file and ReLink to new current xcode project
* Best practice for iOS-Codes-Obfuscation in [MJCodeObfuscation](https://github.com/CoderMJLee/MJCodeObfuscation) based on  libclang.dylib  
![](./Images/BuildSettings4Obfuscation.png)  
