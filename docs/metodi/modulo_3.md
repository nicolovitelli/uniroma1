---
title: Modulo 3
---

## Relazione
!!! abstract "Definizione ― Relazione"
    Una Relazione fra due insiemi $A$ e $B$ è un qualunque sottoinsieme di $A \times B$.
    $$
    \begin{array}{c}
        \mathcal{R} \subseteq A \times B
    \end{array}
	$$

## Composizione di due Relazioni

!!! abstract "Definizione ― Composizione di due Relazioni"
    La Composizione di due Relazioni $\mathcal{R}$ ed $\mathcal{S}$ tra gli insiemi $A,B$ e $C$ è definita come una Relazione $\mathcal{R} \circ \mathcal{S} \subseteq A \times C$, tale che per ogni coppia $(a,c) \in \mathcal{R} \circ \mathcal{S}$, esiste un elemento $b \in B$ tale che $a \mathcal{R} b, b \mathcal{S} c$.

??? example "Esempio"
    <figure markdown="1">
    ![composizione](/uniroma1/assets/metodi/mod3_composizione.png)
    </figure>

## Complemento di una Relazione
!!! abstract "Definizione ― Complemento di una Relazione"
    Sia $\mathcal{R}$ una Relazione definita su un insieme $A$. Il complemento di $\mathcal{R}$, denotato $\mathcal{R}^C$, è definito come l'insieme delle coppie ordinate $(a,b)$ in $A \times A$ tali che $(a,b) \not\in \mathcal{R}$.

    $$
    \begin{array}{c}
        \mathcal{R}^C = \{(a,b) \in A \times A \, | \, (a,b) \not\in \mathcal{R}\}
    \end{array}
    $$

## Relazioni Riflessive e Antiriflessive
!!! abstract "Definizione ― Relazione Riflessiva"
    $$
    \begin{array}{c}
        \forall a \in A \\
        (a,a) \in \mathcal{R}
    \end{array}
	$$

!!! abstract "Definizione ― Relazione Antiriflessiva"
	$$
    \begin{array}{c}
        \forall a \in A \\
        (a,a) \not\in \mathcal{R}
    \end{array}
	$$

??? example "Esempio"
    $$
    \begin{array}{c}
    	\mathcal{R}_1 = \{(x,y) \in \mathbb{R} \times \mathbb{R} : x < y\}
    \end{array}
    $$

    - **Antiriflessiva:** nessun numero reale è minore di se stesso.

    $$
    \begin{array}{c}
    	\mathcal{R}_2 = \{(x,x) \in \mathbb{R} \times \mathbb{R} : x - x \text{ è pari}\}
    \end{array}
    $$

    - **Riflessiva:** qualsiasi numero reale sottratto a se stesso ha come risultato $0$, quindi un numero paro.
    
    $$
    \begin{array}{c}
    	\mathcal{R}_3 = \{(x,x) \in \mathbb{R} \times \mathbb{R} : x \neq x\}
    \end{array}
    $$

    - **Antiriflessiva:** nessun numero è diverso da se stesso.
    
    $$
    \begin{array}{c}
    	\mathcal{R}_4 = \{(x,x) \in \mathbb{N} \times \mathbb{N} : x + x = 6\}
    \end{array}
    $$

    - **né Riflessiva né Antiriflessiva:** $x + x = 6$ è vero solo quando $x$ e $x$ sono uguali a $3$, in tutti gli altri casi è falso.
    
    $$
    \begin{array}{c}
    	\mathcal{R}_5 = \{(x,x) \in \mathbb{R} \times \mathbb{R} : x \cdot x = 0\}
    \end{array}
    $$

    - **né Riflessiva né Antiriflessiva:** $x \cdot x = 0$ è vero solo quando  $(x,x) = 0$, in tutti gli altri casi è falso.
    
    $$
    \begin{array}{c}
    	\mathcal{R}_6 = \{\emptyset\}
    \end{array}
    $$
    
    - **sia Riflessiva che Antiriflessiva:** Riflessiva perchè non ci sono coppie che violano la Riflessività ($\forall (x,x) \in \mathbb{N} \times \mathbb{N}, x \mathcal{R} x$) e contemporaneamente non viola nemmeno l'Antiriflessività, perchè non ci sono coppie da confrontare.

    $$
    \begin{array}{c}
    	\mathcal{R}_7 = \{(x,x) \in \mathbb{R} \times \mathbb{R} : x - x \in \mathbb{Z}\}
    \end{array}
    $$

    - **Riflessiva:** qualsiasi numero reale sottratto a se stesso ha come risultato $0$, quindi appartiene all'insieme $\mathbb{Z}$.
    
    $$
    \begin{array}{c}
    	\mathcal{R}_8 = \{(x,x) \in \mathbb{R} \times \mathbb{R} : x^2 + x^2 = 0\}
	\end{array}
    $$

    - **né Riflessiva né Antiriflessiva:** \(x^2 + x^2 = 0\) è vero solo quando \((x,x) = 0\), in tutti gli altri casi è falso.
    
    $$
    \begin{array}{c}
    	\mathcal{R}_9 = \{(x,x) \in \mathbb{R} \times \mathbb{R} : x \ge x\}
    \end{array}
    $$

    - **Riflessiva:** qualsiasi numero reale è uguale a se stesso.
    
    $$
    \begin{array}{c}
    	\mathcal{R}_{10} = \{(x,x) \in \mathbb{R} \times \mathbb{R} : x \cdot x > 0\}
    \end{array}
    $$

    - **né Riflessiva né Antiriflessiva:** $x \cdot x > 0$ è falso solo quando $x$ e $x$ valgono $0$, in qualsiasi altro caso è vero.

