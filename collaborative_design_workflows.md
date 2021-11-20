Collaborative Design Workflows
==============================

You can call a typeface a work of art, a design, or a computer program: all these denominers make sense. What these three things have in common is that they are systems of signs, wherein every part is dependent on every other part.

This makes the possibility of collaboration inevident; to have such a system to be contained within one creative mind seems to be the most logical approach, as it assures a coherent approach to the different levels of structure within such a project.

However, many art and design projects just don't fit into one mind only. Even though a movie can be said to express the vision of its director, it is also the result of the collaboration between the director and a thousand other people, whose talents have all in one way or the other contributed to the end result.

Similarly, many visual artists now work as producers, assembling teams and acquiring skills as required by the subject matter at hand.

And with computer programs, of course, collaboration has been evident ever since they were written, as they were conceived in the sphere of Science.

The highly interesting question is, IEHO, if we can map the collaboration mechanisms as devised within the free software movement, to the production of cultural artefacts, in this case typefaces.

#### CONTENTS 

#### VERSIONING (REVISION CONTROL) 

> Revision control (also known as version control, source control or (source) code management (SCM)) is the management of changes to documents, programs, and other information stored as computer files. It is most commonly used in software development, where a team of people may be changing the same files.

#### CENTRALISED AND DISTRIBUTED VERSIONING 

> Distributed revision control (DRCS) takes a peer-to-peer approach, as opposed to the client-server approach of centralized systems. Rather than a single, central repository on which clients synchronize, each peer's working copy of the codebase is a bona-fide repository. Synchronization is conducted by exchanging patches (change-sets) from peer to peer.

#### VERSIONING SYSTEMS 

Centralised CVS was the first widely used free tool. SVN is the one that is currently ubiquitous. Distributed Darcs, Mercurial, Git and Bazaar are the main software packages used right now. All are free. Hosted [Sourceforge](http://sourceforge.net/ "http://sourceforge.net") (SVN) [Launchpad](https://launchpad.net/ "https://launchpad.net/")(Bazaar) [FreeHG](http://freehg.org/ "http://freehg.org/") (Mercurial) [GitHub](http://github.com/ "http://github.com/") (Git)

You will probably not want to go through the hassle of configuring a server with version control software; it most cases it is probably the most practical to choose a hosted service.

The other choice is between distributed and centralised, IEHO distributed versioning is more suited to dealing with cultural artefacts than centralised versioning; it allows and even promotes variation between different copies of the same repository. This might be unhandy sometimes with computer software---with cultural artefacts it is the way go to achieve the pluriformity and personality we associate with culture in the first place.

Simon Pascal Klein shows how to use GitHub to fork the OpenBaskerville project, which is as trivial as geek gets, @ <http://klepas.org/openbaskerville/#using-git>

In a rather spectacular turn of events (at least in my mind) GitHub recently implemented UFO support, including visual diffs: <http://github.com/rbmntjs/open-baskerville/commit/c5b3322fb49baa3104363ca98546c684d940c0ef>

And visualisations of UFO typefaces: <http://github.com/rbmntjs/open-baskerville/tree/bc03fca9968df8683b3df2ae9afb0185c4acf433/OpenBaskerville.ufo>

#### WORKFLOWS AND TOOLS 

The [ff-hg python plugin for FontForge](http://freehg.org/u/taejo/ffhg/ "http://freehg.org/u/taejo/ffhg/") is a simple interface to the Mercurial version control system. To install it, make sure you have Mercurial installed using your operating system's usual way. Then open the Terminal and run the following command:

   mkdir ~/.FontForge/python; cd ~/.FontForge/python;
   curl -O <http://freehg.org/u/taejo/ffhg/raw-file/tip/ffhg.py>

[The ff-hg walkthrough](http://freehg.org/u/taejo/ffhg/raw-file/tip/docs/walkthru.html "http://freehg.org/u/taejo/ffhg/raw-file/tip/docs/walkthru.html") has more details.

Debian has an [Overview of a complete set of files and sources (with links) for VCS (version control system) development and release branch of an open font.](http://svn.debian.org/wsvn/pkg-fonts/foo-open-font-sources/ "http://svn.debian.org/wsvn/pkg-fonts/foo-open-font-sources/")

The lazyhandwriterfont project has published some [scripts for importing SVG files into FontForge](http://bazaar.launchpad.net/~gryc-ueusp/lazyhandwriterfont/main/files/head%3A/scripts/ "http://bazaar.launchpad.net/~gryc-ueusp/lazyhandwriterfont/main/files/head%3A/scripts/")

[TTX](http://sourceforge.net/projects/fonttools/ "http://sourceforge.net/projects/fonttools/") is a tool to convert OpenType and TrueType fonts to and from XML. FontTools is a library for manipulating fonts, written in Python. It supports TrueType, OpenType, AFM and to an extent Type 1 and some Mac-specific formats.

[RoboFab](http://robofab.org/ "http://robofab.org/") is a Python library with objects that deal with data usually associated with fonts and type design. It writes and reads UFOs. There is an [SVN helper script for Robofab](http://www.lowest-common-denominator.com/2007/03/svn_helper_script_for_robobab.php "http://www.lowest-common-denominator.com/2007/03/svn_helper_script_for_robobab.php") by Brook Elgie

[Meld](http://meld.sourceforge.net/ "http://meld.sourceforge.net") is a visual diff and merge tool. 

How do you programmaticaly go from a UFO or SFD to OTF files? FontForge's python makes this simple, and Dave Crossland published a simple [conversion script](http://article.gmane.org/gmane.comp.freedesktop.fonts/1741 "http://article.gmane.org/gmane.comp.freedesktop.fonts/1741") on the Font Library mailing linst.
