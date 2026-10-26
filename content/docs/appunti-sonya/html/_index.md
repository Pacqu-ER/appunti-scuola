+++
date = '2026-10-04T17:16:36+02:00'
draft = false
title = 'Html'
+++

**`Hypertext Mark-up Language (HTML)`:** consente di sfruttare i vantaggi e le prestazioni dell’ipertesto. È diventato uno standard dell’architettura web.

Le specifiche del linguaggio sono stabilite dal **`World Wide Web Consortium (W3C)`**, l’ente che regola gli standard del Web, e sono consultabili alla pagina [w3.org](http://w3.org).

I WWW sono dei normali testi di caratteri e di conseguenza sono visibili e modificabili con qualunque `editor di testo`.

Un documento in formato Web può essere aperto con un **`Browser`**, sia un file `Locale` che `Remoto`. La visualizzazione è il risultato di un’elaborazione del Browser che interpreta i codici contenuti nel file e li trasforma in comandi per la costruzione della pagina → **`Rendering`**.

* **`Https`:** indica il protocollo http
* **`IDE` (`Integrated Development Environment`):** è un software che raccoglie in un unico programma tutti gli strumenti necessari per scrivere, modificare e testare del codice → scrivere il codice in modo molto più semplice

## Tag ##

È un **`Linguaggio Markup`** (come `XAML` e `XML`).  
Sono file di caratteri, in cui vengono aggiunti i codici di formattazione della pagina che prendono il nome di **`Tag`**.

Sono etichette di marcatura utilizzate per costruire la struttura scheletrica di una pagina web e dire al browser come mostrare i contenuti.

I tag in generale vengono scritti in minuscolo.

* **Parentesi angolari:** `<` e `>`.
* **Tag di apertura e chiusura:** un'apertura (es. `<b>`) e una chiusura con una barra inclinata (es. `</b>`).
* **Tag vuoti:** Alcuni elementi non hanno un tag di chiusura perché non racchiudono del testo (ad esempio `<br>` per andare a capo o `<hr>` per una linea orizzontale).
* **Attributi:** Possono contenere informazioni aggiuntive dentro il tag di apertura (come `src` in un'immagine o `href` in un link) per specificare il comportamento dell'elemento.
* **`doctype`:** In testa al documento html, viene scritto in maiuscolo.

## Struttura di una pagina ##

Una pagina ha due sezioni principali:
* `<head>...</head>` per le intestazioni
* `<body>...</body>` per il corpo

Generalmente tutti questi sono inclusi all’interno di `<html>...</html>`. Questo perché alcuni browser necessitano di istruzioni su quale posizione di testo interpretare come HTML.

→ A seconda della lingua del sito, può essere utile specificarla come attributo: `<html lang="it">`
