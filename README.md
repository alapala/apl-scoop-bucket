# apl-scoop-bucket
Bucket (i.e., collection of apps) for scoop

Gpg4win
-------

`gpg4win.json` installs the vanilla version, which only includes the
GnuPG component of Gpg4win. This app manifest works insofar as it
installs the program, but
- it requires administrator access,
- because it modifies the system path, if not for other reasons, and
- it puts files in the Start Menu folder.
The Gpg4win README has a section that discusses installer options, but I
don't see a way to solve these problems.
