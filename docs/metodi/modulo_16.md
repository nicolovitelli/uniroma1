---
title: Modulo 16
---

## Modus Ponens
!!! abstract "Definizione ― Modus Ponens"
    Il Modus Ponens è una regola di inferenza che stabilisce quanto segue:

    - Data un'implicazione $P \rightarrow Q$ e la verità di $P$, possiamo concludere $Q$.

    $$
    \begin{array}{c}
        \frac{P \quad P \rightarrow Q}{Q}
    \end{array}
    $$

??? example "Esempio"

    - Usiamo le seguenti tre implicazioni come base di partenza:
    
    $$
        \begin{array}{c}
            P = \text{ tutti gli uomini sono mortali} \\
            Q = \text{ Socrate è un uomo} \\
            R = \text{ dunque, Socrate è mortale} 
        \end{array}
    $$
    
    - Dobbiamo dimostrare perchè $P \mathop{\wedge} Q \rightarrow R$ è vera.
    - Possiamo riscrivere le proposizioni come:
    
    $$
        \begin{array}{c}
            U(x) = x \text{ è un uomo} \\
            M(x) = x \text{ è mortale} \\
            S = \text{ Socrate} \\
            \\
            P = \forall x. U(x) \rightarrow M(x) \\
            Q = U(S) \\
            R = M(S)
        \end{array}
    $$
    
    - $P$ si legge come "per ogni $x$, se $x$ è un uomo ($U(x)$) allora è mortale (cioè vale $M(x)$)".
    - Nel mondo della Logica possiamo continuare la dimostrazione con il Modus Ponens:
    
    $$
        \begin{array}{c}
            \text{Formula Iniziale: } \\
            \forall x. U(x) \rightarrow M(x) \\
            \\
            \text{visto che la premessa vale per ogni } x \text{, allora varrà anche per } S: \\
            \frac{U(S) \quad U(S) \rightarrow M(S)}{M(S)} 
        \end{array}
    $$

## Quantificatori

!!! abstract "Definizione ― Quantificatore Universale"
    Il quantificatore universale $\forall$ (*si legge "per ogni"*) esprime che una formula è vera per tutti gli elementi del dominio.

!!! abstract "Definizione ― Quantificatore Esistenziale"
    Il quantificatore esistenziale $\exists$ (*si legge "esiste almeno uno" o "esiste un"*) esprime che esiste almeno un elemento del dominio per cui una formula è vera.

