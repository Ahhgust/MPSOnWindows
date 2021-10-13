## MPS/NGS tools on windoze

These tools have been compiled in the msys2 environment
on a Windows 7 machine (64-bit). <br>
bcftools_static.exe has been recompiled on a Windows 10 machine and ostensibly it needs to msys2 dlls...

For your convenience I've also added various dlls from the msys2 environment
(specifically, dlls that are required by these programs). Portability needs to
be tested on all of this...

In particular, the following are available:

------------------------

- bgzip [http://www.htslib.org/doc/bgzip.html]
- samtools [http://samtools.sourceforge.net/]
- bwa [http://bio-bwa.sourceforge.net/]
- tabix [https://github.com/samtools/tabix]
- bcftools [http://www.htslib.org/doc/bcftools-1.0.html]
- seqtools [https://github.com/walaj/SeqLib] (note that the SeqLib library also appears to work just fine on Windows as well.)

