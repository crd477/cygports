Minisign is a lightweight program to sign and verify files using modern
cryptography, from the author of the popular libsodium cryptographic
library.  Motivations for using it over something like PGP/GnuPG can be
found here:
* https://latacora.micro.blog/2019/07/16/the-pgp-problem.html
* https://flak.tedunangst.com/post/signify
* https://youtu.be/nCTEKV4UoCM?t=21609 (warning: explicit language)

It would be a new package for Cygwin but is already
packaged in other distributions:
* https://packages.fedoraproject.org/pkgs/minisign/minisign/
* https://packages.debian.org/search?keywords=minisign
* https://software.opensuse.org/package/minisign
* https://pkgs.org/download/minisign
* https://pkgs.alpinelinux.org/package/edge/community/x86_64/minisign
* https://formulae.brew.sh/formula/minisign

It is released under the ISC license.

The current release can be downloaded from:

https://github.com/jedisct1/minisign/releases/tag/0.10

It can be compiled on Cygwin without patches.

The minisign author does supply a native Windows port but I believe it
is useful to have available in Cygwin as well.

.hint and .cygport files can be found in this repository along with
built packages.
