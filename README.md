## what?
a wix project for generating an MSI from Atom build output

+ adds apm to user PATH env variable
+ creates desktop shortcut
+ install / uninstall to custom location
+ takes forever (~2.45 minutes) to build...

## how?

### prerequisites
+ MSBuild
+ Build output from Atom

### wixtoolset (v3.8)
`````batch
cinst wixtoolset -version 3.8.1128.0
`````

### from visual studio command prompt (or with msbuild in your path)
`````batch
msbuild Atom.sln
`````

## resources
[WiX Toolset Manual](http://wixtoolset.org/documentation/manual/v3/)
