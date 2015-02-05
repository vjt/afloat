Afloat - give nerds window management back
==========================================

AFloat, originally started by [@millenomi][], adds useful window management
commands to _most_ Mac apps, such as "Keep on top" and "Focus Follows Mouse",
that you may be accustomed to if you ever used a _real_ UNIX window manager.

:smile:

Afloat adds the following options to supported apps' _Window_ menu:

![Afloat Screenshot][afloat-screenie]


Installation
------------

Download and install EasySIMBL from [@norio-nomura][]'s [repository][simbl-repo],
then download [the current release][current-binary], unpack it, and drag the
extracted `Afloat.bundle` file onto the EasySIMBL window. That's it!

Caveats
-------

I was able to compile this only for 64-bit architectures, so it doesn't work
with 32-bit applications. Chrome *was* one of these, but [as of Chrome 39][chrome-64bit], it's 
released as a 64-bit app, and Afloat works with it.

Credits
-------

* [@millenomi][] for the original Afloat
* [@fjolnir][] for the "Focus follows mouse" option
* [@norio-nomura][] for EasySIMBL
* [@vjt][] for cargo-culting the XCode changes, rebuilding and publishing
  these instructions.

Official Statement
------------------

Open Source Software means :heart: and :beers: and the ability for
individuals to find their way through things, learn in the process, and then
share the results with other individuals, for continuative progress of our
beloved humanity.

Thanks for reading! :smile:

[afloat-screenie]: https://raw.githubusercontent.com/vjt/afloat/master/screenshot.png
[simbl-repo]: https://github.com/norio-nomura/EasySIMBL#how-to-install
[current-binary]: https://github.com/vjt/afloat/releases/latest
[chrome-64bit]: https://code.google.com/p/chromium/issues/detail?id=18323#c74

[@millenomi]: https://github.com/millenomi
[@fjolnir]: https://github.com/fjolnir
[@norio-nomura]: https://github.com/norio-nomura
[@vjt]: https://github.com/vjt
