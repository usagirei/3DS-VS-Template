3DS Homebrew App Template
===
C++ Project Template - For Visual Studio 2015 (VS14.0)

* Uses NMake MakeFile Template <sup>1</sup>
* Build Targets for *Build*, *Netload* and *Citra* <sup>2</sup>

Requires [DevKitPro]

---

#### Notes:

1. If running  `make` on a clean directory or after `make clean` crashes when creating the 3dsx, try rebuilding DevkitPro's [3dsTools]

2. Running **Build** (F6) on Visual Studio will Launch Citra or try to Netload the 3dsx file to the address configured on **REMOTE_IP** on MakeFile when on their associated Build Targets

3. When Adding a new Source File, add them externall then import them into the Project. Visual Studio will create the files on root, where they aren't acessible to DevkitPro

---

Thanks to **[@SteveIce10]** for [BuildTools]  
Thanks to **[@astronautlevel2]** for helping setup MakeFile and the [BuildTools]


[BuildTools]:https://github.com/Steveice10/buildtools
[DevKitPro]:https://sourceforge.net/projects/devkitpro/
[3dsTools]:https://github.com/devkitPro/3dstools

[@astronautlevel2]:https://github.com/astronautlevel2
[@SteveIce10]:https://github.com/Steveice10
