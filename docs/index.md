# Index

```{toctree}
---
hidden:
maxdepth: 1
---
foo
bar
baz
```

Hello world [Test1][test1].

[test1]: http://example.com/

```{include} foo.md
---
start-after: <!-- contents-begin-md -->
end-before: <!-- contents-end-md -->
---
```

```{include} foo.md
---
start-after: <!-- references-begin-md -->
end-before: <!-- references-end-md -->
---
```

```{eval-rst}
.. include:: bar.rst
   :start-after: contents-begin-rst
   :end-before: contents-end-rst

.. include:: bar.rst
   :start-after: references-begin-rst
   :end-before: references-end-rst
```
