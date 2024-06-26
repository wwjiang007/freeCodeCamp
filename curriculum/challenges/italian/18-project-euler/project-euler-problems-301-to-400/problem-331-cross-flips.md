---
id: 5900f4b71000cf542c50ffca
title: 'Problema 331: ribaltamenti a croce'
challengeType: 1
forumTopicId: 301989
dashedName: problem-331-cross-flips
---

# --description--

N×N dischi sono posizionati su un tabellone da gioco quadrato. Ogni disco ha un lato nero e un lato bianco.

A ogni turno, si può scegliere un disco e capovolgere tutti i dischi nella stessa riga e la stessa colonna di questo disco: così $2 × N - 1$ dischi vengono capovolti. Il gioco termina quando tutti i dischi mostrano il loro lato bianco. L'esempio seguente mostra una partita su una griglia 5×5.

<img alt="animazione che mostra il gioco su un tabellone 5x5" src="https://cdn.freecodecamp.org/curriculum/project-euler/cross-flips.gif" style="background-color: white; padding: 10px; display: block; margin-right: auto; margin-left: auto; margin-bottom: 1.2rem;" />

Si può dimostrare che 3 è il numero minimo di turni per finire questo gioco.

Il disco in basso a sinistra sul tabellone $N×N$ ha coordinate (0, 0); il disco in basso a destra ha coordinate ($N - 1$,$0$) e il disco in alto a sinistra ha coordinate ($0$,$N - 1$).

Sia $C_N$ la seguente configurazione di un tabellone con $N × N$ dischi: un disco in ($x$, $y$) che soddisfa $N - 1 \le \sqrt{x^2 + y^2} \lt N$, mostra il suo lato nero; altrimenti, mostra il suo lato bianco. $C_5$ è mostrato sopra.

Sia $T(N)$ il numero minimo di turni per completare una partita che parte dalla configurazione $C_N$ o 0 se la configurazione $C_N$ è irrisolvibile. Abbiamo mostrato che $T(5) = 3$. Ti viene anche dato che $T(10) = 29$ e $T(1\\,000) = 395\\,253$.

Trova $\displaystyle \sum_{i = 3}^{31} T(2^i - i)$.

# --hints--

`crossFlips()` dovrebbe restituire `467178235146843500`.

```js
assert.strictEqual(crossFlips(), 467178235146843500);
```

# --seed--

## --seed-contents--

```js
function crossFlips() {

  return true;
}

crossFlips();
```

# --solutions--

```js
// solution required
```
