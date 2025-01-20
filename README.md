# EXTRA TEXTUTILS
Extra Textutils is a collection of Unix utilities for working with data stored in ASCII formats.

## PHILOSOPHY
Everything in this package is entirely possible with other tools, usually sed + awk.
But, in many cases the required commands, especially to deal with headers, are non-trivial to re-write each time they are needed; this package therefore exists to give those kinds of general-purpose awk/sed scripts a home in a more fully-featured and configurable form as Unix-style programs.
Most of these tools are designed to work with delimiter-separated file types (TSV, CSV), but for the latter there is no support for quoting.
You may want to use a program that converts quoted CSV to TSV or another format that doesn't permit quoting.
No such tool exists in this package because I haven't had a need for it, but if someone submits a PR with such a program I will gladly accept it.

## TOOLS
aff -- Add an affix to each line of input

del -- Remove any lines containing any filter literal

fdel -- remove lines with empty fields

nrep -- Replace just the first N instances of a literal with another literal

ror -- Re-order fields in each line of input

wstrip -- Strip whitespace from each line of input

## COPYRIGHT AND LICENSING
This software and its documentation are licensed under the GPLv3+.
Please see LICENSE for the full terms and conditions of this license.

## CONTRIBUTIONS
Contributions are very very welcome! However, I ask any contributions to please be based on the included template file, and all submitted code must be GPL compatible, and no LLM-generated code should be submitted. Please format all code using the `black` formatter with default settings. Thanks!

## RELEASE
At present release involves either a `git clone` or manually downloading the files (there are no inter-dependencies between the programs). Soon I plan on using GitHub releases and eventually I'd like to get an AUR release going.
