# Description
A modified version of the IEEE-Transactions (ieeetr) style for LaTeX bibliographies (modified in 2020 by Francesco Andreoli). The original version (8-Dec-10 version) is by Howard Trickey and Oren Patashnik.
The original copyright statement is quoted here below, and it is assumed to be valid for this modified version as well:

> Unlimited copying and redistribution of this file are permitted as long as it is unmodified.  Modifications (and redistribution of modified versions) are also permitted, but only if the resulting file is renamed.

According to this statement, this (modified) version has been renamed, from "ieeetr.bst" to "ieeetr_fra.bst".



# Modifications 

List of modifications: 
1. For more than 3 authors, the modified style will print automatically only the first author, followed by ``et al.". This number can be changed by swapping #3 at lines 239 and 240 to an arbitrary number.
2. For papers, a hyperlink to the DOI will be automatically added to the title. If the DOI is undefined, then it will be replaced by the URL (if defined) associated to that entry.
3. For books, it will look for an associated URL and the title of the book will hyperlink to that page.
4. The date format is modified into mm/yy.
