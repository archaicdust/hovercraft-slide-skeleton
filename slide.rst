
:data-transition-duration: 1500
:css: hovercraft.css

:title: tig (Git)

----

tig (A front-end to Git)
============================

::

    archaicdust@gmail.com

----

tig History view
====================

::

  >>> git log

  >>> tig

  >>> tig --all

  h (help view)

  j/k

  / search summary or author

  t open tree view

  Enter on a commit

    a split diff view

  shift-S in the main veiw

    go to status view

----

tig view
=============

::

    h Show help view

    m  Show main view

    s, S  Show status view

    l  Show log view
    t  Show tree view

    r  Show refs view

    c  Show stage view
    y  Show stash view

    d  Show diff view

    b  Show blame view
    f  Show blob view
    g  Show grep view
    p  Show pager view

----

tig
=================

::

  R, F5 Reload and refresh view

  O Maximize the current view

  <Tab> view-next

  q Close the current view
  Q Close all views and quit

  < Go back to the previous view state

  <Ctrl-U> move-page-up

  <Ctrl-D> move-page-dow

----

tig Status view
===================

::

  >>> tig status


  u

    stage or unstage file

  !

    revert all uncommitted changes to that file


  Enter on a file

    j, k

    @ (navigate chunk by chunk)

    u (stage the current diff chunk)

    @@

    1 (stage a single line)


  Shift-C (commit)


----

tig stash
=============

P (git stash pop)

! (git stash drop)



----

tig Blame view
==================


>>> tig blame <file>

::

  Just select a line and press Enter,
  and it will show you the last commit that touched that line.

  t tree view

  S status view

  @ 



-----

Reference
==============

`git? tig! <http://blogs.atlassian.com/2013/05/git-tig/>`_



