# CBT790
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 790 is from Dave Danner (by way of Ken Tomiak) and        *   FILE 790
//*           contains his SRS (Sysout Retrieval Services) package. *   FILE 790
//*                                                                 *   FILE 790
//*           email:  ddanner9@yahoo.com                            *   FILE 790
//*                                                                 *   FILE 790
//*    About SRS (SYSOUT Retrieval Services)                        *   FILE 790
//*    ----- ---  ------ --------- --------                         *   FILE 790
//*                                                                 *   FILE 790
//*    SYSOUT Retrieval Services (SRS) is a product that            *   FILE 790
//*    retrieves data from the JES spool using the SYSOUT           *   FILE 790
//*    Application Program Interface (SAPI).  SRS supports a        *   FILE 790
//*    robust set of SYSOUT selection criteria (documented in       *   FILE 790
//*    the $ABOUT member of this pds) that can be specified         *   FILE 790
//*    by the user on the EXEC PARM= statement.  Using these        *   FILE 790
//*    criteria, SRS builds the necessary data structures and       *   FILE 790
//*    calls SAPI asking for SYSOUT data that matches the           *   FILE 790
//*    selection request.  If JES finds and returns a spool         *   FILE 790
//*    data set, SRS copies the data to a file specified by         *   FILE 790
//*    the user.                                                    *   FILE 790
//*                                                                 *   FILE 790
//*    For more complex applications, SRS supports a                *   FILE 790
//*    user-written "despooler" routine.  In this mode, SRS         *   FILE 790
//*    still processes selection criteria, and makes the SAPI       *   FILE 790
//*    call.  But instead of writing the spool data to a file,      *   FILE 790
//*    SRS calls the despooler routine, one record at a time,       *   FILE 790
//*    to process the data.  The SRSJWRAP program (which is         *   FILE 790
//*    included with SRS) is one example of a special               *   FILE 790
//*    despooler routine.                                           *   FILE 790
//*                                                                 *   FILE 790
//*    SRS can be invoked from a batch job or started task as       *   FILE 790
//*    follows:                                                     *   FILE 790
//*                                                                 *   FILE 790
//*    //DESPOOL EXEC SRS,PARM='<options>'                          *   FILE 790
//*                                                                 *   FILE 790
//*    <options> specify a combination of SRS control options       *   FILE 790
//*    and SYSOUT selection criteria.  An explanation of each       *   FILE 790
//*    option may be found in the $ABOUT member of this pds.        *   FILE 790
//*                                                                 *   FILE 790
//*    Required characters are in uppercase while optional          *   FILE 790
//*    characters are in lowercase.  For example, the DDname        *   FILE 790
//*    keyword can be specified as DD=, DDN=, DDNA=, DDNAM=,        *   FILE 790
//*    or DDNAME=.                                                  *   FILE 790
//*                                                                 *   FILE 790
```
