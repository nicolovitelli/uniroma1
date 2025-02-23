---
title: Successione
---

## Successioni Numeriche

!!! abstract "Definizione ― Successione Numerica"
	Una successione numerica è una lista di numeri organizzati in un ordine specifico. La successione può essere finita o infinita. Di solito, una successione infinita è rappresentata come $(a_n)$, dove $a_n$ è l'elemento che occupa la posizione $n$ della successione.

??? example "Esempio"
	$$
    \begin{array}{c}
        a_1 = 2, a_2 = 3, a_3 = 5, a_4 = 8, \dots
    \end{array}
	$$

	- In questo caso, la successione è infinita, ed ogni termine aumenta di $2$ rispetto al precedente.

	$$
    \begin{array}{c}
        b_1 = 1, b_2 = 2, b_3 = 3
    \end{array}
	$$

	- Questa è una successione finita che termina con il terzo termine.

## Successione Convergente

!!! abstract "Definizione ― Successione Convergente"
	Una successione è convergente se, quando l'indice $n$ cresce all'infinito (cioè $n \to \infty$), i termini della successione si avvicinano sempre più ad un numero fisso, che chiameremo **limite** della successione.

??? example "Esempio"
	$$
    \begin{array}{c}
        a_n = \frac{1}{n}
    \end{array}
	$$

	- I termini di questa successione sono:
	$$
    \begin{array}{c}
        a_1 = \frac{1}{1} = 1, \\
        a_2 = \frac{1}{2} = 0.5, \\
        a_3 = \frac{1}{3} = 0.33, \\
        a_4 = \frac{1}{4} = 0.25, \dots
    \end{array}
	$$

	- Man mano che $n$ cresce, i valori di $a_n$ diventano sempre più piccoli e si avvicinano a $0$. Quindi possiamo dire che:
	$$
    \begin{array}{c}
        \displaystyle \lim_{n \to \infty} a_n = 0
    \end{array}
	$$

	- In questo caso, la successione è convergente ed il suo limite è $0$.

## Successione Divergente

!!! abstract "Definizione ― Successione Divergente"
	Una successione divergente è una successione che non tende ad un numero definito. In altre parole, i termini della successione non si avvicinano mai ad un valore fisso, ma possono crescere senza limiti o alterare valori senza stabilizzarsi su un numero.

	Una successione è divergente in vari modi:

	- **Infinitamente crescente**: la successione tende a $+\infty$.
	- **Infinitamente decrescente**: la successione tende a $-\infty$.
	- **Alternante senza limite**: la successione oscilla tra i valori positivi e negativi senza convergere ad un valore preciso. 

??? example "Esempio ― Successione che tende a $+\infty$"
	$$
    \begin{array}{c}
        a_n = n
    \end{array}
	$$

	- Questa successione cresce indefinitamente man mano che $n$ aumenta, quindi possiamo dire che:

	$$
    \begin{array}{c}
        \displaystyle \lim_{n \to \infty} n = +\infty
    \end{array}
	$$

	- Questa è una successione divergente che tende a $+\infty$.

??? example "Esempio ― Successione che tende a $-\infty$"
	$$
    \begin{array}{c}
        a_n = -n
    \end{array}
	$$

	- Questa successione cresce negativamente all'infinito. Infatti:

	$$
    \begin{array}{c}
        \displaystyle \lim_{n \to \infty} n = -\infty
    \end{array}
	$$

	- Anche questa è una successione divergente, ma tende a $-\infty$.

??? example "Esempio ― Successione alternante senza limite"
	$$
    \begin{array}{c}
        a_n = (-1)^n
    \end{array}
	$$

	- Questa successione alterna tra $1$ e $-1$. Non si avvicina a nessun valore, ma continua ad oscillare senza fermarsi, quindi possiamo dire che:

	$$
    \begin{array}{c}
        \displaystyle \lim_{n \to \infty} (-1)^n \text{ non esiste.}
    \end{array}
	$$

	- Questa è una successione divergente senza un limite definito, poiché i suoi termini non si stabilizzano su un valore fisso.

## Successione Infinitesima

!!! abstract "Definizione ― Successione Infinitesima"
	Una successione infinitesima è una successione di numeri che si avvicina sempre più a zero man mano che i suoi termini diventano più lontani, cioè quando $n$ cresce all'infinito.
	
	$$
    \begin{array}{c}
        \displaystyle \lim_{n \to \infty} a_n = 0
    \end{array}
	$$

