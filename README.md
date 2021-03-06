# MultiPatch
Multi Patch is an all-in-one file patching utility for macOS. 

## Supported formats
Supported patch formats are automatically detected based on the file extension of the patch. At this time, please ensure the patches you wish to use have the proper extension.  
IPS: .ips  
UPS: .ups  
PPF: .ppf  
XDelta: .delta; .dat  
BSDiff: .bdf; .bsdiff  
BPS: .bps  

## License
Multi Patch is built using open source code taken from various sources. The code for each patching algorithm used falls under different licenses, and any changes made will need to adhere to the specific license for that code. The Multi Patch application itself is released under the GPL in an effort to be compatible with the licenses of the patching libraries contained within. The licenses employed by each patching library used are listed below:

**UPS uses LibUPS by byuu.**  
\- Public domain, with one exception. See source code for details.  
**BPS based on beat by byuu.**  
\- Released under the GPLv3.  
**IPS uses UIPS by Neil Corlett.**  
\- Released under the GPL.  
**PPF uses LibPPF by Daniel Ekstr'm.**  
\- Released under the GPL.  
**XDelta uses XDelta3 by Josh MacDonald and others.**  
\- Released under the GPL.  
**BSDiff uses BSDiff by Colin Percival**  
\- Released under custom license. See source code for details.  

## More Information
The ReadMe.rtf file included with the application (which is checked into this repository) contains more information such as version history and usage instructions.