## Relazioni Simmetriche e Antisimmetriche
!!! abstract "Definizione ― Relazione Simmetrica"
    $$
    \begin{array}{c}
        \forall \, (a,b) \in A \\
        a \mathcal{R} b \rightarrow b \mathcal{R} a
    \end{array}
    $$

!!! abstract "Definizione ― Relazione Antisimmetrica"
	$$
    \begin{array}{c}
        \forall \, (a,b) \in A \\
        a \mathcal{R} b, b \mathcal{R} a \rightarrow a = b
    \end{array}
    $$

??? example "Esempio"
    $$
    \begin{array}{c}
    	\mathcal{R}_1 = \{(1,1),(2,2)\}
    \end{array}
    $$

    - **sia Simmetrica che Antisimmetrica**.

	$$
    \begin{array}{c}
    	\mathcal{R}_2 = \{(a,b) \in \mathbb{N} \times \mathbb{N} : a \leq b\}
    \end{array}
    $$

    - **Antisimmetrica:** se $a \leq b$ e $b \leq a$, allora necessariamente $a = b$. Non può capitare che la condizione si verifichi e $a \neq b$ (quindi non può essere Simmetrica).

    $$
    \begin{array}{c}
    	\mathcal{R}_3 = \{(a,b) \in \mathbb{N} \times \mathbb{N} : a < b\}
    \end{array}
    $$

    - **Antisimmetrica:** perchè non troveremo mai coppie in cui $a < b$ e $b < a$, quindi la definizione di Antisimmetria viene rispettata.

    $$
    \begin{array}{c}
    	\mathcal{R}_4 = \{(a,b) \in \mathbb{N} \times \mathbb{N} : a + b = 10\}
    \end{array}
    $$

    - **Simmetrica:** se $a + b = 10$ allora è sicuramente vero che $b + a = 10$. Non è necessariamente vero che $a = b$ (Antisimmetria) perchè possono esserci coppie come $a=3, b=10$.

    $$
    \begin{array}{c}
    	\mathcal{R}_5 = \{(a,b) \in \mathbb{N} \times \mathbb{N} : a \text{ e } b \text{ hanno la stessa parità}\}
    \end{array}
    $$

    - **Simmetrica:** possono esserci coppie come $a=2,b=4$ che rispettano la proprietà di Simmetria ($2,4$ sono pari come $4,2$). Non può essere Antisimmetrica perchè non è detto che $a = b$.

    $$
    \begin{array}{c}
    	\mathcal{R}_6 = \{(a,b) \in \mathbb{N} \times \mathbb{N} : a \text{ è paro}, b \text{ è disparo}\}
    \end{array}
    $$

    - **né Simmetrica né Antisimmetrica:** $a \mathcal{R} b$ e $b \mathcal{R} a$ non potrà mai essere vero, per esempio la coppia $(2,5) \in \mathcal{R}$ ma $(5,2) \not\in \mathcal{R}$.

    $$
    \begin{array}{c}
    	\mathcal{R}_7 = \{(1,2),(2,1)\}
    \end{array}
    $$

    - **Simmetrica:** perchè $(a,b) \in \mathcal{R}$ e $(b,a) \in \mathcal{R}$.

    $$
    \begin{array}{c}
    	\mathcal{R}_8 = \{(3,4),(4,5)\}
    \end{array}
    $$

    - **né Simmetrica né Antisimmetrica:** $(a,b) \in \mathcal{R}$ ma $(b,a) \not\in \mathcal{R}$.

    $$
    \begin{array}{c}
    	\mathcal{R}_9 = \{(5,10),(10,5),(5,5)\}
    \end{array}
    $$

    - **Simmetrica:** $(a,b) \in \mathcal{R}$ e $(b,a) \in \mathcal{R}$.

    $$
    \begin{array}{c}
    	\mathcal{R}_{10} = \{(1,2),(2,3),(1,3)\}
    \end{array}
    $$

    - **Antisimmetrica:** non ci sono coppie $(a,b) \in \mathcal{R}$ e $(b,a) \in \mathcal{R}$.

