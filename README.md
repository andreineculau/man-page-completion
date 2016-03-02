# man-page-completion

If you want a quick and dirty way to have shell completion based on manpages

Based on http://blog.dblevins.com/2010/03/man-page-based-bash-completion.html

``` sh
. man_page_completion

for CMD in somecmd anothercmd; do complete -o default -F _man_generic ${CMD}; done
```