??? example "Esempio"

    - Nella Logica Predicativa, è presente, come nella Logica Proposizionale l'insieme dei modelli, ma quest'ultimi vengono rappresentati in maniera differente:
        - $U$ rappresenta l'universo degli oggetti.
        - $P,Q,R$ rappresentano dei sottoinsiemi che applicano un predicato.
    - Esempio:
        - $U =$ Universo degli Animali
        - $Q_m(x) = x$ è un quadrupede
        - $R_m(x) = x$ è un rettile
    - Prendendo in analisi la frase:
    
    $$
        \begin{array}{c}
            \forall x. Q(x) \rightarrow R(x)
        \end{array}
    $$
    
    - Nel nostro esempio la possiamo leggere come:
    
    $$
        \begin{array}{c}
            \text{tutti i quadrupedi sono rettili}
        \end{array}
    $$
    
    - Ovviamente quest'affermazione è falsa, perciò:
    
    $$
        \begin{array}{c}
            \not\models_m \forall x. Q(x) \rightarrow R(x) \\
            \text{il modello } m \text{ non soddisfa questa formula}
        \end{array}
    $$
    
    ---
    
    - Cambiamo Universo e Modello:
        - $V =$ essere animati
        - $Q_n(x) = x$ è un uomo
        - $R_n(x) = x$ è mortale
    - Prendendo in analisi la frase:
    
    $$
        \begin{array}{c}
            \forall x. Q(x) \rightarrow R(x)
        \end{array}
    $$
    
    - Nel nostro esempio si legge:
    
    $$
        \begin{array}{c}
            \text{tutti gli uomini sono mortali}
        \end{array}
    $$
    
    - L'affermazione è vera, perciò:
    
    $$
        \begin{array}{c}
            \models_n \forall x. Q(x) \rightarrow R(x) \\
            \text{il modello } n \text{ soddisfa questa formula}
        \end{array}
    $$

    ---

    - Tornando all'esempio del modello $m$ con Universo $U$, aggiungiamo una proposizione:
        - $P_m(x) = x$ è squamato
    - Prendendo in analisi la frase:
    
    $$
        \begin{array}{c}
            \exists x. P(x) \mathop{\wedge} Q(x) \\
            \text{"esiste un quadrupede squamato"}
        \end{array}
    $$
    
    - Sicuramente esiste un elemento che è sia un quadrupede che squamato (*il Varano*) quindi possiamo concludere che:
    
    $$
        \begin{array}{c}
            \models_m \exists x. P(x) \mathop{\wedge} Q(x) \\
            \text{il modello } m \text{ soddisfa questa formula}
        \end{array}
    $$
    
    ---
    
    - Torniamo all'esempio con il modello $n$ nell'universo $V$.
    - Aggiungiamo una proposizione:
        - $P_n(x) = x$ ha almeno 100 arti
    - Prendendo in analisi la frase:
    
    $$
        \begin{array}{c}
            \exists x. P(x) \mathop{\wedge} Q(x) \\
            \text{"esiste almeno un uomo con 100 arti"}
        \end{array}
    $$
    
    - L'affermazione è falsa, quindi questra frase non è soddisfatta dal modello $n$:
    
    $$
        \begin{array}{c}
            \not\models_n \exists x. P(x) \mathop{\wedge} Q(x) \\
            \text{il modello } n \text{ non soddisfa questa formula}
        \end{array}
    $$

## Logica Predicativa - Termini

!!! abstract "Definizione ― Termini"
    - Un Termine è un elemento dell'insieme delle Variabili oppure un elemento dell'insieme delle Costanti.
    - Avendo a disposizione $n$ termini ($t_1,t_2,\dots,t_n$) ed $f$ è una funzione di arietà $n$ (quindi può prendere $n$ argomenti), allora $f(t_1,t_2,\dots,t_n$) è anch'esso un termine.

    $$
        \begin{array}{c}
            \text{termini } t_1, t_2, \dots ::= x | y | z | \dots | a | b | c | \dots | f(t_1,t_2,\dots,t_n)
        \end{array}
    $$

    - Dove:
        - $x | y | z | \dots$ fanno parte dell'insieme dei simboli di Variabile.
        - $a | b | c | \dots$ fanno parte dell'insieme dei simboli di Costante (*es. $S =$ Socrate*).
        - $f | g | h | \dots$ fanno parte dell'insieme dei simboli di Funzione.

!!! abstract "Definizione ― Arietà"
    - A ciascun simbolo $f$ nella Logica Predicativa, si suppone che venga accompagnato da un'informazione (*un intero positivo* $n$) che chiamiamo **arietà** di $f$, che rappresenta il numero di argomento della funzione $f$.

??? example "Esempio"
	- La somma $+$ è una funzione che ha bisogno di due argomento, quindi la sua arietà è $2$ (*funzione binaria*).
	- Il fattoriale è una funzione che ha bisogno di un solo argomento, quindi la sua arietà è $1$ (*funzione unaria*).
	- *If-Then-Else* è una funzione ternaria perchè ha bisogno di tre argomenti, perciò la sua arietà è $3$.

## Logica Predicativa - Formule

