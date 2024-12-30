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

    $$
    \begin{array}{c}
        A \subseteq B \mathop{\wedge} B \subseteq A \rightarrow A = B
    \end{array}
    $$


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
    $$
    \begin{array}{c}
        a \in A \iff a \text{ è un elemento di } A
    \end{array}
    $$

??? example "Esempio"
    $$
    \begin{array}{c}
        A = \{1,2,3\} \\
        a = 1 \\
        a \in A
    \end{array}
    $$

## Negazione di Appartenenza
!!! abstract "Definizione ― Negazione di Appartenenza"
    $$
    \begin{array}{c}
        a \not\in A \iff a \text{ non è un elemento di } A
    \end{array}
    $$

??? example "Esempio"
    $$
    \begin{array}{c}
        A = \{1,2,3\} \\
        a = 4 \\
        a \not\in A
    \end{array}
    $$

## Relazione di Sottoinsieme
!!! abstract "Definizione ― Relazione di Sottoinsieme"
    $$
    \begin{array}{c}
        B \subseteq A \iff \forall \, b \in B : b \in A
    \end{array}
    $$

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
    $$
    \begin{array}{c}
        B \not\subseteq A \iff \exists \, b \in B : b \not\in A
    \end{array}
    $$

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
    Un Predicato è una proprietà applicata su un elemento di un insieme.
    $$
    \begin{array}{c}
        \{x \in A : \mathcal{P}(x)\}
    \end{array}
    $$

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