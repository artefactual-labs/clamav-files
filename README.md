# clamav-files

Virus definition files for clamav, downloaded from https://www.clamav.net/downloads.

This repository is used when installing Archivematica using the ansible role
https://github.com/artefactual-labs/ansible-archivematica-src .

Normally virus definition files are downloaded using freshclam.  In cases where it is not possible
to download initial definition files, or when the freshclam process hangs or crashes for any reason,
this repository can be used to at least provide some initial definitions.
