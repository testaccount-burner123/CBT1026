# CBT1026
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE1026 is from Jay Moseley and consists of documentation     *   FILE1026
//*           for how to use (currently 46) MVS-based utilities     *   FILE1026
//*           that he finds useful.  Most of these utilities        *   FILE1026
//*           (not all of them) have versions that can be used      *   FILE1026
//*           in both MVS 3.8 under Hercules, or under z/OS.        *   FILE1026
//*           Some of them come from IBM, and some come from the    *   FILE1026
//*           CBT Tape.                                             *   FILE1026
//*                                                                 *   FILE1026
//*           email:  Jay Moseley <JayMoseley@suddenlink.net>       *   FILE1026
//*                                                                 *   FILE1026
//*           Because Jay wrote the original documentation in       *   FILE1026
//*           HTML format, I am including a copy of that here,      *   FILE1026
//*           although he converted the resulting document to       *   FILE1026
//*           PDF format, and the PDF-format document is all that   *   FILE1026
//*           you really need.                                      *   FILE1026
//*                                                                 *   FILE1026
//*           So, to use either document (for example the PDF       *   FILE1026
//*           document), just download it in BINARY to a PC         *   FILE1026
//*           computer, and view it with a PDF reader, such as      *   FILE1026
//*           ADOBE or FOXIT.                                       *   FILE1026
//*                                                                 *   FILE1026
//*           To use the html-format document, you also need to     *   FILE1026
//*           download it in BINARY to a PC, but you have to        *   FILE1026
//*           rename it on the PC to suffix it with .htm or .html.  *   FILE1026
//*           Then you can view it with a browser, with the name    *   FILE1026
//*           in the format:  file:///h:/download/moseley.doco.htm  *   FILE1026
//*           (Substitute your disk pack letter for "h", and the    *   FILE1026
//*           correct file name that is on your system.)            *   FILE1026
//*                                                                 *   FILE1026
//*           If you make the effort to look at this file, it will  *   FILE1026
//*           reward you many times over.                           *   FILE1026
//*                                                                 *   FILE1026
//*           These tools originate, either from IBM directly, or   *   FILE1026
//*           from the CBT Tape.  The CBT Tape File number is       *   FILE1026
//*           marked clearly in the index part of the document,     *   FILE1026
//*           at the top of the document.                           *   FILE1026
//*                                                                 *   FILE1026
//*           It'll take some work, but the enjoyment awaits        *   FILE1026
//*           immediately afterward.                                *   FILE1026
//*                                                                 *   FILE1026
//*      Note:  The CBT sources mentioned here may not reflect      *   FILE1026
//*             the newest or "best" version of the program named.  *   FILE1026
//*             Sometimes, a different program from the CBT Tape    *   FILE1026
//*             will do a better job.  This is Jay's experience.    *   FILE1026
//*                                                                 *   FILE1026
//*      List of programs documented in this file                   *   FILE1026
//*      ---- -- -------- ---------- -- ---- ----                   *   FILE1026
//*                                                                 *   FILE1026
//*             AMASPZAP        IBM                                 *   FILE1026
//*             AMBLIST         IBM                                 *   FILE1026
//*             CMPRSEQ         CBT File #226                       *   FILE1026
//*             COPYMODS        CBT File #229                       *   FILE1026
//*             DSSDUMP         CBT File #860                       *   FILE1026
//*             DSSREST         CBT File #860                       *   FILE1026
//*             FIXDSCB         CBT File #566                       *   FILE1026
//*             ICKDSF          IBM                                 *   FILE1026
//*             IEBCOMPR        IBM                                 *   FILE1026
//*             IEBCOPY         IBM                                 *   FILE1026
//*             IEBGENER        IBM                                 *   FILE1026
//*             IEBISAM         IBM                                 *   FILE1026
//*             IEBPTPCH        IBM                                 *   FILE1026
//*             IEBUPDTE        IBM                                 *   FILE1026
//*             IEHDASDR        IBM                                 *   FILE1026
//*             IEHINITT        IBM                                 *   FILE1026
//*             IEHLIST         IBM                                 *   FILE1026
//*             IEHMAP          CBT V129 File83                     *   FILE1026
//*             IEHMOVE         IBM                                 *   FILE1026
//*             IEHPROGM        IBM                                 *   FILE1026
//*             LISTPDS         CBT File #316                       *   FILE1026
//*             MINIUNZ         CBT File #135                       *   FILE1026
//*             MINIZIP         CBT File #135                       *   FILE1026
//*             OFFLOAD         CBT File #093                       *   FILE1026
//*             PDSLOAD         CBT File #093                       *   FILE1026
//*             PDSMATCH        CBT File #357                       *   FILE1026
//*             PDSPRINT        CBT File #316                       *   FILE1026
//*             PDSPROGM        CBT File #316                       *   FILE1026
//*             PDSSCAN         CBT File #684                       *   FILE1026
//*             PDSUPDTE        CBT OVF FIle065                     *   FILE1026
//*             PDSUR           CBT File #949                       *   FILE1026
//*             RECV370         CBT File #571                       *   FILE1026
//*             RESETDS         NaSPA 1986                          *   FILE1026
//*             REVLMOD         CBT File #134                       *   FILE1026
//*             SORT            IBM                                 *   FILE1026
//*             SUPERLST        CBT File #134                       *   FILE1026
//*             SYSREPRO        CBT File #316                       *   FILE1026
//*             TAPEMAP         CBT File #299                       *   FILE1026
//*             TAPESCAN        CBT File #102                       *   FILE1026
//*             UNUPDTE         CBT File #093                       *   FILE1026
//*             UPDTE           CBT File #093                       *   FILE1026
//*             VTOCLIST        CBT OVF File343                     *   FILE1026
//*             XMIT370         CBT File #571                       *   FILE1026
//*             ZAPDSCB         CBT File #163                       *   FILE1026
//*             ZTDUMPTP        CBT File #316                       *   FILE1026
//*             ZZRELINK        CBT File #860                       *   FILE1026
//*                                                                 *   FILE1026
```
