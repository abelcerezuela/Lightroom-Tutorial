============================================================
Adobe Photoshop Lightroom: how to make a basic photo editing
============================================================

.. sectnum::

.. contents:: Table of contents

What is Adobe Photoshop Lightroom?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Adobe Lightroom (officially Adobe Photoshop Lightroom) is a family of image organization and image manipulation software developed by Adobe Systems for Windows and macOS. It allows viewing, organizing and editing large numbers of digital images. 

Lightroom's edits are non-destructive. Despite sharing its name with Adobe Photoshop, it cannot perform many Photoshop functions such as photo manipulation (adding, removing or altering the appearance of individual image items), rendering text or 3D objects on images, or modifying individual video frames. Lightroom is not a file manager like Adobe Bridge. It cannot operate on files unless they are imported into its database first, and only in recognized image formats.

- are easy to read in text editor and
- can be *automatically* converted to
 
  - html and 
  - latex (and therefore pdf)

What is it good for?
~~~~~~~~~~~~~~~~~~~~

reStructuredText can be used, for example, to

- write technical documentation (so that it can easily be offered as a
  pdf file or a web page)

- create html webpages without knowing html 

- to document source code

Show me some formatting examples
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can highlight text in *italics* or, to provide even more emphasis
in **bold**. Often, when describing computer code, we like to use a
``fixed space font`` to quote code snippets.

We can also include footnotes [1]_. We could include source code files
(by specifying their name) which is useful when documenting code. We
can also copy source code verbatim (i.e. include it in the rst
document) like this::

  int main ( int argc, char *argv[] ) {
      printf("Hello World\n");
      return 0;
  }

We have already seen at itemised list in section `What is it good
for?`_. Enumerated list and descriptive lists are supported as
well. It provides very good support for including html-links in a
variety of ways. Any section and subsections defined can be linked to,
as well.


Where can I learn more?
~~~~~~~~~~~~~~~~~~~~~~~

reStructuredText is described at
http://docutils.sourceforge.net/rst.html. We provide some geeky small
print in this footnote [2]_.


Show me some more stuff, please
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

We can also include figures:

.. figure:: image.png
   :width: 300pt


   The magnetisation in a small ferromagnetic disk. The diametre is of the order of 120 nanometers and the material is Ni20Fe80. Png is a file format that is both acceptable for html pages as well as for (pdf)latex.

---------------------------------------------------------------------------

.. [1] although there isn't much point of using a footnote here.

.. [2] Random facts: 

  - Emacs provides an rst mode 
  - when converting rst to html, a style sheet can be provided (there is a similar feature for latex)
  - rst can also be converted into XML
  - the recommended file extension for rst is ``.txt``
