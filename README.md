# GNU sed binary version for osx

This repo describes how to build gnu sed on Osx, and makes it available as a simple tar.gz 
on the github [release page](https://github.com/sequenceiq/gnused-osx-bin/releases)

## tldr;
Osx comes with a sed version, which isn’t compatible with GNU sed. It’s specifically annoying
when it comes to newline handling. Most of the times we want to rely on gnu sed 4.2.2.

Normally you are installing it with `brew install gnu-sed --default-names`. But for
that you need brew, which needs xcode and correct ruby environment, Ohhh which ruby
version should I use? Should I use rbenv? 

All I want is *single binary* put into my PATH. Until gnu sed gets implemeted in golang ;)
I would like to have travis take care of building the sed puting into a tar.gz and uploading
it to a github [release page](https://github.com/sequenceiq/gnused-osx-bin/releases)

