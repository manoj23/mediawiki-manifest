mediawiki-manifest
==================

This contains manifest files to easily fetch the mediawiki source code for the following releases:
* REL1_31
* REL1_32
* REL1_33
* REL1_34

It currently fetches the following skins:
* CologneBlue
* Modern

and the following extensions:
* VisualEditor
* Scribunto

To add new skins or extension, modify the file `mediawiki.xml`.

## Example
For instance, to fetch mediawiki REL1_31:
```
$ repo init -u git@github.com:manoj23/mediawiki-manifest.git -m REL1_31.xml
$ repo sync
```
