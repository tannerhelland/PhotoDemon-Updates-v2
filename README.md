## PhotoDemon 8.0+ automatic update interface

In v8.0, PhotoDemon's automatic update interface received a number of improvements.  These improvements were primarily focused delivering faster, smaller, more secure updates to end-users, with a happy side-effect of being a better GitHub citizen (by requiring fewer resources to deliver our updates).

This new update system is built off GitHub Pages, which has several advantages over serving update data from a raw GitHub repository.  (Benefits include better CDN coverage and much more generous bandwidth limits.)  PD already does a lot to minimize update notifications, but nightly builds are a little more cumbersome, owing to the frequency with which they change.

The current update process serves stable and beta updates as complete units, with all 3rd-party libraries bundled with the download.  Nightly builds do *not* do this; instead, they allow users to download just the updated PhotoDemon.exe file (which is actually just a small portion of the overall download size).

Additional ideas for improvements are always welcome!
