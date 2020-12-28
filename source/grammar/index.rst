Grammar
=======

OpenQASM 3.0 includes two reference grammars using ANTLR and Lark.

ANTLR
-----

Grammar specification based in ANTLR_ parser generator. This supports (as of
the time of writing):
- Java
- C#
- Python 2 and 3
- JavaScript
- Go
- C++
- Swift
- PHP
- DART

.. _ANTLR: https://www.antlr.org/

[WIP]

.. literalinclude:: qasm3.g4
   :language: antlr
   :linenos:

Lark
----

Grammar specification based in Lark_ parser generator. This supports (as of the
time of writing):
- Python 3
- Julia

.. _Lark: https://github.com/lark-parser/lark

[WIP]

.. literalinclude:: qasm3.lark
   :linenos: