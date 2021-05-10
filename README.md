# dinbrief
LaTeX/LaTeX 2e dinbrief package

This file is part of the dinbrief package.


# TABLE OF CONTENTS

1. GENERAL INFORMATION
2. ERROR REPORTS
3. FILES IN THIS DISTRIBUTION
4. INSTALLATION

# GENERAL INFORMATION

Distribution of unchanged versions:

 Copyright (C) 1993, 96, 97 by University of Karlsruhe (Computing Center).
 Copyright (C) 1998, 2000   by University of Karlsruhe (Computing Center)
                            and Richard Gussmann.
 All rights reserved.
 For additional copyright information see further down in this file.

 This file is part of the DINBRIEF package

 It may be distributed under the terms of the LaTeX Project Public
 License (LPPL), as described in lppl.txt in the base LaTeX distribution.
 Either version 1.3c or, at your option, any later version.

 The latest version of this license is in

       http://www.latex-project.org/lppl.txt

 LPPL Version 1.3c or later is part of all distributions of LaTeX
 version 2008-05-04 or later.

 For error reports in case of UNCHANGED versions see readme files.

 Please do not request updates from us directly.  Distribution is
 done through Mail-Servers, TeX organizations and others.

 If you receive only some of these files from someone, complain!

  Redistribution of unchanged files is allowed provided that all files
  listed in the corresponding package README file are distributed
  including this readme file.

  However, if these files are distributed by established suppliers as
  part of a complete TeX distribution, and the structure of the
  distribution would make it difficult to distribute the whole set of
  files, *those parties* are allowed to distribute only some of the
  files provided that it is made clear that the user will get a
  complete distribution-set upon request to that supplier (not me).

  Notice that this permission is not granted to the end user.

Generation and distribution of changed versions:

  The generation of changed versions of the files included in the
  packages is allowed under the following restrictions:

  * You rename the file before you make any changes to it.

  * You acknowledge the origin of the original version in the file and
    keep the information that it (or a changed version) has to be
    distributed under the restrictions mentioned in this file.

  * You change the ERROR REPORT address so that we don't get error
    reports for files *not* maintained by us.

  The distribution of changed versions of the files included in the
  packages is allowed under the following restrictions:

  * You provide the user with information how to obtain the original
    package or, even better, distribute it with your files.

  * You make sure that the changed versions contain a notice that
    prevents others to take money for distribution or use of your
    files, i.e. they have to be distributed under the restrictions
    mentioned in this file.

  * You inform us that you created a changed version of the files.
    This is only necessary if you want to distribute it to others.

# ERROR REPORTS

  Before you report an error please check that

  * the error is not already mentioned in the *.bug file of the
    distribution. (In this case it is a feature :-)

  * the error isn't caused by obsolete versions of other software;
    LaTeX from 1986 is a good candidate ...

  * you use an original version of the package.

  If you think you found a genuine bug please report it together
  with the following information:

  * version of the file

  * version (date!) of your LaTeX

  * a short test file showing the behavior with all unnecessary
    code removed.

  * a transcript (log file) of the session that shows the error.

Please note that it is important to make the file as small as possible
to allow us to find and fix the error soon.

# FILES IN THIS DISTRIBUTION

You should get the following files:

  `dinbrief.dtx     `dinbrief' class/style for LaTeX in docstrip format.

  `README.md`        The readme file in MD format.

  `liesmich`         German readme file in plain text format.

  `dinbrief.ins`     This is the installation script that will produce
                   the executable files in this package and the driver
                   files for the documentation when run through LaTeX
                   or TeX.

# INSTALLATION

To produce the executable files please run dinbrief.ins through LaTeX or
TeX, i.e., say

```
   latex dinbrief.ins
```

or whatever is necessary to process a file with LaTeX on your
system.  This will generate all necessary files. If you already have
older versions of the files, the script will ask whether or not you
want to overwrite those versions. Note, that the script calls
docstrip.tex internally which is distributed with LaTeX.

This script will produce the following files:

  * `dinbrief.cls`  The dinbrief class file for LaTeX2e.
  * `dinbrief.sty`  The dinbrief style file for LaTeX 2.09.
  * `dinbrief.cfg`  A sample configuration file for the dinbrief class
                for LaTeX2e.
  * `dinbrief.drv`  The driver file for producing the Users Guide
                and the documentation.
  * `dinbrief.tex`  The Users Guide.
  * `dintab.tex`    A list of available commands.

  * `example.tex`   An example of a letter (needs `brfkopf.tex`).
  * `brfkopf.tex`   An example letter head.
  * `brfbody.tex`   LaTeX input file for the `testXXXX.tex` files.
  * `test10.tex`    Files for testing the class/style.
  * `test11.tex`    dito.
  * `test12.tex`    dito.
  * `testnorm.tex`  dito.
  * `dbold.tex`     letter with R. Sengerlings commands.

To produce the documentation run the corresponding driver files
through LaTeX.  You are allowed to change the driver files to get a
special layout, etc.

```
@stylefile{Ltall
shortpackagename = {dinbrief},
longpackagename  = {dinbrief},
baseformats      = {\LaTeX\ 2.09 and \LaTeXe},
version          = {$Revision: 1.74 $},
date             = {$Date: 2021/05/10 14:51:04 $},
author           = {K.D. Braune, R. Gussmann},
abstract         = {This document serves as User's Guide
                   and as documentation of the new \LaTeX-Style
                   or a \LaTeXe-Class.  This class/style implements
                   a new document layout for writing letters,
                   according to the rules of DIN (Deutsches
                   Institut f\"ur Normung, German standardization
                   institute). The User's Guide is written in
                   German, since we assume the class/style is of
                   minor interest outside Germany.  Of course,
                   most of the macros are explained in English.},
support          = {yes},
comments         = {},
requirements     = {},
incompatibilities = {not full compatible to R. Sengerlings dinbrief}}
```