!!! note "Differenza tra Infinitesima e Convergente"
	- Una successione convergente può convergere a qualsiasi valore finito $\mathop{L}$ (non necessariamente zero). La convergenza a $\mathop{L}$ significa che i termini della successione si avvicinano al valore $\mathop{L}$ quando $\mathop{L}$ cresce.
	- Una successione infinitesima è un caso particolare di successione convergente in cui il limite della successione è zero. Quindi, tutte le successioni infinitesime sono convergenti, ma non tutte le successioni convergenti sono infinitesime.

??? example "Esempio"
	- Considerata la successione $a_n = \frac{1}{n}$, cioè i termini della successione sono:

	$$
    \begin{array}{c}
        a_1 = 1, a_2 = \frac{1}{2}, a_3 = \frac{1}{3}, a_4 = \frac{1}{4}, \dots
    \end{array}
	$$

	- Man mano che $n$ cresce, i termini si avvicinano sempre di più a zero. Per esempio:
		- Quando $n = 10, a_{10} = \frac{1}{10} = 0.1$
		- Quando $n = 100, a_{100} = \frac{1}{100} = 0.01$
		- Quando $n = 1000, a_{1000} = \frac{1}{1000} = 0.001$
	- In effetti, quando $n$ diventa molto grande, il termine $a_n = \frac{1}{n}$ si avvicina sempre di più a zero, e questo è un esempio di una successione infinitesima. Infatti, possiamo dire che:

	$$
    \begin{array}{c}
        \displaystyle \lim_{n \to \infty} \frac{1}{n} = 0
    \end{array}
	$$

## Successione Limitata

!!! abstract "Definizione ― Successione Limitata"
	Una successione limitata è una successione i cui termini sono contenuti all'interno di un intervallo finito:

	$$
    \begin{array}{c}
        m \leq a_n \leq M \text{ per ogni } n
    \end{array}
	$$

	Quindi, i termini della successione sono compresi tra due valori $m$ e $M$, senza mai superare questi limiti. Questo significa che i valori della successione non diventano mai troppo grandi né troppo piccoli.

??? example "Esempio"
	- Considerata la successione $a_n = \frac{(-1)^n}{n}$. I suoi termini sono:

	$$
    \begin{array}{c}
        a_1 = -1, a_2 = 0.5, a_3 = - \frac{1}{3}, a_4 = 0.25, a_5 = - \frac{1}{5}, \dots
    \end{array}
    $$

    - In questo caso, la successione oscilla tra valori positivi e negativi.
    - Tuttavia, i suoi termini diventano sempre più piccoli in valore assoluto man mano che $n$ cresce.
    - Osservando i valori assoluti $|a_n| = \frac{1}{n}$, vediamo che questi termini si avvicinando a zero, ma non diventano mai superiori a $1$. Quindi si può affermare che:

	$$
    \begin{array}{c}
        |a_n| \leq 1 \text{ per ogni n.}
    \end{array}
    $$

    E poiché i valori sono sempre compresi tra $1$ e $-1$, si può concludere che la successione è limitata.

## Successione Indeterminata

!!! abstract "Definizione ― Successione Indeterminata"
	Una successione indeterminata è una successione che non ha un comportamento regolare e non tende ad un valore specifico. I suoi termini possono:

	- Oscillare senza mai stabilizzarsi su un valore fisso.
	- Crescere senza un limite definito.

??? example "Esempio"
	- Una successione come $a_n = (-1)^n$ è indeterminata. I suoi termini oscillano tra $1$ e $-1$ senza mai stabilirsi su un valore fisso. Non ha un limite definito perchè non tende ad un numero specifico.

	$$
    \begin{array}{c}
        a_1 = 1, a_2 = -1, a_3 = 1, a_4 = 1, \dots
    \end{array}
    $$

## Successione Crescente

!!! abstract "Definizione ― Successione Crescente"
	Una successione crescente è una successione in cui ogni termine è maggiore o uguale al termine precedente. In altre parole, per ogni $n$, abbiamo:

	$$
    \begin{array}{c}
        a_n \leq a_n+1 \text{ per ogni } n
    \end{array}
    $$


??? example "Esempio"
	$$
    \begin{array}{c}
        a_n = n
    \end{array}
	$$

	- Quando $n = 1, a_1 = 1$
	- Quando $n = 2, a_2 = 2$
	- $\dots$
	- Si può notare che, per ogni $n, a_n \leq a_{n+1}$, quindi la successione è crescente perchè ogni termine è maggiore o uguale al termine precedente.