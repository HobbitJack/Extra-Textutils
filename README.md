# TEXTUTILS
The TextUtils package is a collection of simple tools designed around the Unix Philosiphy.
Each tool is designed to do something that is for some reason harder to do with the Coreutils than it probably should be.
Stuff involving stupidly long, cryptic, or hairy Sed/Awk commands are prime candidates for inclusion.
The source code is simple, and each tool is meant to do one thing and one thing only.
Most tools in the project are designed to work with Delimiter-Separated Values (DSV) files well, too.
So, many tools have options to either treat each field separately, or treat the whole line as one item.

# TOOLS
aff -- Add an affix to each line of input
ror -- Re-order fields in each line of input
wst -- Strip whitespace from each field of input
