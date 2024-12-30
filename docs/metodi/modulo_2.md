---
title: Modulo 2
---

## Intersezione
!!! abstract "Definizione ― Intersezione"
    L'Intersezione fra un insieme $A$ ed un insieme $B$ è l'insieme delle $x$ appartenenti ad $A$ tali che $x$ appartiene a $B$.
    $$
    \begin{array}{c}
        A \cap B = \{x \in A : x \in B\}
    \end{array}
	$$

<figure markdown="1">
![image](/uniroma1/assets/metodi/mod2_intersezione.png)
</figure>

??? math-adm "Proprietà Algebriche"
    $$
    \begin{array}{c}
        A \cap B = B \cap A \\
        A \cap A = A \\
        A \cap \emptyset = \emptyset \\
        \\
		\text{Proprietà Associativa} \\
	    A \cap (B \cap C) = (A \cap B) \cap C \\
	    \\
	    \text{Definizione di Sottoinsieme attraverso l'Intersezione} \\
	    A \cap B = A \text{ se e solo se } A \subseteq B \\
    \end{array}
	$$

	<figure markdown="1">
	![image](/uniroma1/assets/metodi/mod2_intersezione_subset.png)
	</figure>

??? example "Esempio"
    $$
    \begin{array}{c}
    	\text{Dimostrazione della Proprietà Associativa} \\
        A = \{1,2,3,4,5\} \\
	    B = \{3,4,5,6,7,8\} \\
	    C = \{4,6,9,10\} \\
	    (A \cap B) \cap C = \{3,4\} \cap C = \{4\} \\
	    (B \cap C) \cap A = \{4,6\} \cap A = \{4\} \\
    \end{array}
    $$

## Unione
!!! abstract "Definizione ― Unione"
    L'Unione fra un insieme $A$ ed un insieme $B$ è l'insieme delle $x$ appartenenti ad $A$ oppure appartenenti a $B$.
    $$
    \begin{array}{c}
        A \cup B = x \in A \text{ o } x \in B
    \end{array}
	$$

<figure markdown="1">
![image](/uniroma1/assets/metodi/mod2_unione.png)
</figure>

!!! abstract "Definizione ― Assioma dell'Unione"
    Per ogni collezione $C$ di insiemi $(A,B)$ esiste un insieme $U_C$ che contiene tutti gli elementi che appartengono ad almeno un insieme della collezione.
    $$
    \begin{array}{c}
        A \cup B = \{x \in U_{AB} : x \in A \text{ o } x \in B\}
    \end{array}
	$$

??? math-adm "Proprietà Algebriche"
    $$
    \begin{array}{c}
        A \cup \emptyset = A \\
        \\
        \text{Proprietà della Simmetria} \\
        A \cup B = B \cup A \\
        \\
        \text{Proprietà Associativa} \\
        A \cup (B \cup C) = (A \cup B) \cup C \\
        \\
        \text{Proprietà dell'Impotenza} \\
        A \cup B = (A \cup A) \cup B = A \cup (A \cup B) = A \subseteq (A \cup B)
    \end{array}
	$$

??? example "Esempio"
    $$
    \begin{array}{c}
    	\text{Dimostrazione dell'Operatore Unione} \\
        \text{se } a \in \{x \in A:P(x) \text{ o } Q(x)\} \\
	    \text{allora vale } P(a) \text{ o } Q(a) \\
	    \text{quindi se vale } P(a) \\
	    \text{allora } a \in \{x \in A:P(x)\} \\
	    \text{e dunque } a \in \{x \in A:P(x)\} \cup \{x \in A:Q(x)\} \\
	    \\
	    \text{Dimostrazione della Proprietà Associativa} \\
	    A = \{1,2,3\} \\
	    B = \{4,5,6\} \\
	    C = \{7,8,9\} \\
	    (A \cup B) \cup C = \{1,2,3,4,5\} \cup C = \{1,2,3,4,5,6,7,8,9\} \\
	    (B \cup C) \cup A = \{4,5,6,7,8,9\} \cup A = \{4,5,6,7,8,9,1,2,3\} \\
	    \\
	    \text{Definizione di Sottoinsieme attraverso l'Unione} \\
	    A \cup B = B \text{ se e solo se } A \subseteq B \\
    \end{array}
    $$

    <figure markdown="1">
	![image](/uniroma1/assets/metodi/mod2_intersezione_subset.png)
	</figure>

## Differenza
!!! abstract "Definizione ― Differenza"
    La Differenza fra un insieme $A$ ed un insieme $B$ è l'insieme delle $x$ appartenenti ad $A$ che non appartengono a $B$.
    $$
    \begin{array}{c}
        A - B = x \in A : x \not\in B
    \end{array}
	$$

<figure markdown="1">
![image](/uniroma1/assets/metodi/mod2_differenza.png)
</figure>

??? math-adm "Proprietà Algebriche"
    $$
    \begin{array}{c}
        A \cap B = A - (A - B)
    \end{array}
	$$

??? example "Esempio"
    $$
    \begin{array}{c}
    	A \cap B = A - (A - B) \\
    	A = \{1,2,3,4\} \\
	    B = \{3,4,5,6\} \\
	    A - B = \{1,2\} \\
	    A - (A-B) = \{1,2,3,4\} - \{1,2\} = \{3,4\} \\
	    A \cup B = \{3,4\}
    \end{array}
    $$

## Complemento
!!! abstract "Definizione ― Complemento"
    $$
    \begin{array}{c}
        \overline{A} = \{x \in B : x \not\in A\}
    \end{array}
	$$

<figure markdown="1">
![image](/uniroma1/assets/metodi/mod2_complemento.png)
</figure>

??? math-adm "Proprietà Algebriche"
    $$
    \begin{array}{c}
        \text{Equazioni di De Morgan} \\
        \overline{(A \cap B)}= \overline{A} \cup \overline{B} \\
        \overline{(A \cup B)} = \overline{A} \cap \overline{B}
    \end{array}
	$$

??? example "Esempio"
    $$
    \begin{array}{c}
    	A = \{1,2,3,4\} \\
	    B = \{3,4,5,6\} \\
	    \overline{B} = \{1,2\}
    \end{array}
    $$

## Potenza
!!! abstract "Definizione ― Potenza"
    L'insieme delle parti, o insieme potenza, è l'insieme dei sottoinsiemi di $A$.

    $$
    \begin{array}{c}
        \mathcal{P}(A)
    \end{array}
    $$

??? note "Note aggiuntive"
    - La Cardinalità dell'insieme potenza è uguale a $|\mathcal{P}(A)| = 2^n$.

??? example "Esempio"
    $$
    \begin{array}{c}
    	A = \{1,2\} \\
	    \mathcal{P}(A) = \{\emptyset,\{1,2\},1,2\} \\
	    |A| = |\mathcal{P}(A)| = 2^n = 4
    \end{array}
    $$

## Coppie Ordinate
!!! abstract "Definizione ― Coppie Ordinate"
    Sono delle coppie in cui l'ordine con cui vengono rappresentate è importante.

    $$
    \begin{array}{c}
        (a,b) \neq (b,a) : \{a,b\} = \{b,a\}
    \end{array}
	$$

??? note "Note aggiuntive"
    - Per rappresentare l'eguaglianza tra una coppia ordinata ed un insieme si usa questa equazione:
    
    $$
    \begin{array}{c}
        (a,b) = \{a,\{a,b\}\}
    \end{array}
	$$

## Prodotto Cartesiano
!!! abstract "Definizione ― Prodotto Cartesiano"
    Dati due insiemi $A$ e $B$, si dice Prodotto Cartesiano l'insieme di tutte le coppie ordinate $A$ e $B$ tali che $a$ è un elemento di $A$ e $b$ è un elemento di $B$.

    $$
    \begin{array}{c}
        A \times B = \forall \, (a,b), \, a \in A : b \in B
    \end{array}
    $$

??? math-adm "Proprietà Algebriche"
    $$
    \begin{array}{c}
        A \times \emptyset = \emptyset \times A = \emptyset \\
    	A \times (B \cup C) = (A \times B)\cup(A \times C) \\
    	A \times (B \cap C)=(A \times B)\cap(A \times C)
    \end{array}
	$$

??? example "Esempio"
    $$
    \begin{array}{c}
        A = \{\emptyset\} \\
        A \times A = \{(\emptyset,\emptyset),\{\}\}
    \end{array}
    $$