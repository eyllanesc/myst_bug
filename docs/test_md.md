# Test Markdown

Hello world [Test][test1].

[test1]: http://example.com/

## Include md

```{include} sample_md.md
---
start-after: <!-- contents-begin-md -->
end-before: <!-- contents-end-md -->
---
```

```{include} sample_md.md
---
start-after: <!-- references-begin-md -->
end-before: <!-- references-end-md -->
---
```

## Include rst

```{eval-rst}
.. include:: sample_rst.rst
   :start-after: contents-begin-rst
   :end-before: contents-end-rst

.. include:: sample_rst.rst
   :start-after: references-begin-rst
   :end-before: references-end-rst
```
