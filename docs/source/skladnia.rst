=================================
Składnia elementów dokumentu RtD
=================================

Dokument przedstawia podstawową składnię języka
**reStructuredText (reST)** wykorzystywanego na platformie
**Read the Docs**.

Nagłówki tekstowe
=================

Nagłówek poziom 1
=================

Nagłówek poziom 2
================

Nagłówek poziom 3
----------------

Nagłówek poziom 4
~~~~~~~~~~~~~~~~

Akapit tekstowy
===============

To jest przykładowy akapit tekstowy.
Służy do opisywania treści dokumentacji.
Może składać się z kilku zdań.

Akapit informacyjny
==================

.. note::
   To jest akapit informacyjny typu NOTE.

.. tip::
   To jest akapit informacyjny typu TIP.

Fragment kodu
=============

Kod liniowy
-----------

Polecenie ``git status`` wyświetla aktualny stan repozytorium.

Kod blokowy
-----------

.. code-block:: python

   def hello():
       print("Hello Read the Docs")

Odnośniki
=========

Odnośnik lokalny (Read the Docs)
-------------------------------

:doc:`autor`

Odnośnik zewnętrzny
------------------

`GitHub <https://github.com>`_

Listy
=====

Lista wypunktowana
------------------

- element pierwszy
- element drugi
- element trzeci

Lista numerowana
----------------

1. punkt pierwszy
2. punkt drugi
3. punkt trzeci

Lista definicji
---------------

GitHub
   Platforma do hostowania repozytoriów Git.

Read the Docs
   Platforma do publikowania dokumentacji projektów.

Obraz
=====

.. figure:: _static/obraz.png
   :alt: Przykładowy obraz
   :align: center

   Przykładowy podpis pod obrazem

Tabela
======

+-----------+---------------------------+
| Element   | Opis                      |
+===========+===========================+
| Nagłówek  | Tytuł sekcji              |
+-----------+---------------------------+
| Akapit    | Treść dokumentu           |
+-----------+---------------------------+
| Kod       | Fragment programu         |
+-----------+---------------------------+
