mediawiki-manifest
==================

This contains manifest files to easily fetch the mediawiki source code for the following releases:
* REL1_43

It currently fetches the following skins:
* Vector
* MonoBook
* MinervaNeue
* Timeless

and the following extensions:
* WikiEditor
* VisualEditor
* Cite
* SyntaxHighlight_GeSHi
* ParserFunctions
* Scribunto

To add new skins or extensions, modify the file `mediawiki.xml`.

## Example
For instance, to fetch mediawiki REL1_43:
```
$ repo init -u git@github.com:manoj23/mediawiki-manifest.git -m REL1_43.xml
$ repo sync
```