## Relazioni Transitive & Antitransitive
!!! abstract "Definizione ― Relazione Transitiva"
    $$
    \begin{array}{c}
        \forall \, (a,b,c) \in A \\
        a \mathcal{R} b, b \mathcal{R} c \rightarrow a \mathcal{R} c
    \end{array}
    $$

!!! abstract "Definizione ― Relazione Transitiva"
    $$
    \begin{array}{c}
        \forall \, (a,b,c) \in A \\
        a \mathcal{R} b, b \mathcal{R} c \rightarrow a \cancel{\mathcal{R}} c
    \end{array}
    $$

??? example "Esempio"
    $$
    \begin{array}{c}
    	\textit{Esempi di Relazioni Transitive e Non Transitive}\\
	    A = \{1,2,3,4\} \\
	    \\
	    \mathcal{R}_1 = \{(2,1),(3,1),(3,2),(4,4)\} \\ \mathcal{R}_1 \text{ è Transitiva perchè } \{(3,2),(2,1),(3,1)\} \in \mathcal{R}_1 \\
	    \\
	    \mathcal{R}_2 = \{(2,1),(1,3)\} \\ \mathcal{R}_2 \text{ non è Transitiva perchè } \{(2,1),(1,3)\} \in \mathcal{R}_2,(2,3) \not\in \mathcal{R}_2
    \end{array}
    $$

## Chiusura
!!! abstract "Definizione ― Chiusura"
    Un insieme $B$ è detto chiusura di un insieme $A$ rispetto ad una proprietà $\mathcal{P}$ quando sono soddisfatte le seguenti condizioni:

    - $B$ gode della proprietà $\mathcal{P}$, quindi $\mathcal{P}(B)$
	- $A \subseteq B$
	- per ogni insieme $C$, se $\mathcal{P}(C)$ e $A \subseteq C$, allora $B \subseteq C$

<figure markdown="1">
![image](/uniroma1/assets/metodi/mod3_chiusura.png)
</figure>

??? note "Note aggiuntive"
    - La Chiusura di un insieme rispetto ad una proprietà, se esiste, è unica.

