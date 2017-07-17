
1. To discard all chanes
git reset --hard # removes staged and working directory changes

 _be very careful with these_.<br>
 _you may end up deleting what you don't want to_.<br>
 _read comments and manual._.

* git clean -f -d # remove untracked
* git clean -f -x -d # CAUTION: as above but removes ignored files like config.
* git clean -fxd :/ # CAUTION: as above, but cleans untracked and ignored files through the entire repo (without :/, the operation affects only the current directory)
