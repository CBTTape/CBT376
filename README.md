# CBT376
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 376 contains the ZDF display system from David Marsden    *   FILE 376
//*           of Perth, Australia.  In addition, there are many     *   FILE 376
//*           other utilities in this file which can work either    *   FILE 376
//*           together with ZDF or as independent tools.  This      *   FILE 376
//*           file is therefore potentially very useful.            *   FILE 376
//*                                                                 *   FILE 376
//*           Look in the pds itself and the doc to see extra       *   FILE 376
//*           facts and learn about the extra utilities contained   *   FILE 376
//*           in this file.                                         *   FILE 376
//*                                                                 *   FILE 376
//*           David Marsden                                         *   FILE 376
//*           Currently working at CSC Australia                    *   FILE 376
//*           (East Perth Data Centre)                              *   FILE 376
//*                                                                 *   FILE 376
//*           email : dmarsden@one.net.au                           *   FILE 376
//*             web : www2.one.net.au/~dmarsden                     *   FILE 376
//*                                                                 *   FILE 376
//*            mail : P O Box 244                                   *   FILE 376
//*                   Hillarys                                      *   FILE 376
//*                   Western Australia 6923                        *   FILE 376
//*                                                                 *   FILE 376
//*           phone : 61 08 9421 6405 (work)                        *   FILE 376
//*                                                                 *   FILE 376
//*       --------------------------------------------------------  *   FILE 376
//*                                                                 *   FILE 376
//*       ZDF and most add-ons work for up to OS 390 v 2.6.         *   FILE 376
//*                                                                 *   FILE 376
//*       Callable interfaces are used where possible so it does    *   FILE 376
//*       not matter what the MVS version is.                       *   FILE 376
//*                                                                 *   FILE 376
//*       ZDF was updated from XDF as distributed on CBT many       *   FILE 376
//*       years ago.                                                *   FILE 376
//*                                                                 *   FILE 376
//*       There is a lot of stuff in add-ons already on CBT but     *   FILE 376
//*       those here are maybe mofified by me.                      *   FILE 376
//*                                                                 *   FILE 376
//*        - as well as ZDF, UDF (display devices)                  *   FILE 376
//*        and EDJES3 (ISPF JES3 console with nice help)            *   FILE 376
//*                   are worth a good look.                        *   FILE 376
//*                                                                 *   FILE 376
//*       (The add-ons are called from the top line of the ZDF      *   FILE 376
//*        panel display - they can be called as TSO commands       *   FILE 376
//*        but some rely on panels in the PDS which is ISPPLIB      *   FILE 376
//*        LIBDEFed when ZDF is called.  You can fix that by        *   FILE 376
//*        copying the panels to a d/s in ISPPLIB defn.)            *   FILE 376
//*                                                                 *   FILE 376
//*        ZDF displays :                                           *   FILE 376
//*        _____________                                            *   FILE 376
//*                                                                 *   FILE 376
//*        . CPU utilisation as seen by SRM                         *   FILE 376
//*        . avail frame count                                      *   FILE 376
//*        . total paging rate                                      *   FILE 376
//*        . UIC                                                    *   FILE 376
//*        . memory estimate                                        *   FILE 376
//*        . TSO period details (if source adjusted to skip         *   FILE 376
//*                              correct # of performance groups    *   FILE 376
//*                              in IPS - see line                  *   FILE 376
//*                 LA    R5,13      ** PERFORM GROUP SKIP **  )    *   FILE 376
//*        . speed constant                                         *   FILE 376
//*        . # of CPUs and LPAR #                                   *   FILE 376
//*        . total CPU calculated as sum of all ASCBs CPU/elapse    *   FILE 376
//*          time - thus max 300% say for 3 CPUs if all CPU         *   FILE 376
//*          available to an LPAR.                                  *   FILE 376
//*        . ASCB details (job name, # EXCPs, memory status, pg,    *   FILE 376
//*          dispatching priority, %CPU and CPU).                   *   FILE 376
//*                                                                 *   FILE 376
```
