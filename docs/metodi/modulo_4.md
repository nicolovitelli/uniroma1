---
title: Modulo 4
---

## Ordinamento Parziale
!!! abstract "Definizione ― Ordinamento Parziale"
    Un Ordinamento Parziale si presenta quando una Relazione $\mathcal{R}$ è:

    - Riflessiva $(a \mathcal{R} b)$
    - Antisimmetrica $(a \mathcal{R} b, b \mathcal{R} a, a = b)$
    - Transitiva $(a \mathcal{R} b, b \mathcal{R} c, a \mathcal{R} c)$

??? example "Esempio"
    $$
    \begin{array}{c}
    	\{(a,b) \in \mathcal{P}(B) \times \mathcal{P}(B) : a \subseteq b\} \\
		\{(n,m) \in \mathbb{N} \times \mathbb{N} : n \leq m\} \\
	    A \cup B = B \text{ se e solo se } A \subseteq B \\
    \end{array}
    $$

## Ordine Stretto
!!! abstract "Definizione ― Ordine Stretto"
    Un Ordine Stretto si presenta quando una Relazione $\mathcal{R}$ è:

    - Transitiva $(a \mathcal{R} b, b \mathcal{R} c, a \mathcal{R} c)$
	- Antisimmetrica $(a \mathcal{R} b, b \mathcal{R} a, a = b)$
	- Non necessariamente Riflessiva $(a \mathcal{R} b)$

??? example "Esempio"
    $$
    \begin{array}{c}
    	\{(n,m) \in \mathbb{N} \times \mathbb{N} : n < m\}
    \end{array}
    $$

## Ordinamento Totale
!!! abstract "Definizione ― Ordinamento Totale"
    Per ogni $(a,b) \in A, a \mathcal{R} b$ oppure $b \mathcal{R} a$.

??? note "Note aggiuntive"
    - Ogni Ordinamento Totale è un caso particolare di Ordinamento Parziale.

??? example "Esempio"
    $$
    \begin{array}{c}
        \{(a,b) \in \mathbb{N} \times \mathbb{N} : a \text { e } b \text{ hanno la stessa parità}\}
    \end{array}
    $$

## Relazione di Equivalenza
!!! abstract "Definizione ― Relazione di Equivalenza"
    Una Relazione di Equivalenza si presenta quando una Relazione $\mathcal{R}$ è:
    
    - Riflessiva $(a \mathcal{R} b)$
    - Simmetrica $(a \mathcal{R} b, b \mathcal{R} a)$
    - Transitiva $(a \mathcal{R} b, b \mathcal{R} c, a \mathcal{R} c)$

??? example "Esempio"
    $$
    \begin{array}{c}
        \{(a,b) \in \mathbb{N} \times \mathbb{N} : a \text { e } b \text{ hanno la stessa parità}\}
    \end{array}
    $$

    - Un numero avrà sicuramente la stessa parità di se stesso.
    - Se $a$ ha la stessa parità di $b$, allora sicuramente $b$ ha la stessa parità di $a$.
    - Se $a$ ha la stessa parità di $b$, e $b$ ha la stessa parità di $c$, allora sicuramente $a$ ha la stessa parità di $c$.

## Inverso di una Relazione
!!! abstract "Definizione ― Inverso di una Relazione"
    L'inverso di una Relazione d'ordine (stretto) è ancora una Relazione d'ordine (stretto).

    $\mathcal{R}_1$ = mette in relazione tutte quelle coppie $(b,a)$ tale che $(a,b) \in \mathcal{R}$.

??? example "Esempio"
    $$
    \begin{array}{c}
    	A = \{1,2,3\} \\
        \mathcal{R} = \{(1,2),(2,3),(1,3)\} \\
        \mathcal{R}_{-1} = \{(2,1),(3,2),(3,1)\} \\
    \end{array}
    $$

## Classe di Equivalenza
!!! abstract "Definizione ― Classe di Equivalenza"
    Data una Relazione di Equivalenza $\mathcal{R}$ e dato un elemento $a$ dell'insieme $A$, l'insieme di tutti gli elementi $b$ che sono in relazione con $a$ ($\{b \in A:  b \mathcal{R} a\}$) si chiama Classe di Equivalenza di $A$ rispetto alla Relazione $\mathcal{R}$. 
    $$
    \begin{array}{c}
        [a]_\mathcal{R}
    \end{array}
    $$

