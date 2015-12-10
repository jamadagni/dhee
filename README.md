# Dhee
*A tiny app to give quick access to the C/C++/D programming languages*

**Dhee** makes learning or just trying something out in C/C++/D easier by simplifying the edit-compile-run-debug cycle. You just type in your code into a simple highlighting editor widget and click *Execute*. The text output to *stdout* and *stderr* is shown in separate tabs.

I wrote this because I wanted a quick light-weight app (simpler than a full-fangled IDE) that Simply Works (TM) to help me try out my "D legs" (like "sea legs"). Then I extended it to C/C++ (wasn't too difficult thanks to QScintilla). Hopefully it will be useful for others too.

Regarding the name: By formal training I'm a Sanskrit scholar, and in Sanskrit, "dhee" (rhymes with "sea") means "knowledge". The consonant is an aspirated dental, not alveolar as in English (sounds like "thee" but not fricative). :-)

## Dependencies
Python 3 and bindings for it to Qt 4 and to the QScintilla 2 editor widget based on Qt 4. On Debian-based systems `sudo apt-get install python3-pyqt4.qsci` should bring in all dependencies.

## Installation and usage
`sudo install dhee /usr/local/bin/` or such should suffice to install the app and make it available for launching from your terminal or app launcher by typing just `dhee`. Before pressing *Execute*, go to the *Settings* tab and ensure that the compiler command and options are correct for the appropriate language.
