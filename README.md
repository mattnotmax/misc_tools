# Miscellaneous Tools

Not necessarily my tools, but backups of older tools that I've found useful that are not easily available.   

## OfficeMalScanner

Originally from http://reconstructer.org/. Also currently available at https://github.com/fboldewin/reconstructer.org

I've also included some slides and papers from the author.  

From the website:  

```
25.11.2013

A new version of Officemalscanner/RTFScan has been released. This update includes a generic decryption loop detection, enhanced shellcode patterns and bugfixes. Enjoy!

12.09.2012

The new version of the OfficeMalScanner suite introduces RTFScan. As you might know, there are several samples in the wild, using the RTF format as OLE and PE-File container. So here is a very first version of RTFScan. It currently is able to scan for malicious traces like shellcode, dumps embedded OLE and PE files and other data containers. Buffer decryption in RTFScan is not supported in this release, as OMS and RTFScan will be enhanced to a cryptanalysis feature to break keys up to 1024 bytes in seconds. The old brute force feature in OMS will be kicked then.

10.08.2012

I found some time to update OfficeMalScanner lately. So here is Version 0.54! Next to bugfixes, it now has its own RtlDecompressBuffer library to support VB-macro extraction on WINE. Further the document format is detected (word, ppt, excel) and is able to extract embedded flash files (compressed and uncompressed).

28.09.2009

I made several new updates for OfficeMalScanner, including a new "inflate" feature for Ms Office 2007 documents. You can download the package from the code section. Enjoy!

30.07.2009

Finally i'm happy to release my paper Analyzing MSOffice malware with OfficeMalScanner. This paper describes all features of the OfficeMalScanner suite in detail. Further i've updated some features since my PH-Neutral talk, fixed bugs and replaced bin2code with MalHost-Setup. A much smarter way to analyze the inner workings of shellcode in a real life session. Both malicious samples described in the paper are included in the package. For sure additionally compressed and with extra password safety. Switch to the paper section and enjoy reading!
```

