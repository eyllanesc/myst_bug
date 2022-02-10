Baz
===

.. include:: bar.rst
   :start-after: contents-begin-rst
   :end-before: contents-end-rst

.. include:: bar.rst
   :start-after: references-begin-rst
   :end-before: references-end-rst

.. include:: foo.md
   :parser: myst_parser.sphinx_
   :start-after: <!-- contents-begin-md -->
   :end-before: <!-- contents-end-md -->

.. include:: foo.md
   :parser: myst_parser.sphinx_
   :start-after: <!-- references-begin-md -->
   :end-before: <!-- references-end-md -->
