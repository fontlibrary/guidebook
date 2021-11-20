Font Packaging
==============

This page deals with all distribution-related topics.

#### FONT ARCHIVE NAMING 

If the font has a suitable license and gets accepted to Debian/Ubuntu/Fedora, for example, it will acquire a name of the form ttf-foundryname-fontfamilyname"

The actually package could be ttf-oflb-myfont.1.0.zip (or ttf-oflb-myfont.1.0.7z, or ttf-oflb-myfont.1.0.tar.gz)

The package should contains as much of the extended font source as possible.

Regarding the version numbers please follow the binary version field in the ttf itself.

#### FONT HEADERS 

TrueType and Postscript fonts possess headers which can bear meta information. Amongst others, there are standard fields for

-   creator
-   creation date
-   copyright
-   trademark
-   notice/description
-   designer
-   designer url
-   vendor
-   url
-   license
-   license url
-   version
-   truetype version record
-   truetype vendor code
-   font creation date

and several more.

Packaging is best left to distro teams like the [Fedora font SIG](http://fedoraproject.org/wiki/SIGs/Fonts "http://fedoraproject.org/wiki/SIGs/Fonts") and the [Debian font task force](http://pkg-fonts.alioth.debian.org/ "http://pkg-fonts.alioth.debian.org/") but encouraging designers uploading to Font Library to follow best practises will help everyone.