??? example "Esempio ― Dimostrazione dell'unicità della Chiusura"
    Supponiamo di avere $B$ e $B^\prime$ che sono entrambe chiusure di $A$ rispetto a $\mathcal{P}$.
    
    Per le tre proprietà della Chiusura, possiamo dire che:
    
    - esiste un insieme $\mathcal{P}(B^\prime)$
    - $A \subseteq B^\prime$
    - $B$ è un superinsieme di $B^\prime$, quindi $B^\prime \subseteq B$.
    
    Ora scambiando i due insiemi ($B$ e $B^\prime$) otteniamo quanto segue:
    
    - esiste un insieme $\mathcal{P}(B)$
    - $A \subseteq B$
    - $B^\prime$ è un superinsieme di $B$, quindi $B \subseteq B^\prime$.
    
    Si nota quindi che $B^\prime \subseteq B$ e $B \subseteq B^\prime$. Possiamo concludere che $B = B^\prime$.
    
??? example "Esempio ― Preservazione della Transitività"
    
    Nel paragrafo che segue si va a dimostrare che l'operatore insiemistico di Intersezione preserva la Transitività di due Relazioni.
    
    Supponiamo di avere due relazioni transitive, $\mathcal{R}$ e $\mathcal{S}$.
    
    - Se $(a,b),(b,c) \in \mathcal{R} \cap \mathcal{S}$, allora $(a,b),(b,c) \in \mathcal{R}$ e $(a,b),(b,c) \in \mathcal{S}$.
    
    - Visto che sono entrambe relazioni transitive:
        - $(a,c) \in \mathcal{R}$
        - $(a,c) \in \mathcal{S}$
    - Quindi per definizione di Intersezione, $(a,c) \in \mathcal{R} \cap \mathcal{S}$.
    
    Possiamo quindi confermare che l'Intersezione tra due relazioni transitive ne preserva la transitività.
    
    Verifichiamo ora che lo stesso accada con l'operatore di Unione.
    
    Supponiamo di avere due relazioni transitive: $\mathcal{R}$ = essere più basso di, $\mathcal{B}$ = essere antenato di.
    
    Quindi l'unione $\mathcal{R} \cup \mathcal{B}$ sarà formata dalle coppie in cui o $x$ è antenato di $y$ o $x$ è più basso di $y$.
    
    - Pietro è antenato di Valerio, quindi troviamo la coppia (Pietro, Valerio) nell'Unione tra le due Relazioni.
    - Valerio è più basso di Giuliana, quindi troviamo la coppia (Valerio, Giuliana) nell'Unione tra le due Relazioni.
    - Pietro non è però più basso di Giuliana ne Giuliana è suo antenato. Quindi sicuramente non troveremo la coppia (Pietro, Giuliana) nell'Unione tra le due Relazioni.
    - Secondo la Transitività però, se $x$ è più basso di $y$ (Giuliana è più basso di Pietro), allora $x$ è sicuramente più basso di $z$ (Giuliana è più bassa di Valerio).
    
    Possiamo concludere quindi che l'Unione non preserva la Transitività di una Relazione.

## Chiusura Transitiva
!!! abstract "Definizione ― Chiusura Transitiva"
    La Chiusura Transitiva di una Relazione $\mathcal{R}$ su un insieme $A$ è la relazione più piccola che contiene $\mathcal{R}$ e che è transitiva.

??? example "Esempio"
    $$
    \begin{array}{c}
        A = \{1,2,3\} \\
        \mathcal{R} = \{(1,2),(2,3)\} \\
        \mathcal{R}^{+} = \{(1,2),(2,3),(1,3)\}
    \end{array}
    $$

## P-Maggiorabile
!!! abstract "Definizione ― P-Maggiorabile"
    Quando esiste un insieme $B$ tale che $\mathcal{P}(B)$ e $A \subseteq B$, diciamo che $A$ è P-Maggiorabile.

    In altre parole, $A$ è P-Maggiorabile quando rispetta le prime due proprietà della Chiusura.

<figure markdown="1">
![image](/uniroma1/assets/metodi/mod3_pmaggiorabile.png)
</figure>