!!! abstract "Definizione ― Termini"

    - A ciascun simbolo predicativo $P$ è associato un intero positivo $n$, chiamato arietà di $p$, che ne rappresenta il numero di argomenti.
        - $P$ è un elemento che fa parte dell'insieme dei simboli predicativi (oltre a $Q,R,\dots$). 

    $$
        \begin{array}{c}
            \text{formule } A, B \dots ::= P(t_1,t_2,\dots,t_n)
        \end{array}
    $$

    - Altre Formule:
        - *falso*
    	- $A \mathop{\wedge} B$
    	- $A \mathop{\vee} B$
    	- $A \rightarrow B$
    	- $\neg A$
    	- $\forall x. A$
    	- $\exists x. A$

??? note "Note aggiuntive"
    - Altre definizioni formali sulle Formule:
        - se $t_1,t_2,\dots,t_n$ sono termini e $P$ è un simbolo predicativo di arietà $n$, allora $P(t_1,t_2,\dots,t_n)$ è una formula.
        - se $A$ è una formula, allora $\forall x. A$ è una formula.
        - se $A$ è una formula, allora $\exists x. A$ è una formula.
        - nient'altro è una formula!

??? example "Esempio"

    $$
        \begin{array}{c}
            \neg \exists x. x = succ(0)
        \end{array}
    $$

    - Si legge come: "non esiste un $x$ tale che $x$ è uguale al successore di $0$" (*terzo assioma di Peano*).
    - Modo alternativo per scrivere questa formula:

    $$
        \begin{array}{c}
            =(x, succ(0))
        \end{array}
    $$

    - Verifichiamo che la formula sia sintatticamente corretta:
        - $x$ è un termine
        - $0$ è una costante
        - $succ(x)$ è una funzione unaria, che dato un numero ne restituisce il successore.
    - Terminata l'analisi, possiamo concludere che è una formula corretta.

## Variabili Legate e Libere
!!! abstract "Definizione ― Variabili Legate"
    - Una Variabile $x$ la chiameremo Legata perchè è agganciata ad un quantificatore ed è indipendente per verificare la veridicità della formula.

!!! abstract "Definizione ― Variabili Libera"
    - Una Variabile $y$ la chiameremo Libera perchè non è agganciata ad un quantificatore ed il valore di verità di una formula dipende da esse.

??? example "Esempio"
    - Usiamo l'esempio dell'universo $V$ con modello $m$ ed aggiungiamo delle costanti:
        - $S =$ Socrate
        - $B =$ Briareo (*dio con 100 braccia*)
    - Verifichiamo alcune proposizioni:
    
    $$
        \begin{array}{c}
            P(S) = F \\
            P(B) = T \\
            P(B) \mathop{\wedge} R(S) = T \\
            P(B) \mathop{\wedge} \forall x. Q(x) \rightarrow R(x) = ?
        \end{array}
    $$

    - L'ultima proposizione si legge: "Briareo ha 100 braccia ed ogni uomo è mortale."
    - In questo caso la variabile $x$ sarà la variabile Legata, perchè agganciata ad un quantificatore ($\forall x$), mentre $y$ è una variabile Libera perchè non è agganciata a nessun quantificatore ($P(y)$).

    ---

    - Altri esempi:

    $$
        \begin{array}{c}
            P(y) \mathop{\wedge} \forall z. Q(z) \rightarrow R(z) \\
            y = \text{ libera}, z = \text{ legata} \\
            \\
            P(y) \mathop{\wedge} \forall z. Q(x) \rightarrow R(z) \\
            x,y = \text{ libera}, z = \text{ legata} \\
            \\
            P(z) \mathop{\wedge} \forall z. Q(x) \rightarrow R(z) \\
            \\
            z,x = \text{ libere}, z = \text{ legata} \\
        \end{array}
    $$

    - Nell'ultimo esempio, $z$ è sia legata che libera perchè la prima occorrenza ($P(z)$) non è agganciata a nessun agganciatore, mentre la seconda occorrenza ($R(z)$) è agganciata a $\forall z$.

    $$
        \begin{array}{c}
            (\forall x. (P(z) \mathop{\wedge} \exists y. P(y) \mathop{\wedge} Q(x))) \rightarrow
            (\forall z. \exists w. R(x) \mathop{\vee} Q(y)) \\
            x,y,z = \text{ libere}, x,y = \text{ legate}
        \end{array}
    $$


