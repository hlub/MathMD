MathMD -- Mathematical Mark Down
================================

**MathMD** is yet another attempt to unify or standardize the way of 
representing mathematical formulas digitally.
The major purpose is to unify conventions and symbols used in quick 
communication in comparison to generating typesetting-rich, beautifully crafted,
almost artistic pieces of mathematical writing where locations of every 
single pixel is carefully considered.
The goal is to have a practical alternative for the good old piece of paper 
and pen, which, rather sadly, still seems to be the most popular method for 
mathematical note taking, experimenting and communication.
The markups are meant to be easily written with a standar keyboard and the 
format is plain text.
MathMD adopts the idioms **easy-to-read** and **what-you-see-is-what-you-get** 
from the plain text markup syntaxes 
`reStructuredText <https://en.wikipedia.org/wiki/ReStructuredText>`_ and 
`Markdown <https://en.wikipedia.org/wiki/Markdown>`_, which have recently
gained a lot of popularity.

The project's major goals are:

* The markups are easy to read as is without any conversions (e.g. no converting to images)
* The markups are easy to write
* The markups offer practical alternative for the traditional piece of paper and pen
* The system does not restrict invention and use of of new symbols and structures

This project has been initiated and it is authorized by the Finnish Braille 
Authorities. The fundamental goal of the project is to make communication of
mathematics easier for visually impaired people. Nevetheless, the project's
outcome is definitely useful for others too, and the more widespread the
markups get the more it benefits the communication.

The project is still in its infancy. The work is based on the existing markup
languages and my personal experience. I lost my vision just before school 
but still had ambitions to math. Combined with the digitalization I had to 
invent my own way of writing maths -- something that I could use for 
making notes, communicate with teachers and other students and exams. After
ending my quite mathematically wighted studies of computer science,
I feel it is time to share and try tomake things easier for others.

However, the nature of this project require it to be open source.
Clearly the goals cannot be obtained by efforts of a signle person.
I don'w want to announce a new standard created by me and used by no one 
but a new standard created by us.
Further, the project needs to gain popularity to be of any use.

The following existing markup languages were considered while perparing MathMD:

* AsciiMath: an easy-to-write markup language for mathematics that offers automated conversion to images (website http://asciimath.org/)
* LaTeX: a document prepration system and typesetting language designed for printing or corresponding digital distribution. LaTeX is widely used in
academia for the communication and publication of scientific documents 
in many fields. (see wiki article `here <https://en.wikipedia.org/wiki/LaTeX>`_)
* programming languages: of course, many programming languages support simple equations written in plain text

.. note:: All of these approaches have a rather different objectives 
   and none of them is meant for replacement for paper and pen.

Documentations
--------------

The specifications are currently only available in Finnish.

* Specifications in Finnish (`PDF <docs/mathmd.pdf>`_)
* Specifications in Finnish (TeX `document <docs/mathmd.tex>` and `contents <docs/body.tex>`_)

Todo and future plans
---------------------

The proposed future plans:

* Translate to English
* Conver the documentation to other formats, maybe html or rst
* Translate from English to other languages?
* Automated conversions from/to LaTeX?

The documentation is still missing:

* Markup for metrics
* Physics
* Chemistry
* What else? please point out!
