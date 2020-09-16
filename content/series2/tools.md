---
title: "Instrumenten"
date: 2020-09-15T19:02:27+02:00
---
Leren schaken gaat beter als we een computer bij de hand hebben:

- De stukken staan sneller opgesteld
- Je kan zetten terugnemen
- Je kan stellingen analyseren met behulp van de computer.

Toch een waarschuwing! Vergeet zelf niet te denken ...

## FEN

Al in de 19e eeuw werd de [Forsyth-Edwards Notation](https://nl.wikipedia.org/wiki/Forsyth-Edwards_Notation) uitgevonden. Het is een handige - zij het wat cryptische manier - om met 1 karakterrij een schaakpositie vast te leggen. Deze notatie weet ook wie al gerokeerd heeft, wie aan zet is en of er en-passant mag worden geslagen.

De meeste schaaksoftware kan omgaan met *FEN*: er zijn mogelijkheden om - dikwijls via *Knip en Plak* een schaakpartij op te zetten.
Je hoeft zelf niet te leren hoe een dergelijk FEN in elkaar zit (hoewel dat niet verboden is :-)

Voorbeeld:

FEN: `8/8/4kpp1/3p1b2/p6P/2B5/6P1/6K1 b - - 0 47`

Deze FEN staat voor de volgende positie:

![`8/8/4kpp1/3p1b2/p6P/2B5/6P1/6K1 b - - 0 47`](/chess/images/ab20ea7b89eb7040b1c61bfac97581952baa6e0d6cfa809e6a351925.svg)


<div id="board"></div>
        <script>
            PGNV.pgnView('board',{ pgn: '1. e4 e5 2. Nf3 Nc6 3. Bb5', pieceStyle: 'merida' });
        </script>