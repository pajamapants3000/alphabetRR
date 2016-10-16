# alphabet RR #

I just got this cool idea to write a utility that will normalize the length
of lines in text. So, for example say I write like I do with vim, not
relying on word wrapping to take me to the next line but rather inserting
newlines as I go. But then I add a line, or remove a line, or simply edit
a line. Well now everything is out of whack and it takes forever to sort
out.

Perhaps this would be better as a vim plugin? Anyway, this is just a
placeholder/reminder of the idea.

2016-10-16
I think both approaches would be good, actually. A command-line utility, and
a plugin that can make use of it within vim. This, then, would be that
command line utility, and I could create a separate project called
vim-alphabetRR.

I also thought of another feature that would be good - indentation. Specify
from the command line how indentation should be applied, and use occurrences
of '\n' to decide where to apply it.

