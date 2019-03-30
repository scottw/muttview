# Muttview

This script will allow you to safely view MIME content in mutt on Mac OS.

## Installation

```sh
cp -p muttview (somewhere in your $PATH, e.g., ~/opt/bin)
```

## Usage

Add lines to your `.mailcap` file:

```
image/jpeg;             $HOME/opt/bin/muttview Preview %s
application/pdf;        $HOME/opt/bin/muttview Preview %s
application/rtf;        $HOME/opt/bin/muttview TextEdit %s
```

In mutt, select a MIME part or attachment and hit 'm'.
