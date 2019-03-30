# Muttview

This script will allow you to safely view MIME content in mutt on Mac OS.

Usage:

Add lines to your `.mailcap` file:

```
image/jpeg;             $HOME/opt/bin/muttview Preview %s
application/pdf;        $HOME/opt/bin/muttview Preview %s
application/rtf;        $HOME/opt/bin/muttview TextEdit %s
```
