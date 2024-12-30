---
title: Modulo 8
---

## Cardinalità
!!! abstract "Definizione ― Numeri Transfiniti"
    Sono definiti Numeri Transfiniti quei numeri che vanno oltre l'infinito.

!!! abstract "Definizione ― Equipotenza"
    $A$ si dice equipotente a $B$ se esiste una biiezione $A \rightarrow B$.

!!! abstract "Definizione ― Cardinalità"
    La Cardinalità di un insieme $A$ indicata con $|A|$, è la classe di equipotenza (*numero di elementi*) di $A$.

    $$
    \begin{array}{c}
    |A| \leq |B| \text{ se esiste } f \text{ iniettiva } A \rightarrow B \\
    \text{invece, se } |A| \leq |B| \text{ e } |B| \leq |A|, \text{ allora } |A| = |B|
    \end{array}
	$$

!!! abstract "Definizione ― Cardinalità di una Funzione"
    La Cardinalità dell'insieme delle Funzioni da $A \rightarrow B$ è uguale a $|B|^{|A|}$.

??? note "Note aggiuntive"
    - L'equipotenza è una Relazione di Equivalenza (*Riflessiva, Simmetrica e Transitiva*).
    - La Cardinalità di $\mathop{N}$ è uguale a quella di $\mathop{N} \times \mathop{N} \times \dots \times \mathop{N}$.



## Teorema di Cantor
!!! abstract "Definizione ― Teorema di Cantor"
    Se esistono $A \rightarrow B$ e $B \rightarrow A$ iniettive, allora esiste $A \rightarrow B$ biiettiva.

??? example "Esempio"
    <figure markdown="1">
    ![image](/uniroma1/assets/metodi/mod8_cantor_01.png)
    </figure>

    Nell'esempio 1, c'è una funzione iniettiva $A \rightarrow B$, ma non c'è una l'iniettività $B \rightarrow A$, quindi la cardinalità di $A$ è minore di quella di $B$:

    $$
    \begin{array}{c}
    |A| < |B|
    \end{array}
	$$

	<figure markdown="1">
    ![image](/uniroma1/assets/metodi/mod8_cantor_02.png)
    </figure>

    Nell'esempio 2, c'è una funziona iniettiva $A \rightarrow B$ ed una funzione iniettiva $B \rightarrow A$, quindi secondo il Teorema di Cantor, esiste una funzione biiettiva $A \rightarrow B$:

    $$
    \begin{array}{c}
    |\mathbb{N}| = |\mathbb{N}+1|
    \end{array}
	$$

## Polvere di Cantor

Proviamo a mettere in corrispondenza l'insieme di tutti i numeri naturali $\mathbb{N}$ compresi fra $0$ ed $1$ con un insieme numerico $C$ che definiamo nel seguente modo:

- Immaginiamo una retta di tutti i numeri reali compresi tra $0$ ed $1$, e la dividiamo in esattamente tre parti uguali:

<figure markdown="1">
![image](/uniroma1/assets/metodi/mod8_polvere_01.png)
</figure>

- Andiamo a togliere la parte centrale e prendiamo solo la parte evidenziata in blu ($0 < x < \frac{1}{3}$ e $\frac{2}{3} < x < 1$) per andare a costruire altre piccole rette:

<figure markdown="1">
![image](/uniroma1/assets/metodi/mod8_polvere_02.png)
</figure>

- Applichiamo la stessa strategia in cui andiamo a dividere in esattamente tre parti uguali ed andiamo a prendere la parte centrale, continuando all'infinito:

<figure markdown="1">
![image](/uniroma1/assets/metodi/mod8_polvere_03.png)
</figure>

- L'insieme $C$ sarà quindi l'intersezione tra tutti gli insiemi che abbiamo estratto:

	$$
    \begin{array}{c}
    C = C_1 \cap C_2 \cap C_3 \cap \dots
    \end{array}
	$$

- Quali sono quindi gli elementi di $C$? Sicuramente possiamo dire che tutti gli estremi ne fanno parte: $0, \frac{1}{3}, \frac{2}{3}, 1, \frac{1}{9}, \frac{2}{9}, \frac{7}{9}, \frac{8}{9}, \dots$ 

