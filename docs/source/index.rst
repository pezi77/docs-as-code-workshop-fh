.. include:: ../README.rst

Welcome to the docs-as-code workshop docs
=========================================

.. note::

   This is where we will write our docs today

Contents
--------

.. toctree::

   Home <self>
   intro
   general

Links
-----

Here are some useful links on how to write reStructured Text:

* https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html
* https://docutils.sourceforge.io/rst.html
* https://www.ericholscher.com/blog/2016/jul/1/sphinx-and-rtd-for-writers/


Basic formatting
----------------

Here are the basic formatting options:

Chapter 1 Title
===============

Section 1.1 Title
-----------------

Subsection 1.1.1 Title
~~~~~~~~~~~~~~~~~~~~~~

Section 1.2 Title
-----------------

Chapter 2 Title
===============


Paragraphs
==========
The paragraph (ref) is the most basic block in a reST document. Paragraphs are simply chunks of text separated by one or more blank lines. As in Python, indentation is significant in reST, so all lines of the same paragraph must be left-aligned to the same level of indentation.


Inline markup
=============
The standard reST inline markup is quite simple: use

one asterisk: *text* for emphasis (italics),

two asterisks: **text** for strong emphasis (boldface), and

backquotes: ``text`` for code samples.


Lists and Quote-like blocks
===========================
List markup (ref) is natural: just place an asterisk at the start of a paragraph and indent properly. The same goes for numbered lists; they can also be autonumbered using a # sign:

* This is a bulleted list.
* It has two items, the second
  item uses two lines.

1. This is a numbered list.
2. It has two items too.

#. This is a numbered list.
#. It has two items too.
Nested lists are possible, but be aware that they must be separated from the parent list items by blank lines:

* this is
* a list

  * with a nested list
  * and some subitems

* and here the parent list continues


Images
======

.. image:: images/example-image.png
