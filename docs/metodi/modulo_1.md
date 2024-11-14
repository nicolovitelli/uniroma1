---
title: Modulo 1
---

## Insiemi

!!! abstract "Definizione ― Insiemi"
    Un Insieme è una qualsiasi collezione non ordinata di elementi su cui è possibile determinare una condizione di appartenenza.

## Proposta di Von Neumann

$$
    \begin{array}{c}
        0 = \emptyset \\
        1 = \{\emptyset\} \\
        2 = \{\{\emptyset\},\emptyset\} \\
        3 = \{\{\emptyset\}, \emptyset, \{\{\emptyset\},\emptyset\}\}
    \end{array}
$$

## Assioma di Estensione
!!! abstract "Definizione ― Assioma di Estensione"
    Due insiemi sono uguali se e solo se hanno gli stessi elementi.

!!! abstract "Definizione ― Conseguenza dell'Assioma di Estensione"
    Se $A \subseteq B$ e $B \subseteq A$, allora $A = B$.

??? example "Esempio"
    $$
    \begin{array}{c}
        A = \{1,2,3\} \\
        B = \{3,2,1\} \\
        B = A
    \end{array}
    $$

## Relazione di Appartenenza
!!! abstract "Definizione ― Relazione di Appartenenza"
    $B \in A$ se e solo se $B$ è un elemento di $A$.

??? example "Esempio"
    $$
    \begin{array}{c}
        A = \{1,2,3\} \\
        B = 1 \\
        B \in A
    \end{array}
    $$

## Negazione di Appartenenza
!!! abstract "Definizione ― Negazione di Appartenenza"
    $B \not\in A$ se e solo se $B$ non è un elemento di $A$.

??? example "Esempio"
    $$
    \begin{array}{c}
        A = \{1,2,3\} \\
        B = 4 \\
        B \not\in A
    \end{array}
    $$

## Relazione di Sottoinsieme
!!! abstract "Definizione ― Relazione di Sottoinsieme"
    $B \subseteq A$ se e solo se ogni elemento di $B$ è un elemento di $A$.

??? example "Esempio"
    $$
    \begin{array}{c}
        A = \{1,2,3,\{4,5\}\} \\
        B = \{4,5\} \\
        B \subseteq A
    \end{array}
    $$

??? note "Note aggiuntive"
    - L'insieme vuoto è un sottoinsieme di qualsiasi insieme.
    $$
    \begin{array}{c}
        \emptyset \subseteq A
    \end{array}
    $$
    - Ogni insieme è sottoinsieme di se stesso.
    $$
    \begin{array}{c}
        A \subseteq A
    \end{array}
    $$

## Negazione di Sottoinsieme
!!! abstract "Definizione ― Negazione di Sottoinsieme"
    $B \not\subseteq A$ se e solo se almeno un elemento di $B$ non è un elemento di $A$.

??? example "Esempio"
    $$
    \begin{array}{c}
        A = \{1,2,3,\{4,5\}\} \\
        B = \{4,5,6\} \\
        B \not\subseteq A
    \end{array}
    $$

## Predicato
!!! abstract "Definizione ― Predicato"
    Si indica con $\{x \in A : \mathcal{P}(x)\}$ l'insieme degli elementi di $A$ che godono della proprietà $\mathcal{P}$.

## Assioma di Specificazione
!!! abstract "Definizione ― Assioma di Specificazione"
    Ad ogni insieme $A$ e ad ogni frase $\mathcal{P}(x)$ che predica sugli elementi $x$ di $A$ corrisponde un insieme $\{x \in A : \mathcal{P}(x)\}$ i cui elementi sono esattamente quelli di $A$ che soddisfano $\mathcal{P}$.

??? example "Esempio"
    $$
    \begin{array}{c}
        A = \{1,2,3,4,5,6\} \\
        \mathcal{P}(x) = x \text{ è un numero paro} \\
        \{x \in A : \mathcal{P}(x)\} = \{2,4,6\}
    \end{array}
    $$