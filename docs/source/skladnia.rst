Nagłówki tekstowe (poziomy 1–4)
===============================

Poziom pierwszy nagłówka
=======================

Poziom drugi nagłówka
--------------------

Poziom trzeci nagłówka
~~~~~~~~~~~~~~~~~~~~~

Poziom czwarty nagłówka
^^^^^^^^^^^^^^^^^^^^^^


Akapit tekstowy (treść)
======================

Akapit tekstowy jest podstawową formą przekazywania
informacji w dokumentacji.
Może opisywać działanie programu, sposób instalacji
lub zasady użytkowania aplikacji.


Akapit informacyjny (Note, Tip)
===============================

.. note::
   Dokumentacja powinna być czytelna
   i zrozumiała dla użytkownika.

.. tip::
   Warto stosować krótkie zdania
   i przejrzystą strukturę.


Fragment kodu (liniowy, blokowy)
================================

Kod liniowy
-----------

Aby uruchomić serwer lokalny, użyj polecenia ``python app.py``.

Kod blokowy
-----------

.. code-block:: bash

   git add .
   git commit -m "Pierwszy commit"
   git push


Odnośnik (lokalny RtD, zewnętrzny-inny serwis)
=============================================

Odnośnik do zewnętrznej strony
------------------------------

`Strona Python <https://www.python.org>`_

Odnośnik do innej części dokumentacji
-------------------------------------

Szczegóły projektu opisano na stronie :doc:`autor`.


Listy (numerowana, wypunktowana, definicji)
===========================================

Lista wypunktowana
------------------

- instalacja środowiska
- konfiguracja projektu
- uruchomienie aplikacji

Lista numerowana
----------------

1. Pobierz repozytorium
2. Otwórz projekt w edytorze
3. Uruchom dokumentację

Lista definicji
---------------

Repozytorium
   Miejsce przechowywania kodu źródłowego.

Dokumentacja
   Opis sposobu działania projektu.


Obraz (z alternatywnym tekstem oraz podpisem)
=============================================

.. figure:: ./obraz.jpg
   :alt: Schemat projektu
   :align: center

   Schemat przedstawiający strukturę projektu.


Tabela
======

+-------------------+----------------------+
| Plik              | Przeznaczenie        |
+===================+======================+
| index.rst         | Strona główna        |
+-------------------+----------------------+
| skladnia.rst      | Opis składni         |
+-------------------+----------------------+
| autor.rst         | Informacje o autorze |
+-------------------+----------------------+
