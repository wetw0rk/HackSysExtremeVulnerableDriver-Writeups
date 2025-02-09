# HackSys Extreme Vulnerable Driver

               ooooo   ooooo oooooooooooo oooooo     oooo oooooooooo.   
               `888'   `888' `888'     `8  `888.     .8'  `888'   `Y8b  
                888     888   888           `888.   .8'    888      888 
                888ooooo888   888oooo8       `888. .8'     888      888 
                888     888   888    "        `888.8'      888      888 
                888     888   888       o      `888'       888     d88' 
               o888o   o888o o888ooooood8       `8'       o888bood8P'   

------------------------------------------------------------------------

[![Black Hat Arsenal](https://www.toolswatch.org/badges/arsenal/2016.svg)](https://www.blackhat.com/asia-16/arsenal.html#hacksys-extreme-vulnerable-driver)
[![Appveyor Build Status](https://ci.appveyor.com/api/projects/status/o0i4crgqxjfnqf1s/branch/master?svg=true)](https://ci.appveyor.com/project/hacksysteam/hacksysextremevulnerabledriver/branch/master)
[![GitHub all Releases](https://img.shields.io/github/downloads/hacksysteam/HackSysExtremeVulnerableDriver/total)](https://github.com/hacksysteam/HackSysExtremeVulnerableDriver/releases)
[![Twitter Follow](https://img.shields.io/twitter/follow/HackSysTeam?style=social)](https://twitter.com/HackSysTeam)
[![Mastodon Follow](https://img.shields.io/mastodon/follow/109291325205105061?domain=https%3A%2F%2Finfosec.exchange&style=social)](https://infosec.exchange/@hacksysteam)
[![Discord Server](https://dcbadge.vercel.app/api/server/ns32uNhaq7?style=flat)](https://discord.com/invite/ns32uNhaq7)

The **HackSys Extreme Vulnerable Driver (HEVD)** is a **Windows Kernel** driver that is intentionally vulnerable. It has been developed for **security researchers** and **enthusiasts** to improve their skills in **kernel-level** exploitation.

**HEVD** offers a range of vulnerabilities, from simple **stack buffer overflows** to more complex issues such as **use-after-free**, **pool buffer overflows**, and **race conditions**. This allows researchers to explore exploitation techniques for each implemented vulnerability.


## Black Hat Arsenal 2016

* [Presentation](https://www.blackhat.com/docs/asia-16/materials/arsenal/asia-16-Ansari-HackSys-Extreme-Vulnerable-Driver.pdf)
* [White Paper](https://www.blackhat.com/docs/asia-16/materials/arsenal/asia-16-Ansari-HackSys-Extreme-Vulnerable-Driver-wp.pdf)


## Blog Post

* <http://www.payatu.com/hacksys-extreme-vulnerable-driver/>


## External Exploits

* <https://github.com/wetw0rk/Exploit-Development/tree/master/HEVD-Exploits>
* <https://github.com/sam-b/HackSysDriverExploits>
* <https://github.com/sizzop/HEVD-Exploits>
* <https://github.com/badd1e/bug-free-adventure>
* <https://github.com/FuzzySecurity/HackSysTeam-PSKernelPwn>
* <https://github.com/theevilbit/exploits/tree/master/HEVD>
* <https://github.com/GradiusX/HEVD-Python-Solutions>
* <http://pastebin.com/ALKdpDsF>
* <https://github.com/Cn33liz/HSEVD-StackOverflow>
* <https://github.com/Cn33liz/HSEVD-StackOverflowX64>
* <https://github.com/Cn33liz/HSEVD-StackCookieBypass>
* <https://github.com/Cn33liz/HSEVD-ArbitraryOverwrite>
* <https://github.com/Cn33liz/HSEVD-ArbitraryOverwriteGDI>
* <https://github.com/Cn33liz/HSEVD-StackOverflowGDI>
* <https://github.com/Cn33liz/HSEVD-ArbitraryOverwriteLowIL>
* <https://github.com/mgeeky/HEVD_Kernel_Exploit>
* <https://github.com/tekwizz123/HEVD-Exploit-Solutions>
* <https://github.com/FULLSHADE/Windows-Kernel-Exploitation-HEVD>
* <https://github.com/w4fz5uck5/3XPL01t5/tree/master/OSEE_Training>


## External Blog Posts

* <https://wetw0rk.github.io/posts/0x00-introduction-to-windows-kernel-exploitation/>
* <https://wetw0rk.github.io/posts/0x00-introducci%C3%B3n-a-windows-kernel-explotaci%C3%B3n/>
* <https://wetw0rk.github.io/posts/0x01-killing-windows-kernel-mitigations/>
* <https://wetw0rk.github.io/posts/0x01-mat%C3%A1ndo-windows-kernel-mitigaciones/>
* <https://wetw0rk.github.io/posts/0x02-introduction-to-windows-kernel-uafs/>
* <https://wetw0rk.github.io/posts/0x02-introducci%C3%B3n-a-windows-kernel-uafs/>
* <https://wetw0rk.github.io/posts/0x03-approaching-the-modern-windows-kernel-heap/>
* <https://wetw0rk.github.io/posts/0x03-acerc%C3%A1ndose-al-heap-moderno-del-windows-kernel/>
* <https://wetw0rk.github.io/posts/0x04-writing-what-where-in-the-kernel/>
* <https://wetw0rk.github.io/posts/0x04-escribiendo-que-donde-en-el-kernel/>
* <https://wetw0rk.github.io/posts/0x05-introduction-to-windows-kernel-type-confusion-vulnerabilities/>
* <https://wetw0rk.github.io/posts/0x05-introducci%C3%B3n-a-windows-kernel-type-confusion-vulnerabilidades/>
* <https://wetw0rk.github.io/posts/0x06-approaching-modern-windows-kernel-type-confusions/>
* <https://wetw0rk.github.io/posts/0x06-acerc%C3%A1ndose-a-windows-kernel-type-confusions-modernos/>
* <https://wetw0rk.github.io/posts/0x07-introduction-to-windows-kernel-race-conditions/>
* <https://wetw0rk.github.io/posts/0x07-introducci%C3%B3n-a-windows-kernel-race-conditions/>
* <https://wetw0rk.github.io/posts/0x08-modern-windows-kernel-race-conditions/>
* <https://wetw0rk.github.io/posts/0x08-race-conditions-moderno-del-windows-kernel/>
* <https://wetw0rk.github.io/posts/0x09-return-of-the-stack-overflow/>
* <https://wetw0rk.github.io/posts/0x09-el-regreso-del-stack-overflow/>
* <http://niiconsulting.com/checkmate/2016/01/windows-kernel-exploitation/>
* <http://samdb.xyz/2016/01/16/intro_to_kernel_exploitation_part_0.html>
* <http://samdb.xyz/2016/01/17/intro_to_kernel_exploitation_part_1.html>
* <http://samdb.xyz/2016/01/18/intro_to_kernel_exploitation_part_2.html>
* <http://samdb.xyz/2017/06/22/intro_to_kernel_exploitation_part_3.html>
* <https://sizzop.github.io/2016/07/05/kernel-hacking-with-hevd-part-1.html>
* <https://sizzop.github.io/2016/07/06/kernel-hacking-with-hevd-part-2.html>
* <https://sizzop.github.io/2016/07/07/kernel-hacking-with-hevd-part-3.html>
* <https://sizzop.github.io/2016/07/08/kernel-hacking-with-hevd-part-4.html>
* <https://www.fuzzysecurity.com/tutorials/expDev/14.html>
* <https://www.fuzzysecurity.com/tutorials/expDev/15.html>
* <https://www.fuzzysecurity.com/tutorials/expDev/16.html>
* <https://www.fuzzysecurity.com/tutorials/expDev/17.html>
* <https://www.fuzzysecurity.com/tutorials/expDev/18.html>
* <https://www.fuzzysecurity.com/tutorials/expDev/19.html>
* <https://www.fuzzysecurity.com/tutorials/expDev/20.html>
* <http://dokydoky.tistory.com/445>
* <https://hshrzd.wordpress.com/2017/05/28/starting-with-windows-kernel-exploitation-part-1-setting-up-the-lab/>
* <https://hshrzd.wordpress.com/2017/06/05/starting-with-windows-kernel-exploitation-part-2/>
* <https://hshrzd.wordpress.com/2017/06/22/starting-with-windows-kernel-exploitation-part-3-stealing-the-access-token/>
* <https://osandamalith.com/2017/04/05/windows-kernel-exploitation-stack-overflow/>
* <https://osandamalith.com/2017/06/14/windows-kernel-exploitation-arbitrary-overwrite/>
* <https://osandamalith.com/2017/06/22/windows-kernel-exploitation-null-pointer-dereference/>
* <http://dali-mrabet1.rhcloud.com/windows-kernel-exploitation-arbitrary-memory-overwrite-hevd-challenges/>
* <https://blahcat.github.io/2017/08/31/arbitrary-write-primitive-in-windows-kernel-hevd/>
* <https://klue.github.io/blog/2017/09/hevd_stack_gs/>
* <https://glennmcgui.re/introduction-to-windows-kernel-exploitation-pt-1/>
* <https://glennmcgui.re/introduction-to-windows-kernel-driver-exploitation-pt-2/>
* <https://kristal-g.github.io/2021/02/07/HEVD_StackOverflowGS_Windows_10_RS5_x64.html>
* <https://kristal-g.github.io/2021/02/20/HEVD_Type_Confusion_Windows_10_RS5_x64.html>
* <https://wafzsucks.medium.com/hacksys-extreme-vulnerable-driver-arbitrary-write-null-new-solution-7d45bfe6d116>
* <https://wafzsucks.medium.com/how-a-simple-k-typeconfusion-took-me-3-months-long-to-create-a-exploit-f643c94d445f>
* <https://mdanilor.github.io/posts/hevd-0/>
* <https://mdanilor.github.io/posts/hevd-1/>
* <https://mdanilor.github.io/posts/hevd-2/>
* <https://mdanilor.github.io/posts/hevd-3/>
* <https://mdanilor.github.io/posts/hevd-4/>

## Author

> **Ashfaq Ansari**

> ashfaq[at]hacksys[dot]io

> **[Blog](https://hacksys.io/ "HackSys Team") | [@HackSysTeam](https://twitter.com/HackSysTeam)**

> [![HackSys Inc](https://hacksys.io/android-chrome-192x192.png "HackSys Inc")](https://hacksys.io)

> [https://hacksys.io/](https://hacksys.io/ "HackSys Inc")


## Screenshots

![Driver Banner](Screenshots/hevd-banner.png "Driver Banner")

![Help](Screenshots/hevd-help.png "Help")

![Exploitation](Screenshots/hevd-exploitation.png "Exploitation")

![Driver Debug Print](Screenshots/hevd-debug-print.png "Driver Debug Print")


## Vulnerabilities Implemented

* **Write NULL**
* **Double Fetch**
* **Buffer Overflow**
  * **Stack**
  * **Stack GS**
  * **NonPagedPool**
  * **NonPagedPoolNx**
  * **PagedPoolSession**
* **Use After Free**
  * **NonPagedPool**
  * **NonPagedPoolNx**
* **Type Confusion**
* **Integer Overflow**
  * **Arithmetic Overflow**
* **Memory Disclosure**
  * **NonPagedPool**
  * **NonPagedPoolNx**
* **Arbitrary Increment**
* **Arbitrary Overwrite**
* **Null Pointer Dereference**
* **Uninitialized Memory**
  * **Stack**
  * **NonPagedPool**
* **Insecure Kernel Resource Access**


## Building the driver

1. [Install Visual Studio 2017](https://visualstudio.microsoft.com/downloads/)
2. [Install Windows Driver Kit](https://docs.microsoft.com/en-us/windows-hardware/drivers/download-the-wdk)
3. Run the appropriate driver builder `Build_HEVD_Vulnerable_x86.bat` or `Build_HEVD_Vulnerable_x64.bat`


## Download

If you do not want to build **HackSys Extreme Vulnerable Driver** from source, you could download pre-built
executables for the latest release:

[https://github.com/hacksysteam/HackSysExtremeVulnerableDriver/releases](https://github.com/hacksysteam/HackSysExtremeVulnerableDriver/releases)


## Installing the driver

Use [OSR Driver Loader](https://www.osronline.com/article.cfm?article=157) to install **HackSys Extreme Vulnerable Driver**


## Testing

The **HackSys Extreme Vulnerable Driver** and the respective exploits have been tested on **Windows 7 SP1 x86** and **Windows 10 x64**  


## Sessions Conducted

* [Windows Kernel Exploitation 1](http://null.co.in/event_sessions/156-windows-kernel-exploitation)
* [Windows Kernel Exploitation 2](http://null.co.in/event_sessions/186-windows-kernel-exploitation-2)
* [Windows Kernel Exploitation 3](http://null.co.in/event_sessions/226-windows-kernel-exploitation-3)
* [Windows Kernel Exploitation 4](http://null.co.in/event_sessions/234-windows-kernel-exploitation-4)
* [Windows Kernel Exploitation 5](http://null.co.in/event_sessions/309-windows-kernel-exploitation-5)
* [Windows Kernel Exploitation 6](https://null.co.in/event_sessions/482-windows-kernel-exploitation-6)
* [Windows Kernel Exploitation 7](https://null.co.in/event_sessions/845-windows-kernel-exploitation-7)


## Workshops Conducted

* [Windows Kernel Exploitation Humla Pune](http://null.co.in/event_sessions/280-windows-kernel-exploitation)
* [Windows Kernel Exploitation Humla Mumbai](http://null.co.in/event_sessions/327-windows-kernel-exploitation)


## HEVD for Linux

![Linux HEVD Driver Banner](Screenshots/hevd-linux-banner.png "Linux HEVD Driver Banner")

![Linux HEVD Driver Installer](Screenshots/hevd-linux-install-uninstall.png "Linux HEVD Driver Installer")

![Linux HEVD Driver IOTCL Tests](Screenshots/hevd-linux-ioctl-tests.png "Linux HEVD Driver IOTCL Tests")

![Linux HEVD Driver IOTCL Log](Screenshots/hevd-linux-ioctl-log.png "Linux HEVD Driver IOTCL Log")


## License

Please see the file `LICENSE` for copying permission


## Contribution Guidelines

Please see the file `CONTRIBUTING.md` for contribution guidelines


## TODO & Bug Reports

Please file any enhancement request or bug report via the **GitHub** issue tracker at the below-given address: [https://github.com/hacksysteam/HackSysExtremeVulnerableDriver/issues](https://github.com/hacksysteam/HackSysExtremeVulnerableDriver/issues)


## Acknowledgments

Thanks go to these wonderful people: 🎉

<a href="https://github.com/hacksysteam/HackSysExtremeVulnerableDriver/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=hacksysteam/HackSysExtremeVulnerableDriver" />
</a>

------------------------------------------------------------------------

[![HackSys Inc](https://hacksys.io/android-chrome-192x192.png "HackSys Inc")](https://hacksys.io)
