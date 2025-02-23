---
title: Esercizi Esami
---

## Successione Numerica

??? question "Domanda 1"

	1. Sia data la successione numerica reale:

	$$
	\begin{array}{c}
	    a_n = \frac{(-1)^n}{arctan(n)+2}
	\end{array}
	$$

	- la successione $a_n$ è infinitesima (V/F)
	- la successione $b_n = |a_n|$ ammette limite per $n \to \infty$ (V/F)
	- la successione $a_n$ è limitata (V/F)
	- $a_n$ è indeterminata (V/F)

	---

	<big>Individuare il Limite della Successione</big>

	- Il numeratore della successione è $(-1)^n$, che alterna tra $-1$ e $1$ a seconda del valore di $n$:
		- Quando $n$ è pari, $(-1)^n = 1$.
		- Quando $n$ è dispari, $(-1)^n = -1$.
	- Quindi la successione oscilla tra numeri positivi e negativi.
	- La funzione $arctan(n)$ tende a $\frac{\pi}{2}$ quando $n \to \infty$. Infatti:

	$$
	\begin{array}{c}
	    \displaystyle \lim_{n \to \infty} arctan(n) = \frac{\pi}{2}
	\end{array}
	$$

	- Di conseguenza, $arctan(n) + 2$ tende a $\frac{\pi}{2} + 2 \approx 2.57$ quando $n$ diventa molto grande.
	- Ora, cerchiamo di capire cosa succede alla successione $a_n$ quando $n$ tende all'infinito.
	- Quando $n \to \infty$:
		- Il numeratore $(-1)^n$ continua ad oscillare tra $-1$ e $1$.
		- Il denominatore $arctan(n) + 2$ tende ad un valore fisso di circa $2.57$.
	- Poiché il numeratore oscilla tra $-1$ ed $1$ ed il denominatore si stabilizza su un numero fisso, possiamo dire che la successione $a_n$ non ha un limite unico. Anzi, i termini della successione continuano ad oscillare tra valori positivi e negativi, ma non si stabilizzano mai su un valore fisso.

	$$
	\begin{array}{c}
	    \displaystyle \lim_{n \to \infty} a_n = \text{ non esiste.}
	\end{array}
	$$

	---

	<big>Risposte al Vero/Falso</big>

	- :x: **1A** è **FALSA** ― Perchè $a_n$ non è infinitesima: si definisce infinitesima una successione il cui limite tende a 0; in questo caso, la successione oscilla tra dei valori positivi e negativi, quindi non è infinitesima.
	- :white_check_mark: **1B** è **VERA** ― Perchè $b_n = |a_n|$ ammette limite per $n \to \infty$: visto che la successione ha un limite che oscilla tra valori positivi e negativi, possiamo affermare che la successione ammette un limite.
	- :white_check_mark: **1C** è **VERA** ― Perchè $a_n$ è limitata: i termini di $a_n$ oscillano tra numeri positivi e negativi, ma l'ampiezza di questi termini diventa sempre più piccola, poiché il denominatore cresce man mano che $n$ aumenta. Inoltre, il denominatore è sempre maggiore di un certo valore positivo (poiché $arctan(n) + 2$ tende ad un numero positivo e stabile), quindi i termini di $a_n$ sono sempre limitati tra due valori.
	- :white_check_mark: **1D** è **VERA** ― Perchè $a_n$ è indeterminata: come detto in precedenza, il limite di $a_n$ si alterna tra valori, quindi rispetta la definizione di Successione Indeterminata.
	  
## Funzioni