## Modelli nella Logica Predicativa
!!! abstract "Definizione ― Modelli"
    Un Modello della Logica Predicativa (chiamato anche *Struttura*) è costituito da:

    - un insieme $U$ (universo)
    - $\forall a \dots \in$ simboli di costante
        - notazione: $[[a]] \in A$
    - $\forall f \dots \in$ simboli di funzione
        - notazione: $[[f]] : U \times U \times \dots \times U \rightarrow U$
    - $\forall P \dots \in$ simboli predicativi
        - notazione: $[[P]] \subseteq U \times U \times \dots \times U$

??? example "Esempio"
    - Consideriamo:
    
    $$
        \begin{array}{c}
            U = \text{ numeri naturali} \\
            [[a]] = 0, [[b]] = 1, \dots, [[m]] = 9 \\
            [[f]] (x,y) = x + y \text{ (funzione binaria che rappresenta la somma) } \\
            [[P]] = \text{ essere un numero primo - predicato unario} \\
            [[Q]] = \text{ essere maggiore di - predicato binario}
        \end{array}
    $$

    - Prendiamo ora in considerazione la formula:

    $$
        \begin{array}{c}
            \exists y. Q(y,x) \mathop{\wedge} P(y) \mathop{\wedge} P(y+c)
        \end{array}
    $$

    - La quale si legge: "esiste un numero primo $y$ maggiore di $x$ tale che $y+2$ è primo".
    - L'unica variabile libera è $x$, quindi la verità o falsità di questa formula dipende dal valore che vogliamo associare ad $x$.
    - Esempio:

    $$
        \begin{array}{c}
            x = 4 = T \\
            x = 820 = T
        \end{array}
    $$

    - In realtà questa formula è vera per qualsiasi $x$, quindi possiamo scrivere:

    $$
        \begin{array}{c}
            \forall x. \exists y. Q(y,x) \mathop{\wedge} P(y) \mathop{\wedge} P(y+c)
        \end{array}
    $$

    - Questa formula si chiama congettura dei numeri primi gemelli.

## Ambiente
!!! abstract "Definizione ― Ambiente"
    - Un Ambiente (in $U$) è una funzione $\rho :$ variabili $\rightarrow U$.

??? note "Note aggiuntive"
    - Sia i termini che le formule possono essere interpretate fornendo un ambiente:
    
    $$
        \begin{array}{c}
            [[-]] : \text{ termini, ambienti } \rightarrow U \\
            \text{dato un termine e dato un ambiente, restituisce un elemento dell'universo.} \\
            \\
            [[-]] : \text{ formule, ambienti } \rightarrow \{T,F\} \\
            \text{data una formula e dato un ambiente per interpretare le variabili, \\
                restituisce un valore True/False.}
        \end{array}
    $$

!!! abstract "Definizione ― Rho Primo"
    - Dati un ambiente $\rho$, una variabile $x$ ed un elemento $v \in U$, denotiamo con $\rho [x \rightarrow v]$ l'ambiente $\rho^\prime$ definito come segue:
    
    $$
        \begin{array}{c}
            \rho^\prime(x) = v \\
            \rho(y) = \rho(y), \text{ per } y \neq x
        \end{array}
    $$

??? example "Esempio ― Applicazione degli Ambienti sulla Sintassi della LP"
    - Applicando quindi gli ambienti sui termini della Logica Predicativa:
    
    $$
        \begin{array}{c}
            [[x]]_\rho = \rho(x)
        \end{array}
    $$

    - Si legge: "qual è il significato di $x$ nell'ambiente $\rho$? quell'elemento di $u$ che $\rho$ assegna ad $x$."

    ---

    - Per quanto riguarda le Costanti, l'ambiente $\rho$ non è rilevante:

    $$
        \begin{array}{c}
            [[a]]_\rho = [[a]]
        \end{array}
    $$

    ---

    - Per le funzioni invece è necessario interpretare ogni termine:

    $$
        \begin{array}{c}
            [[f(t_1,t_2,\dots,t_n)]] = [[f]]([[t_1]]_\rho,[[t_2]]_\rho,\dots,[[t_n]]_\rho)
        \end{array}
    $$

    - Quindi, ogni interpretazione $[[t_1]]_\rho$ restituisce un elemento dell'universo $U$.

    ---

    - Applichiamo gli Ambienti sulle Formule della Logica Predicativa:

    $$
        \begin{array}{c}
            1) [[\text{falso}]] = F \\
            2) [[A \mathop{\vee} B]]_\rho = [[A]]_\rho \mathop{\vee} [[B]]_\rho \\
        \end{array}
    $$
    
    - Nella Seconda Interpretazione Semantica, il risultato delle due interpretazioni ($[[A]]_\rho, [[B]]_\rho$) sarà $T$ o $F$, ed infine si otterrà il risultato finale attraverso le Tavole della Verità.
    - Inoltre, sempre nella Seconda Interpretazione Semantica, il primo simbolo $\mathop{\vee}$ rappresenta un oggetto sintattico, mentre il secondo $\mathop{\vee}$ rappresenta un oggetto semantico, ovvero un operatore che lavora similmente ad altri operatori ($+,-$).

