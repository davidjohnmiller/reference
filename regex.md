---
title: Regular Expressions
layout: default
---
Pattern       |Purpose
--------------|---------------------------------
.             |Any character (excluding newline)
[\S\s]        |Any character (including newline)
*             |Repeat, zero or more
+             |Repeat, one or more
?             |Stop repeat
^             |Start of line
$             |End of line
\             |Escape
\n            |Newline
\d            |Single digit
\s            |Whitespace
\w            |Word
\b            |Word boundary
( )           |Group (Find)
$#            |Group (Replace), where # is 1, 2...
[^ ]          |Not character
^\n           |Empty line
(?=  )        |Positive look ahead
(?!  )        |Negative look ahead
(?<= )        |Positive look behind
(?<! )        |Negative look behind
(?<= ).+?(?= )|Positive look between
^.*?,         |Everything before first comma each line

Find|Replace|Purpose
----|-------|-------
([A-Z])([A-Z]+)\b|$1\L$2|Upper case to Title case

## VBS

- Global
- Multiline
- IgnoreCase
