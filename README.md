WinMTR (Redux)
==============
**WinMTR (Redux)** in an extended fork of [Appnor's WinMTR](http://winmtr.net/) ([sourceforge](http://sourceforge.net/projects/winmtr/)) <br>
with IPv6 support and other different enhancements and bug fixes

### Download (binaries)
* [**view all available**](https://github.com/LatinSuD/WinMTR/releases)

#### Differences to [WinMTR](http://winmtr.net/) 0.98
- `[x]` - removed Windows 2000 support <br>
- `[x]` + added IPv6 support <br>
- `[x]` + clickable entries when stopped.. *(why the heck wasn't it possible before?)* <br>
- `[x]` * added start delay of about 30ms for each hop *(870ms before the 30th hop gets queried) <br>
this should improve performance and reduces network load* <br>
- `[x]` ! fixed trace list freeze *(list didn't update while tracing, happens when tracing just one hop)* <br>
- `[x]` * theme support *(more fancy look :P)* <br>
- ~~`[ ]` + remembers window size~~ <br>
- `[ ]` ! CTRL+A works for host input <br>
- `[ ]` + host history: pressing del key or right mouse will remove selected entry <br>
- `[ ]` * new icon <br>

### Requirements
* Windows XP+ *(Windows 2000 support can be added on request, but IPv6 will not work)*
* Microsoft Visual C++ 2010 Redistributables
([32bit](http://microsoft.com/en-us/download/details.aspx?id=5555) |
[64bit](http://microsoft.com/en-us/download/details.aspx?id=14632)) or use static build

### About me (White-Tiger) / why I decided to create this fork
There isn't that much to say actually, I've been using IPv6 for a few years now thanks to [**SixXS**](http://sixxs.net/)
and it always annoyed me that WinMTR couldn't handle IPv6... finally my ISP got some sort of IPv6 beta test.
And that's what I wanted to compare: native vs SixXS with long-term trace routes such as those WinMTR provides. <br>
Since there wasn't any WinMTR build with IPv6, I decided to do it myself ;) The result can be seen here :P <br>
*(after 1 day for IPv6, and 2 additional days to fix other stuff and polishing)*

### About me (LatinSuD) / why I decided to create this fork
This is probably a temporary fork in order to create a few enhancements. We already have too many forks.

### How to compile
1. Download and install Visual Studio Community 2022
2. Install workload "Desktop developtment with C++", with optional package "C++ MFC for the latest v143..." (other versions may work too).
3. Open WinMTR.vcxproj
4. Build and run

~~~~
