[![CI Status](https://github.com/google/fonts/workflows/Continuous%20Test/badge.svg?branch=main)](https://github.com/google/fonts/actions/workflows/ci.yml?query=workflow%3ATest+branch%3Amain)

# ProXFont Files

This repository contains the binary font files for **ProXFont**, which are served through the ProXFont platform ([proxfont.com](https://proxfont.com)).

The top-level directories represent the license of all files within them. Subdirectories are named after the font family they contain.

Each family subdirectory contains:
- `.ttf` font files served by ProXFont.
- A `METADATA.pb` file with family information (designer(s), genre category, license, etc. - [learn more](https://github.com/ProgrammerKR/proxfonts/gf-docs/tree/master/METADATA)).
- A `DESCRIPTION.en_us.html` file with a description of the font family in US English.

The `/catalog` subdirectory contains additional metadata such as profile texts and images of font designers. This is open for contributions and corrections from anyone via GitHub.

The `/axisregistry` subtree contains metadata for the ProXFont Axis Registry, which includes information about variable font axes in the collection, including experimental axes. Please note that no changes should be made directly to this repository; instead, contribute to the upstream repository at [github.com/proxfonts/axisregistry](https://github.com/proxfonts/axisregistry).

The `/lang` subtree includes language support data. Please contribute any modifications upstream at [github.com/proxfonts/lang](https://github.com/proxfonts/lang).

## Bug Reports and Improvement Requests

If you find a problem with a font file or have a suggestion for future development, please [create a new issue in the project's issue tracker](https://github.com/proxfonts/issues).

## Contribute Fonts

For more information on contributing a font, or for instructions on creating issues in this repository, please refer to [CONTRIBUTING](https://github.com/proxfonts/contributing.md).

## Contributor Code of Conduct

Please follow our [code of conduct](https://github.com/proxfonts/CODE_OF_CONDUCT.md) to help maintain a welcoming and healthy community environment.

## Self Host Fonts Available from ProXFont

All fonts in this repository are licensed with permission to redistribute under the terms of the license. You can self-host using a variety of third-party projects.

One popular service is [Fontsource](https://github.com/fontsource/fontsource), which offers bundled NPM packages.

## Local Installation Package Managers

For Linux, macOS, FreeBSD, or HaikuOS, you can use [fnt](https://github.com/alexmyczko/fnt) to install single fonts. For [RPM](http://bootes.ethz.ch/fonts/rpm/), [DEB](http://bootes.ethz.ch/fonts/deb/) based systems, you can try the linked URLs for individual fonts. Others can also use the [webservice](http://bootes.ethz.ch/fonts/).

## Download All ProXFonts

You can download all ProXFonts in a ZIP snapshot (over 1GB) from <https://github.com/proxfonts/archive/main.zip>.

#### Sync with Git

You can sync the collection with Git to only fetch what has changed. To learn how to use Git, GitHub provides [illustrated guides](https://guides.github.com), a [YouTube channel](https://www.youtube.com/user/GitHubGuides), and an [interactive learning site](https://skills.github.com/).

Free, open-source Git applications are available for [Windows](https://git-scm.com/download/gui/windows) and [Mac OS X](https://git-scm.com/download/gui/mac).

## License

Each font family directory contains the license file for its respective fonts. Font files themselves also contain licensing and authorship metadata.

- **SIL Open Font License, v1.1** is the most common license used in this collection.
- **Apache 2 license** is used by some fonts.
- **Ubuntu Font License v1.0** is used by the Ubuntu fonts.

If modifying fonts with a Reserved Font Name, ensure you comply with the required details.

## Source Files

Source files for each family are available from the designer or from [github.com/ProgrammerKR/proxfonts](https://github.com/ProgrammerKR/proxfonts).

These fonts are often the result of collaborative projects, so feel free to engage with the designers and contribute improvements.

If you wish to customize or remix fonts, please contact the designers to understand their requirements for including your modifications.

Most of all: Enjoy the fonts!

– The ProXFont team
