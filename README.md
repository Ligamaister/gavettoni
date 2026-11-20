# Gavettoni dietro le quinte

Un gioco da browser. Sei una scimmietta in piazza del Duomo a Firenze, hai palloncini d'acqua a volontà e 90 secondi per bagnare più gente che puoi.

**Si gioca qui, senza installare niente → https://ligamaister.github.io/gavettoni/**

Funziona da computer e da telefono. Chi apre il link nello stesso momento gioca nella stessa piazza.

## Come si gioca

- Da computer corri con WASD o con le frecce, guardi col mouse, tiri col clic e salti con la barra.
- Da telefono corri con la leva a sinistra, guardi trascinando il dito e tiri col bottone giallo.
- Il cerchio al centro dice dove cade il gavettone. Più alzi lo sguardo, più va lontano.
- Un colpo da lontano vale doppio. Tre centri di fila raddoppiano i punti, sei li triplicano.

La prima volta il gioco si presenta da solo, un passo alla volta, e la presentazione si può rivedere dal cartello d'inizio.

## Chi c'è in piazza

- **I passanti.** Fiorentini, turisti e radical chic valgono un punto.
- **Il maranza.** Se lo bagni ti corre dietro, e se ti prende sono 2 punti in meno.
- **Il vigile.** Vale il triplo, ma se ti acchiappa ti fa la multa, 4 punti in meno.
- **Il Bruttaio.** Gira col suo carroccio, e sopra c'è una tipa col sacchetto di carta in testa. Se dice «Come sei brutto, ora ti metto nel mio carroccio», scappa.
- **Il ciuco del Cioni.** Secco secco alla morte, passa piano piano.
- **Chiarina.** Vestitino estivo, tutta felice, a chi le passa vicino dice «Ho fatto finuccia!».
- **Il Doni.** Jeans, marsupio sul davanti e un sorriso che non finisce più.
- **Nonno Sugo.** Un signore norvegese con la passione per le scimmiette. Ti gira attorno e ti studia.

Chi bagna gli ultimi cinque nella stessa partita prende 10 punti in più.

## Giocare con gli amici

Basta mandare il link. Sul cartello d'inizio ognuno scrive un soprannome, ed è l'unica cosa che gli altri vedono di lui. Con il bottone «Piazza privata» si apre una piazza a parte, dove entra solo chi riceve quel link.

I giocatori si collegano direttamente fra loro, da browser a browser, senza passare da un server del gioco. Su certe reti chiuse (uffici, alberghi) il collegamento può non riuscire, e allora si gioca da soli.

## Di cosa è fatto

Tutto il gioco è il file `index.html`. La piazza è ricostruita da dati aperti.

- Sagome degli edifici e strade © [OpenStreetMap](https://www.openstreetmap.org/copyright) contributors, licenza ODbL. I dati degli edifici scritti dentro la pagina derivano da OpenStreetMap e restano sotto la stessa licenza.
- Altezze degli edifici dal DSM 2021 della Regione Toscana, licenza CC BY 4.0.
- Facciate descritte a mano guardando le foto della piazza.
- Grafica 3D con [three.js](https://threejs.org/), collegamento fra giocatori con [Trystero](https://github.com/dmotz/trystero), caratteri Bangers e Inter da Google Fonts.
