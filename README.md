# bstr
C/C++ high performance string library made entirely in C.

it has The basic string operation like find, split replace ...

# Functions

here is the list of the functions and macros and what they do
```
bstrCreate : Create a new bstr from C string

bstrDestroy : Destroy bstr string

bstrLen : The lenght of bstr string

bstrCStr : return C string from bstr string

bstrSGetChar : return a character in the given position or return the given fail character if the postion out of range

bstrGetChar : return a character in the given position or return 0 if the postion out of range

bstrCatC : concatenate a bstr string with c string

bstrCat : concatenate two bstr string

bstrCmp : compare two bstr string

bstrCopy : return a new copy of the given bstr string

bstrFind : find the first "tofind" appear in "str"

bstrFindIndex : find the n th appear of "tofind" in "str"

bstrCount : count how many time "b" appeared in "s"

bstrSplitp : split a bstr string from the given position

bstrSplitIndex : split the string in the n th appear of "b"

bstrSplit : split the string on every appear of "b"

LbstrDestroy : destroy the given Lbstr list

bstrToLower : turn the given string to lowercase

bstrToUpper : turn the given string to uppercase

bstrClearify : remove all the white space from the given bstr string

bstrReplace : replace "what" with "with" in "str"

bstrReplaceIndex : replace "what" with "with" in the n th appear in "str"

bstrReplacep : replace from begin to the end position by "what" in "str"

bstrRemove : remove "toRemove" in "str"

bstrRemoveIndex : remove "toRemove" in "str" the n th appear

bstrReverse : reverse the given string

bstrCaptalize : captalise the given string

bstrAppend : append or insert "toAppend" to "str" in pos

bstrIsNum : check if the given string is a number

bstrIsFPNum : check if the given string is floating-point number

bstrIsAllUpper : check if the given string has all the letters in upper case

bstrIsAllLower : check if the given string has all the letters in lower case

bstrEndsWith : check if "str" ends with "with"

bstrBeginsWith : check if "str" begins with "with"

```