## Alberghi Transfiniti
Il matematico Hilbert ha immaginato un albergo con infinite stanze per mostrare alcune caratteristiche dell'infinito stesso.

Caso semplice: arriva un singolo nuovo ospite.

- Tutti i clienti già presenti si sposteranno nella camera successiva.
- In questo modo, nonostante l'albergo fosse pieno, è possibile far accomodare il nuovo ospite.

Possiamo quindi dedurre che l'albergo può accomodare infiniti clienti più uno:

$$
    \begin{array}{c}
    |\mathbb{N}| = |\mathbb{N}+1|
    \end{array}
$$

Nel caso più complesso: arrivano infiniti nuovi ospiti.

- Tutti i clienti si spostano nella stanza $2^n$ (quindi l'ospite 2 si sposta nella camera 4 e così via).
- Tutti i nuovi ospiti potranno quindi posizionarsi nelle camere di numero dispari.

$$
    \begin{array}{c}
    |\mathbb{N}| = |\mathbb{N}+\mathbb{N}|
    \end{array}
$$

Nel caso ancora più complesso: ci sono infiniti alberghi con infinite stanze tutte al completo. Tutti gli alberghi chiudono, tranne uno. Tutti gli ospiti vogliono alloggiare nell'unico albergo rimasto aperto.

- Ad ogni cliente, viene assegnata una coppia ordinata di numeri $(n,m)$ in cui $n$ rappresenta l'abergo di provenienza e $m$ la relativa stanza.
- Successivamente, ad ogni coppia viene assegnata la nuova stanza: $(1,1) \rightarrow 1; (2,1) \rightarrow 2; (1,2) \rightarrow 3; (3,1) \rightarrow 4; \dots$

Possiamo quindi dedurre che ogni insieme infinito avrà sempre la stessa cardinalità?

Supponiamo che:

$$
    \begin{array}{c}
    |\mathbb{N}| = |2^\mathbb{N}|
    \end{array}
$$

Quindi cerchiamo di creare una relazione biiettiva tra l'insieme dei numeri naturali e l'insieme di tutte le sue possibili combinazioni (*insieme potenza*) e dimostriamo che sono equipotenti.

Mettiamo in forma tabellare la relazione:

| -       | **0** | **1** | **2** | **3** | **4** | ... |
|---------|-------|-------|-------|-------|-------|-----|
| **0**   |   1   |   0   |   1   |   0   |   1   | ... |
| **1**   |   1   |   0   |   1   |   1   |   0   | ... |
| **2**   |   0   |   1   |   1   |   0   |   0   | ... |
| **3**   |   1   |   1   |   1   |   1   |   1   | ... |
| **...** | ...   | ...   | ...   | ...   | ...   | ... |

Le righe rappresentano l'insieme dei numeri naturali $\mathbb{N}$ mentre le colonne l'insieme di tutti i sottoinsiemi di $\mathbb{N}$.

Ad esempio:

- Associamo allo $0$ dell'insieme $\mathbb{N}$ il sottoinsieme di tutti i numeri pari.
- Associamo all'$1$ il sottoinsieme $\{0,2,3\}$
- Associamo al $2$ il sottoinsieme $\{1,1\}$
- Associamo al $3$ l'insieme $\mathbb{N}$ stesso
- continuiamo all'infinito $\dots$

Se prendessimo la diagonale dei numeri (*nell'esempio raffigurato sono i numeri in grassetto e corsivo*):

| -       | **0**   | **1**   | **2**   | **3**   | **4** | ... |
|---------|---------|---------|---------|---------|-------|-----|
| **0**   | **_1_** |    0    |    1    |    0    |   1   | ... |
| **1**   |    1    | **_0_** |    1    |    1    |   0   | ... |
| **2**   |    0    |    1    | **_1_** |    0    |   0   | ... |
| **3**   |    1    |    1    |    1    | **_1_** |   1   | ... |
| **...** | ...     | ...     | ...     | ...     | ...   | ... |

.. si formerà sicuramente un sottoinsieme presente in $2^\mathbb{N}$, che quindi sarà associato ad un numero naturale dell'insieme $\mathbb{N}$.

Dovremmo quindi trovare su una delle righe una combinazione che corrisponderà all'esatto opposto della diagonale.

Ciò non è possibile perchè nel punto in cui la diagonale ed il complemento si incontreranno, è impossibile che si trovi sia il numero della diagonale che il numero del complemento.

Si è dimostrato quindi che non esiste una funzione suriettiva $\mathbb{N} \rightarrow 2^\mathbb{N}$, e che quindi:
$$
    \begin{array}{c}
    |\mathbb{N}| < |2^\mathbb{N}|
    \end{array}
$$

## Polvere di Cantor new

!!! abstract "Definizione ― Equipotenza"
    La polvere di Cantor è un insieme costruito partendo dall'intervallo $[0,1]$ (in una dimensione) e applicando un procedimento iterativo di "rimozione". Alla fine di questo processo, otteniamo un insieme che ha proprietà molto particolari, come essere infinito ma non numerabile e avere misura nulla.

??? example "Dimostrazione della Polvere di Cantor"
    1. Partiamo dall'intervallo $[0,1]$ sulla retta reale. Questo è l'intervallo di partenza.
        * Dividiamo $[0,1]$ in tre parti uguali: $[0,\frac{1}{3}],(\frac{1}{3},\frac{2}{3}),[\frac{2}{3},1]$.
        * Rimuoviamo la parte centrale aperta: il segmento $(\frac{1}{3},\frac{2}{3})$.
        * Dopo questo primo passo, rimangono due intervalli chiusi: $[0,\frac{1}{3}]$ e $[\frac{2}{3},1]$.
    2. Adesso applichiamo lo stesso procedimento ai due intervalli rimanenti $[0,\frac{1}{3}]$ e $[\frac{2}{3},1]$:
        * Dividiamo ciascun intervallo in tre parti uguali:
        $$
            \begin{array}{c}
            [0,\frac{1}{9}],(\frac{1}{9},\frac{2}{9}),[\frac{2}{9},\frac{1}{3}] \\
            [\frac{2}{3},\frac{7}{9}],(\frac{7}{9},\frac{8}{9}),[\frac{8}{9},1]
            \end{array}
        $$
    3. Rimuoviamo i segmenti centrali aperti di ciascun intervallo:
        * Dal primo intervallo $[0,\frac{1}{3}]$, rimuoviamo $(\frac{1}{9},\frac{2}{9})$.
        * Dal secondo intervallo $[\frac{2}{3},1]$, rimuoviamo $(\frac{7}{9},\frac{8}{9})$.
    4. Dopo quest'ultimo passo, rimangono 4 intervalli chiusi:
    $$
        \begin{array}{c}
            [0,\frac{1}{9}],[\frac{2}{9},\frac{1}{3}],[\frac{2}{3},\frac{7}{9}],[\frac{8}{9},1]
        \end{array}
    $$
    5. A questo punto, ripetiamo lo stesso procedimento in modo infinito per tutti gli intervalli rimanenti:
        * Ad ogni passo, dividiamo ogni intervallo rimanente in tre parti uguali.
        * Rimuoviamo sempre il segmento centrale aperto di ciascun intervallo.
    6. Ad esempio, dopo il quarto passo, rimangono 8 intervalli chiusi (uno per ogni estremità dei quattro intervalli del passo precedente). Dopo il quarto passo, ci saranno 16 intervalli, e così via.
    7. Ad ogni iterazione, il numero di intervalli rimanenti raddoppia, ma la loro lunghezza totale diminuisce progressivamente.
    8. Dopo infinite iterazioni, la lunghezza totale rimanente tende a $0$ (poiché $(\frac{2}{3})^n \rightarrow 0$ quando $n \rightarrow \infty$). Quindi, la polvere di Cantor ha misura nulla. Anche se rimangono infiniti punti, la somma della loro lunghezza è $0$.
        