# Dhee
*A tiny app to help learn the D programming language*

**Dhee** makes learning (or just trying something out in) D easier by simplifying the edit-compile-run-debug cycle. You just type in your code into a simple D-highlighting editor widget and click *Execute*. The text output to *stdout* and *stderr* (if any) is shown in separate tabs.

I wrote this because I wanted a quick light-weight app (simpler than a full-fangled IDE) that Simply Works (TM) to help me try out my "D legs" (like "sea legs"). Hopefully it will be useful for others too.

Regarding the name: By formal training I'm a Sanskrit scholar, and in Sanskrit, "dhee" (rhymes with "sea") means "knowledge". The consonant is an aspirated dental, not alveolar as in English (sounds like "thee" but not fricative). :-)

## Dependencies
1. DMD (currently this is hardcoded but it wouldn't be difficult for anyone to change it to their desired D compiler)
2. Python 3 and bindings for it to Qt 4 and to the QScintilla 2 editor widget based on Qt 4. On Debian-based systems `sudo apt-get install python3-pyqt4.qsci` should bring in all dependencies.

## Installation and usage
Assuming DMD is in your default executable search path, `sudo install dhee /usr/local/bin/` or such should suffice to install the app and make it available for launching from your terminal or app launcher by typing just `dhee`.
