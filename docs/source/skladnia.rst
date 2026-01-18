===============================
Elementy dokumentacji RtD
===============================

Poniższy dokument prezentuje podstawowe elementy składni
języka **reStructuredText**, używanego w dokumentacji
tworzonej na platformie **Read the Docs**.

Nagłówki tekstowe (poziomy 1–4)
===============================

Przykład nagłówka poziomu pierwszego
===================================

Przykład nagłówka poziomu drugiego
----------------------------------

Przykład nagłówka poziomu trzeciego
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Przykład nagłówka poziomu czwartego
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


Akapit tekstowy (treść)
======================

Akapit tekstowy służy do opisywania funkcjonalności projektu,
instrukcji obsługi lub innych informacji.
Może zawierać wiele zdań zapisanych w kilku liniach.


Akapit informacyjny (Note, Tip)
===============================

.. note::
   Ten blok służy do przekazywania ważnych informacji
   dotyczących dokumentacji.

.. tip::
   W tym miejscu można umieścić praktyczną wskazówkę
   dla użytkownika.


Fragment kodu (liniowy, blokowy)
================================

Kod liniowy
-----------

Polecenie ``git pull`` umożliwia pobranie najnowszych zmian
z repozytorium.

Kod blokowy
-----------

.. code-block:: python

   for i in range(3):
       print("Read the Docs")


Odnośnik (lokalny RtD, zewnętrzny)
=================================

Odnośnik zewnętrzny
------------------

`Oficjalna strona Read the Docs <https://readthedocs.org>`_

Odnośnik lokalny (inna podstrona)
--------------------------------

Więcej informacji znajduje się na stronie :doc:`autor`.


Listy (numerowana, wypunktowana, definicji)
===========================================

Lista wypunktowana
------------------

- dokumentacja
- repozytorium
- konfiguracja

Lista numerowana
----------------

1. Utworzenie repozytorium
2. Dodanie plików `.rst`
3. Publikacja na Read the Docs

Lista definicji
---------------

Sphinx
   Narzędzie do generowania dokumentacji.

Read the Docs
   Platforma hostująca dokumentacje projektów.


Obraz (z alternatywnym tekstem oraz podpisem)
=============================================

.. figure:: ./obraz.jpg
   :alt: Przykładowa grafika
   :align: center

   Przykładowy obraz użyty w dokumentacji.


Tabela
======

+----------------+----------------------------+
| Element        | Zastosowanie               |
+================+============================+
| Nagłówek       | Tytuł sekcji               |
+----------------+----------------------------+
| Lista          | Grupowanie informacji      |
+----------------+----------------------------+
| Kod            | Prezentacja przykładu      |
+----------------+----------------------------+
