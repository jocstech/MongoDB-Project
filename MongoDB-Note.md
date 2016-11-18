#MongoDB Learning Note


## MongoDB Installation Directories Paths(via brew install)

- The databases are stored in the /usr/local/var/mongodb/ directory
- The mongod.conf file is here: /usr/local/etc/mongod.conf
- The mongo logs can be found at /usr/local/var/log/mongodb/
- The mongo binaries are here: /usr/local/Cellar/mongodb/[version]/bin


## When you install/upgrade mongodb, brew will tell you what to do:

### To have launchd start mongodb at login:

- ln -sfv /usr/local/opt/mongodb/*.plist ~/Library/LaunchAgents

### Then to load mongodb now:

- launchctl load ~/Library/LaunchAgents/homebrew.mxcl.mongodb.plist

### Or, if you don't want/need launchctl, you can just run:

- mongod

### It works perfectly.





---

Last updated:
Nov-18-2016
