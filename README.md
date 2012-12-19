Intro
=====

This is the patch queue I use with Mercurial queue for all the work I do for
Mozilla. I work with the developer tools team (Web Console, Source Editor
and other tools).

Patches fail to apply?
======================

This repository holds the daily "snapshot" from "inside the kitchen".
I have queues where I usually put unrelated patches. Check Bugzilla for the
bug dependencies to determine the correct order. I usually work with `qpush
--move`.

I came from Bugzilla...
=======================

If you came from Bugzilla use this repo as a way to get the latest copy of
the patch you are interested of. Don't try to respect the patch queue order
from here - it represents my work-in-progress situation. Always respect the
Bugzilla dependencies which I keep up-to-date.

If things continue to be broken, contact me.

Updates
=======

I push as often as I do work - sometimes I just review stuff, so I don't push to
the repo.

License
=======

Mozilla code is typically licensed under MPL 2. Test code is usually public
domain.

Sometimes public files from web apps on public servers may temporarily end up in
my patches. I test Firefox against varying web apps. I am assuming no
ownership for such code.

I also include in my queue patches written by colleagues or contributors.
License is up to their choice. Again, I am assuming no ownership whatsoever.

Availability
============

This repository is provided voluntarily. I am making no guarantees of its
availability in the future and its commit history. I may do non-fast-forward
pushes.
