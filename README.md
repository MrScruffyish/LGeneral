# LGeneral
A copy of the LGeneral https://lgames.sourceforge.io/LGeneral/ 

## SVN upstream

`lgeneral-svn/` is a Subversion working copy of:

    https://svn.code.sf.net/p/lgeneral/code/trunk

It is currently at revision 204. To fetch newer upstream changes:

    cd lgeneral-svn
    svn update

The bulky `.svn/pristine/` base-copy cache has been removed to keep the tree
compact. `svn update`, `svn checkout` and normal file access still work; if you
need `svn diff`, `svn revert` or merges, restore the cache with a fresh
checkout:

    cd ..
    mv lgeneral-svn lgeneral-svn-old
    svn checkout https://svn.code.sf.net/p/lgeneral/code/trunk lgeneral-svn
