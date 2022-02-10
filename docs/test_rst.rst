Test ReStructuredText
=====================

Hello world `Test <test2>`_.

.. _test2: http://example.com/

Include md
~~~~~~~~~~

.. include:: sample_rst.rst
   :start-after: contents-begin-rst
   :end-before: contents-end-rst

.. include:: sample_rst.rst
   :start-after: references-begin-rst
   :end-before: references-end-rst

Include rst
~~~~~~~~~~~

.. include:: sample_md.md
   :parser: myst_parser.sphinx_
   :start-after: <!-- contents-begin-md -->
   :end-before: <!-- contents-end-md -->

.. include:: sample_md.md
   :parser: myst_parser.sphinx_
   :start-after: <!-- references-begin-md -->
   :end-before: <!-- references-end-md -->