??? example "Esempio ― tilizzo del NOT nella Logica Predicativa"
    - Prendiamo come esempio queste proposizioni e la relativa Formula:
    
    $$
        \begin{array}{c}
            L(x) = \text{ x è un leone} \\
            C(x) = \text{ x beve il caffè} \\
            F(x) = \text{ x è feroce} \\
            \\
            \exists x. L(X) \mathop{\wedge} \neg C(X) \\
            \text{esiste un leone che non beve il caffè}
        \end{array}
    $$
    
    - Sostituiamo $x$ con $a$, deducendo quindi che $a$ è un particolare leone:
    
    $$
        \begin{array}{c}
            L(a) \mathop{\wedge} \neg C(a)
        \end{array}
    $$
    
    - La seconda ipotesi che abbiamo a disposizione è:
    
    $$
        \begin{array}{c}
            \forall x. L(x) \rightarrow F(x) \\
            \text{se } x \text{ è un leone, allora è feroce}
        \end{array}
    $$
    
    - Sicuramente varrà anche per quel particolare leone $a$:
    
    $$
        \begin{array}{c}
            L(a) \rightarrow F(a)
        \end{array}
    $$
    
    - A questo punto, usiamo il Modus Ponens per derivare che $a$ è feroce:
    
    $$
        \begin{array}{c}
            \frac{L(a) \quad L(a) \rightarrow F(a)}{F(a)}
        \end{array}
    $$

## Istanza di una Variabile
!!! abstract "Definizione ― Istanza di una Variabile"
    - Data una qualunque formula $A$, denotiamo con $[b/x]A$ la formula ottenuta sostituendo $b$ ad ogni occorrenza libera di $x$ in $A$.

    $$
        \begin{array}{c}
            \frac{\forall x. A}{[a/x]A} \\
            \frac{\exists x. A}{[b/x]A}
        \end{array}
    $$

??? example "Esempio ― Perchè è necessaria questa notazione"
    
    - Usiamo l'esempio del modello $n$ con le seguenti proposizioni:
        - $Q_n(x) = x$ è un uomo
        - $R_n(x) = x$ è mortale
        - $P_n(x) = x$ ha 100 arti

        \begin{array}{c}
            \frac{\exists x. P(x)}{P(a)} \\
            \frac{\exists x. Q(x)}{Q(a)} \\
            \\
            P(a) \mathop{\wedge} Q(a)
        \end{array}
    $$

    - Ovviamente $P(a) \mathop{\wedge} Q(a)$ è falso, perchè sappiamo che non esiste un uomo con 100 arti.
    - Dobbiamo quindi differenziare le due istanze in quanto non potranno avere entrambe $a$.

