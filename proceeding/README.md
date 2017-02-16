# Advanced Modular Software Performance Monitoring
## Abstract 

The LHCb software is based on the Gaudi framework, on top of which are built several large and complex software applications. As the LHCb experiment is now in the active phase of collecting and analyzing data,  performance problems arise in various parts of the software, from the High Level Trigger (HLT) programs to data analysis frameworks. It is not easy to find hotspots in the code - only specialized tools can help to understand where CPU or memory usage are not reasonable. There exist many performance analyzing tools, but the main problem is that they show reports in terms of class and function names and such information usually is not very useful - the majority of algorithm developers use the Gaudi framework abstractions and usually do not know about functions which lie at the lower level. We will show a new approach which adds to performance reports a higher abstraction level based on knowledge of framework architecture and run-time object properties. A set of profiling tools (based on Intel® VTune™ Amplifier XE) and visualization interfaces has been developed and deployed.



