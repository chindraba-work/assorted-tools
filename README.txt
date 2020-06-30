Assorted-tools

Contents
======================================================================

* Description
* Requirements
* Version Numbers
* Copyright and License

Description
======================================================================

A collection of tools, mostly [Bash][bash] scripts, for dealing with
thing as I encounter them. Each may have its own requirements and
instructions, for which see the source of each.

-   `dir-merger` Script to merge two directories, resolving conflicts
    with a simple suffix
-   `git-full-clone` Script to clone a remote repository, collecting
    all the branches and effectively making a complete mirror
-   `git-update-clone` Script to keep a full-clone up-to-date with a
    remote repository. Suitable for a chron job
-   `lsync` Direct access to `rsync` with my optimized values for a
    local copy process
-   `push_it` Simple tool to initiate a `git commit` and `git push`
    to gitlab and github
-   `save_it` Simple tool to do a `git commit` forcing a GPG
    signature and using UTC


Requirements
======================================================================

All the tools are written to be used in a Linux environment, and
normally will expect to use BASH 4.3+. Each tool will have its own
requirements, which may be included in the source if they are more than
the basics of Linux + Bash.

Version Numbers
======================================================================

There is no use of version numbers within this collection. Each tool
is likely to be built, used, and forgotten, and the collection as a
whole has no "version" concept to apply.

Copyright and License
======================================================================

The MIT license applies to all the code within this repository.

Copyright © 2020  Chindraba (Ronald Lamoreaux)
                  <projects@chindraba.work>
- All Rights Reserved

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use, copy,
modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS
BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN
ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