??? example "Esempio"

    $$
        \begin{array}{c}
            [b\x](P(x) \mathop{\wedge} R(x,y)) = P(b) \mathop{\wedge} R(b,y) \\
            [b\x](P(z) \mathop{\wedge} R(z,y)) = P(z) \mathop{\wedge} R(z,y) \\
            [b\x](P(x) \mathop{\wedge} \forall y. R(x,y)) = P(b) \mathop{\wedge} \forall y. R(b,y) \\
            [b\x](P(x) \mathop{\wedge} \forall x. R(x,y)) = P(b) \mathop{\wedge} \forall x. R(x,y)
        \end{array}
    $$

    - Nell'ultimo esempio, $x$ rimane inalterato nella seconda parte perhè è legato ad un quantificatore.

## Tableu Predicativi

!!! abstract "Definizione ― Istanza di una Variabile"
    Un Tableau Predicativo è una tecnica utilizzata in logica predicativa per verificare la soddisfacibilità di una formula o per dimostrare la validità di un argomento logico. Si basa sull'espansione sistematica della formula mediante regole logiche, introducendo variabili, termini e quantificatori fino a raggiungere una contraddizione (nel caso di formule insoddisfacibili) o una struttura completa.

??? math-adm "Formule per i Tableu Predicativi"

    $$
    \begin{array}{c}
        \frac{\forall x. A}{[a/x] A} \\
        \frac{\neg \exists x. A}{[a/x] \neg A} \\
        \\
        \frac{\exists x. A}{[b/x] A} \\
        \frac{\neg \forall x. A}{[b/x] \neg A}
    \end{array}
    $$

??? example "Esempio"

    $$
    \begin{array}{c}
        (\forall x. P(x)) \rightarrow (\exists x. P(x))
    \end{array}
    $$

    - Sappiamo che questa è una formula valida: proviamo a derivarlo con i Tableu Predicativi:

    $$
    \begin{array}{c}
        \neg((\forall x. P(x)) \rightarrow (\exists x. P(x))) \\
                                | \\
        \forall x. P(x), \neg \exists x. P(x) \\
                                | \\
        P(a), \neg \exists x. P(x) \\
                                | \\
        P(a), \neg P(a) \\
        \text{Tableu chiuso}
    \end{array}
    $$

    - Tra il secondo e terzo passaggio, abbiamo applicato la regola del $\forall$ ed istanziamo un $x$ per ottenere $P(a)$.
    - Tra il terzo e quarto passaggio, applichiamo la regola del $\neg \exists x. A$ ed istanziamo $x$.

    ---

    $$
    \begin{array}{c}
        (\exists x. \neg P(x)) \mathop{\vee} (\forall x. P(x)) \\
        \text{o esiste un } x \text{ per la quale non vale } P(x) \text{, oppure esiste un } x \text{ per cui vale.} \\
                                | \\
        \neg ((\exists x. \neg P(x)) \mathop{\vee} (\forall x. P(x))) \\
                                | \\
        \neg \neg P(a), \neg \forall x. P(x) \\
                                | \\
        \neg \neg P(a), \neg P(b)
    \end{array}
    $$

    - Il Tableu non viene chiuso perchè abbiamo istanziato la prima parte della formula piuttosto che la seconda.
    - Modificando il procedimento:

    $$
    \begin{array}{c}
        (\exists x. \neg P(x)) \mathop{\vee} (\forall x. P(x)) \\
                                | \\
        \neg ((\exists x. \neg P(x)) \mathop{\vee} (\forall x. P(x))) \\
                                | \\
        \neg \exists x. \neg P(x), \neg P(a) \\
                                | \\
        \neg \neg P(a), \neg P(a) \\
        \text{Tableu chiuso}
    \end{array}
    $$