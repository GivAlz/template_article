# Article Template

This is meant as a quick example of latex usage in git.
It is meant as a "good" (well...at least reasonable) starting
point if you're writing an article and want to back it up
on git, or write it collaboratively or with someone else.

Since many times I've seen people recompiling dozens of pages
because they wanted to get a formula right it also contains a
trick to help with that: use multiple files and comment out
what you're not currently using!

Trust me: I know you're used to one big file...this is no good
reason to waste your time!!!

Warning: to compile the file, when using include or input you
only need to compile the original file, in this case:
template_article.tex

Also notice that, since these files are inside a git project, to
rename them use something like:
git mv template_article.tex my_best_article.tex

