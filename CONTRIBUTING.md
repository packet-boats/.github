# Contributing to Packet Boats

Thanks for helping. This guide covers the open-source repositories of
Packet Boats. Each one has its licence in its `LICENSE` file, and its
README says how to build and test it. Closed-source repositories don't
take outside contributions yet; when they do, they will ask for a
separate contributor agreement instead of the sign-off below.

## Before you start

For anything bigger than a small fix, open an issue first and describe
what you'd like to change, so we can agree on the approach before you
write the code.

Please report security problems privately to
[contact@packet.boats](mailto:contact@packet.boats), not in a public
issue.

## Sign off your commits

Every commit needs a `Signed-off-by` line. With it you certify the
[Developer Certificate of Origin 1.1](https://developercertificate.org/),
printed below: that you wrote the change, or otherwise have the right
to submit it under the repository's licence. `git commit -s` adds the
line from the name and email in your Git configuration:

```
Signed-off-by: Your Name <you@example.com>
```

Use a name and an email address you can be reached at. To add the line
to commits you've already made, run `git rebase --signoff main`. A pull
request with a commit that isn't signed off can't be merged.

Contributions are licensed under the licence of the repository they go
into. There is no separate agreement to sign for these repositories.

## Pull requests

- Keep a pull request to one change, and each commit to one step of it,
  with a message that says what changed and why.
- Say how you tested it. New behaviour comes with tests.
- CI has to pass: the build, vet and tests the repository's README
  describes.
- Follow the style of the code around your change.
- A maintainer reviews the pull request. Changes are merged by
  fast-forward, so rebase onto `main` when it moves rather than merging
  it in.

## Developer Certificate of Origin

```
Developer Certificate of Origin
Version 1.1

Copyright (C) 2004, 2006 The Linux Foundation and its contributors.

Everyone is permitted to copy and distribute verbatim copies of this
license document, but changing it is not allowed.


Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.
```
