## Contributor requirements

### Developer Certiticate of Origin

This project uses the Developer Certificate of Origin, Version 1.1 used by Linux Foundation in developing the Linux Kernel. The Developer Certificate of Origin is in the root of this repository as [DCO.md][DCO], or online at [http://developercertificate.org/][DC]. In short, it says that you know where your contribution came from, you know you have the right to distribute it under the same license as this project, and that you can, and do, grant the right for this project to distribute it under the license listed in the [LICENSE.md][LMD] file of this project. You, as a contributor will say that you agree to the [DCO][DCO] by inluding a "Signed-off-by" line with any commit you make. The Command Line version of `git` makes doing so simple, use the `--signoff` or `-s` option when you do make your commit. Inside the commit message it will look like this:

    Signed-off-by: Ronald Lamoreaux <gitkey@chindraba.work>

### GPG-signed commits

In addition, to be acceptable to the project, the commits need to be GPG-signed. Again, `git` makes this simple with the `--gpg-sign[<keyid>]` or `-S[<keyid>]` options for a commit. That, of course, means that you will have to have a PGP key for the same name and email address as you use for creating the commits. GitHub has a good page, [Generating a new GPG key][GPG-HELP], that helps you do make one, and associate it with your GitHub account if you wish.

### OpenPGP public key

One extra step that is required beyond the GitHub help example is that your key also needs to be on a public key server somewhere. Two choices, that I know of, are the regular public key server network and [Keybase][KIO]. The public key server pool can be accessed directly by [GNU Privacy Guard][GPG], the `gpg` command line tool, or on the web at many addresses, including a host at MIT, [https://pgp.mit.edu][MIT-HOST]. The [Keybase app][APP] supposedly makes things easier to use, and increases other users confidence in the connection between an identity and the key. However it is done, I support and encourage the personal and professional use of encryption in every possible case. Requiring contributors here to have, and use, an OpenPGP key is just one way to advance the cause.

---

## Code of Conduct

This project adheres to No Code of Conduct.  We are all adults.  Anyone's contributions will be considered.  Nothing else matters.

For more information please visit the [No Code of Conduct][NCOC] homepage.

---

## Issues and bugs

### Find one, report one

If you find a bug, or have an issue with how something works, or doesn't work, open an [Issue][ISSUE] on the GitHub project page. Maybe it is not a bug, or is the result of a prior decision, maybe it is a problem and needs to be fixed. Either way, the Issue will be seen and addressed.

### Find one, patch one

If you find a truly serious bug, and know how to fix it, code the solution and create a [Pull request][PULL].
Kudos to anyone willing to take the time to create solutions rather than notices. Please read the __Contributor requirements__ secion above.

---

## Feature requests and enhancements

Treat these like an issue you found. The project is small enough that there probably isn't any meaningful enhancements possible that are not already planned without taking it out of it's planned scope. Asking, or offereing, won't hurt anything however, so create an [Issue][ISSUE] anyway.

---

## Using the project locally

Once the project reaches a state where it is truly "usable" an initial release will be tagged. Prior to this, it is a collection of scripts that do something on their own, yet do not fulfill the goal. After that point is reached, changes will be primarily in the "user experience" and "cleaning the code" rather than new functions or new methods. At any stage you find the project, within the scope of the license, feel free to copy and use what you find.


  [DC]: http://developercertificate.org/
  [DCO]: https://github.com/chindraba-work/gpg-tools/blob/master/DCO.md
  [LMD]: https://github.com/chindraba-work/gpg-tools/blob/master/LICENSE.md
  [GPG-HELP]: https://help.github.com/articles/generating-a-new-gpg-key/
  [GPG]: https://www.gnupg.org/
  [KIO]: https://keybase.io/
  [MIT-HOST]: https://pgp.mit.edu/
  [APP]: https://keybase.io/download
  [NCOC]: https://github.com/domgetter/NCoC
  [ISSUE]: https://github.com/chindraba-work/gpg-tools/issues
  [PULL]: https://github.com/chindraba-work/gpg-tools/pulls