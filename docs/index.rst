.. module:: mypackage

=================================
Some Python Callables That I Like
=================================

In the Standard Library
-----------------------

As :samp:`\`{name}()\``:

- `repr()` — not linked
- `str()` — not linked
- `str.splitlines()` — not linked

As :samp:`\`{name}\``:

- `repr` — linked
- `str` — linked
- `str.splitlines` — linked

As :samp:`:py:{reftype}:\`{name}()\``:

- :py:func:`repr()` — linked
- :py:class:`str()` — not linked
- :py:meth:`str.splitlines()` — linked

As :samp:`:py:{reftype}:\`{name}\``:

- :py:func:`repr` — linked
- :py:class:`str` — linked
- :py:meth:`str.splitlines` — linked


In My Package
-------------

As :samp:`\`{name}()\``:

- `afunc()` — not linked
- `AClass()` — not linked
- `AClass.amethod()` — not linked

As :samp:`\`{name}\``:

- `afunc` — linked
- `AClass` — linked
- `AClass.amethod` — linked

As :samp:`:py:{reftype}:\`{name}()\``:

- :py:func:`afunc()` — linked
- :py:class:`AClass()` — not linked
- :py:meth:`AClass.amethod()` — linked

As :samp:`:py:{reftype}:\`{name}\``:

- :py:func:`afunc` — linked
- :py:class:`AClass` — linked
- :py:meth:`AClass.amethod` — linked