??? example "Esempio"
    $$
    \begin{array}{c}
        A = \{1,2,3,4,5,6\} \\
        \mathcal{R} = \text{due numeri sono equivalenti se hanno la stessa parità.} \\
        \\
        [1]_\mathcal{R} = \{1,3,5\} \\
        [2]_\mathcal{R} = \{2,4,6\} \\
        [3]_\mathcal{R} = \{3,1,5\} \\
        \dots 
    \end{array}
    $$

## Quoziente
!!! abstract "Definizione ― Quoziente"
    L'insieme di tutte le Classi di Equivalenza si chiama Quoziente e si indica con $A/\mathcal{R}$.

??? example "Esempio"
    $$
    \begin{array}{c}
        A = \{1,2,3,4,5,6\} \\
        \mathcal{R} = \text{due numeri sono equivalenti se hanno la stessa parità.} \\
        \\
        [1]_\mathcal{R} = \{1,3,5\} \\
        [2]_\mathcal{R} = \{2,4,6\} \\
        [3]_\mathcal{R} = \{1,3,5\} \\
        [4]_\mathcal{R} = \{2,4,6\} \\
        [5]_\mathcal{R} = \{1,3,5\} \\
        [6]_\mathcal{R} = \{2,4,6\} \\
        \\
        A/\mathcal{R} = \{\{1,3,5\},\{2,4,6\}\}
    \end{array}
    $$

## Partizione
!!! abstract "Definizione ― Partizione"
    Dato un insieme $A$, una famiglia $P$ di sottoinsiemi di $A$ si chiama Partizione di $A$ se ogni $a \in A$ appartiene ad uno ed un solo insieme della famiglia $P$.

    Quindi, $P$ è una partizione di $A$ se possiamo verificare che soddisfa le seguenti due condizioni:

    - ogni elemento di $A$ appartiene ad uno ed un solo sottoinsieme di $P$.
    - i sottoinsiemi di $P$ sono disgiunti e la loro unione è $A$.

??? example "Esempio"
    $$
    \begin{array}{c}
        A = \{1,2,3,4,5,6\} \\
        P = \{\{1,3,5\},\{2,4,6\}\} \\
        \\
        \text{Verifichiamo che P soddisfi le condizioni:} \\
        \text{1) Ogni elemento di } A \text{ appartiene ad uno ed un solo sottoinsieme di } P \text{:} \\
        1 \in \{1,3,5\} \\
        2 \in \{2,4,6\} \\
        3 \in \{1,3,5\} \\
        4 \in \{2,4,6\} \\
        5 \in \{1,3,5\} \\
        6 \in \{2,4,6\} \\
        \\
        \text{2) I sottoinsiemi di } P \text{ sono disgiunti e la loro unione è } A \text{:} \\
        \{1,3,5\} \cap \{2,4,6\} = \emptyset \\
        \{1,3,5\} \cup \{2,4,6\} = \{1,2,3,4,5,6\} = A
    \end{array}
    $$

<figure markdown="1">
![image](\metodi\assets\mod4_partizione.png)
</figure>

- Nell'esempio raffigurato, la Partizione $P$ è composta da 4 sottoinsiemi, in cui ogni $a \in A$ si trova in uno ed uno soltanto di questi 4 sottoinsiemi.

!!! abstract "Definizione ― Relazioni di una Partizione"
    Data una Partizione $P$ di $A$, indichiamo con $\sim_P$ la relazione su $A$ tale che $a \sim_P b$ se e solo se $a,b \in X$, per qualche $X \in P$.

    Possiamo quindi costruire una Relazione $\sim_P$ mettendo in relazione quegli elementi di $A$ che appartengono allo stesso elemento della Partizione.

??? example "Esempio"
    $$
    \begin{array}{c}
        A = \{a,b,c,d,e,f\} \\
        P = \{\{a,b\},\{c,d,e\},\{f\}\} \\
        \\
        a \sim_P b \\
        d \sim_P c \\
        f \sim_P f \\
        e \not\sim_P a
    \end{array}
    $$

??? note "Note aggiuntive"
    - Le Relazioni di Equivalenza sono Partizioni e viceversa.