mailx wrapper for rlwrap
========================

This repository contains a `rlwrap` wrapper for the `mailx` command. It allows
completing folder names, setting names, and alias names. To use, invoke `mailx`
as follows:

    RLWRAP_FILTERDIR=PATH_TO_GIT_REPO rlwrap -z mail_filter mail

where `PATH_TO_GIT_REPO` is the location of your copy of this repository. The
above can be abbreviated via the alias:

    alias mail="RLWRAP_FILTERDIR=PATH_TO_GIT_REPO rlwrap -z mail_filter mail"

The `mail_filter` filter is

    Copyright (C) 2013 Ryan Kavanagh <rak@debian.org>

and is distributed under a 3-clause revised-BSD license. Please see the file
`LICENSE` for details.
