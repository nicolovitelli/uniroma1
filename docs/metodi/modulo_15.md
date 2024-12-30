---
title: Modulo 15
---

## Sistema Logico Assiomatico
!!! abstract "Definizione ― Sistema Logico Assiomatico"
	- Un Sistema nel quale vengono definiti un insieme di assiomi che sono delle proposizioni che vengono assunte senza dimostrazione (*quindi ovvie*).

!!! abstract "Definizione ― Regole di Inferenza"
	- Una regola di inferenza è un procedimento logico che stabilisce come è possibile dedurre una nuova proposizione (conclusione) a partire da una o più proposizioni già date (premesse), secondo schemi logici prestabiliti.

	- Formalmente, una regola di inferenza ha la forma:

	$$
    \begin{array}{c}
        \frac{C_1,C_2,\dots,C_n}{B}
    \end{array}
	$$

	- $C_1,C_2,\dots,C_n$ sono le premesse, cioè proposizioni che assumiamo siano vere.
	- $B$ è la conclusione che si può dedurre logicamente dalle premesse.
	- La regola afferma che, se le premesse sono vere, allora anche la conclusione è vera.

??? example "Esempio"
	- Il Modus Ponens è una regola di inferenza che permette di dedurre una conclusione da una premessa e un'implicazione. Si basa sul principio logico fondamentale:

	$$
    \begin{array}{c}
        \frac{A \quad A \rightarrow B}{B}
    \end{array}
	$$

	- $A$ è una proposizione considerata vera.
	- $A \rightarrow B$ è una proposizione che afferma "se $A$ allora $B$" (un'implicazione).
	- $B$ la proposizione che possiamo concludere come vera grazie alla regola.

## Assiomi di Hillbert

$$
    \begin{array}{c}
        A \rightarrow B \\
        B \rightarrow (A \rightarrow B) \\
        (A \rightarrow (B \rightarrow C)) \rightarrow (A \rightarrow B) \rightarrow (A \rightarrow C) \\
        (\neg A \rightarrow \neg B) \rightarrow (B \rightarrow A)
    \end{array}
$$

!!! abstract "Definizione ― Schema di Assioma"
	- Uno Schema di Assioma è una formula logica proposizionale che rimane valida (cioè è una tautologia) per tutti i valori di verità delle variabili proposizionali che contiene. In altre parole, è una struttura logica generale che rappresenta verità universali indipendentemente dalle proposizioni specifiche che la compongono.
	- Negli Assiomi di Hillbert, quelli rappresentati sono tutti Schemi di Assiomi perchè sono proprietà che valgono per qualunque formula e non solo per $A$ e $B$.

!!! abstract "Definizione ― Istanza di Assioma"
	- Un'istanza di un assioma è una proposizione logica specifica che si ottiene dallo schema di un'assioma sostituendo le variabili proposizionali ($A, B, C, \dots$) con proposizioni concrete o con altre formule logiche.
	- In altre parole, mentre uno schema di assioma rappresenta una regola generale e astratta, un'istanza di assioma è una forma concreta che segue lo schema, ottenuta scegliendo specifiche proposizioni o formule logiche per le variabili.

??? example "Esempio"
	$$
    	\begin{array}{c}
    		\text{Istanza del primo Assioma di Hillbert} \\
        	(P \rightarrow Q) \rightarrow (P \rightarrow Q) \\
        	\\
        	\text{Istanza del secondo Assioma di Hillbert} \\
        	(P \mathop{\wedge} Q) \rightarrow ((Q \rightarrow R) \rightarrow (P \mathop{\wedge} Q))
    	\end{array}
	$$

## Dimostrazione
!!! abstract "Definizione ― Dimostrazione"
	- Una Dimostrazione di una proposizione $A$ è una sequenza finita di proposizioni, di cui $A$ è l'ultima, ciascuna delle quali è una istanza di assioma o è ottenuta per Modus Ponens da due proposizioni che la precedono.

??? example "Esempio ― Dimostrazione della Derivazione"
	- Dimostriamo che lo schema d'assioma $A \rightarrow A$ è derivabile attraverso gli altri schemi, usando il Modus Ponens.
	
	$$
    \begin{array}{c}
    	\frac{A \rightarrow ((A \rightarrow A) \rightarrow A) \quad
    	(A \rightarrow ((A \rightarrow A) \rightarrow A)) \rightarrow (A \rightarrow (A \rightarrow A)) \rightarrow (A \rightarrow A)}{(A \rightarrow (A \rightarrow A)) \rightarrow (A \rightarrow A)}
    \end{array}
	$$
	
	- La prima parte:

		$$
	    \begin{array}{c}
	    		A \rightarrow ((A \rightarrow A) \rightarrow A)
	    \end{array}
		$$
	- rappresenta un'istanza del primo schema di Assioma di Hilbert, usiamo **Ax1** come notazione.
	- La seconda parte:

		$$
	    \begin{array}{c}
	    		(A \rightarrow ((A \rightarrow A) \rightarrow A)) \rightarrow (A \rightarrow (A \rightarrow A)) \rightarrow (A \rightarrow A)
	    \end{array}
	    $$
	- rappresenta un'istanza del secondo schema di Assioma di Hillbert, usiamo **Ax2** come notazione.
	- Infine, la terza parte:

		$$
	    \begin{array}{c}
	    		(A \rightarrow (A \rightarrow A)) \rightarrow (A \rightarrow A)
	    \end{array}
	    $$
	- rappresenta il Modus Ponens tra Ax1 e Ax2, usiamo **MP 1 2** come notazione.
	- Come facciamo a capire che rappresenta il Modus Ponens? Perchè MP 1 2 corrisponde alla seconda parte dell'istanza Ax2, mentre la prima parte dell'istanza Ax2 corrisponde esattamente a Ax1.
	- Possiamo continuare, usando il MP 1 2:

		$$
	    \begin{array}{c}
	    		\frac{A \rightarrow (A \rightarrow A) \quad (A \rightarrow (A \rightarrow A)) \rightarrow (A \rightarrow A)}{A \rightarrow A}
	    \end{array}
	    $$
	 - la prima parte rappresenta la prima parte dell'istanza MP 1 2, mentre il Modus Ponens finale rappresenta MP 3 4, cioè la seconda parte dell'istanza MP 1 2.
	 - Concludendo deducendo che $A \rightarrow A$ è derivabile dalle altre formule.

## Sistema di Hillbert
!!! abstract "Definizione ― Sistema di Hillbert"
	- Una Dimostrazione di una proposizione $A$ da un insieme $T = \{B_1,B_2,\dots,B_n\}$ è una sequenza finita di proposizioni, di cui $A$ è l'ultima, ciascuna delle quali è un'istanza di assioma, o una proposizione in $T$, o è ottenuta per Modus Ponens da due proposizioni che la precedono.
	
	$$
	   \begin{array}{c}
	    	B_1,B_2,\dots,B_n \vdash A
	   \end{array}
	 $$

	 - $A$ è derivabile da $B_1,B_2,\dots,B_n$

??? note "Note aggiuntive"
	- Si usa la notazione $\vdash A$ quando non ci sono premesse.
	- Similmente alla Deduzione Semantica:
	
	$$
	   \begin{array}{c}
	    	C_1,C_2,\dots,C_n,A \vdash B \\
	    	\text{ se e solo se } \\
	    	C_1,C_2,\dots,C_n \vdash A \rightarrow B
	   \end{array}
	$$



