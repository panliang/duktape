============================
reStructuredText conventions
============================

File extension
==============

Although ``.txt`` extension is probably technically correct for RST files,
use ``.rst`` for internal documentation for better compatibility with editors,
GitHub, etc.

Section markers
===============

Book level:

  #. Over- and underlined hash marks (``#``) for book title
  #. Over- and underlines stars (``*``) for book sub-title

File level:

  #. Over- and underlined equals signs (``=``) once at top of file (file topic)
  #. Underlined equals signs (``=``)
  #. Underlined minus signs (``-``)
  #. Underlined colons (``:``)
  #. Underlined periods (``.``)

The book level notation is reserved for future use.  It allows the
internal documentation to be easily built into a single HTML/PDF
file for ease of browsing.

Page breaks
===========

See http://comments.gmane.org/gmane.text.docutils.user/6473.

You can use::

  .. raw:: LaTeX
  
     \newpage

