---
title: Modulo 9
---

## Reticoli
!!! abstract "Definizione ― Reticolo"
    Un Reticolo è un insieme (parzialmente) ordinato $S$ tale che, per ogni $a, b \in S$, esistono $inf(a,b)$ e $sup(a,b)$.

	$$
    \begin{array}{c}
    \forall \text{ } a,b \in A \\
    \exists \text{ } sup(a,b) \text{ e } inf(a,b)
    \end{array}
	$$

!!! abstract "Definizione ― Estremi"
    
    - L'estremo inferiore (detto anche *Meet*, rappresentato con il simbolo $\mathop{\wedge}$) è il più grande di tutti quegli elementi che sono più piccoli di $a$ e $b$.

    $$
    \begin{array}{c}
    	a \mathop{\wedge} b = inf(a,b)
    \end{array}
	$$

	- L'estremo superiore (detto anche *Join*, rappresentato con il simbolo $\mathop{\vee}$) è il più piccolo di tutti quegli elementi che sono più grandi di $a$ e $b$.

	$$
    \begin{array}{c}
    	x \mathop{\vee} y = sup(x,y)
    \end{array}
	$$

!!! math-adm "Proprietà Algebriche"

	- **Commutatività**: l'ordine degli elementi non influenza il risultato.

	$$
	    \begin{array}{c}
	    	x \mathop{\wedge} y = y \mathop{\wedge} x \\
	    	y \mathop{\vee} x = x \mathop{\vee} y
	    \end{array}
	$$

	- **Associatività**: la disposizione delle parentesi non influenza il risultato.

	$$
	    \begin{array}{c}
	    	x \mathop{\wedge} (y \mathop{\wedge} z) = (x \mathop{\wedge} y) \mathop{\wedge} z \\
	    	x \mathop{\vee} (y \mathop{\vee} z) = (y \mathop{\vee} x) \mathop{\vee} z
	    \end{array}
	$$

	- **Assorbimento**: assicura che combinare un elemento con il risultato dell'intersezione (o unione) dell'elemento con un altro non cambia il risultato.

	$$
	    \begin{array}{c}
	    	x \mathop{\wedge} (x \mathop{\wedge} y) = x \\
	    	x \mathop{\vee} (x \mathop{\vee} y) = x
	    \end{array}
	$$

	- **Idempotenza**: l'operazione applicata due volte all'elemento restituisce l'elemento stesso.

	$$
	    \begin{array}{c}
	    	x \mathop{\wedge} x = x \\
	    	x \mathop{\vee} x = x
	    \end{array}
	$$

??? example "Esempio"

	- Sia $L = \{a,b\}$ e verifichiamo se l'insieme $\{L,\subseteq\}$ è un reticolo.
	- Per farlo, costruiamo l'insieme delle parti di $L$:

    $$
    \begin{array}{c}
    	\mathcal{P}(L) = \{\emptyset, \{a\},\{b\},\{a,b\}\}
    \end{array}
    $$

    - Verifichiamo se $\mathcal{P}(L)$ è un insieme parzialmente ordinato:

    $$
    \begin{array}{c}
    	\text{Riflessività: } x \subseteq x : x \in \mathcal{P}(L) \\
    	\text{Antisimmetria: se } x \subseteq y \text{ e } y \subseteq x, \text{ allora } x = y \\
    	\text{Transitività: se } x \subseteq y \text{ e } y \subseteq z, \text{ allora } x \subseteq z 
    \end{array}
    $$

    - Calcoliamo infimo e supremo per ogni coppia di sottoinsiemi in $\mathcal{P}(L)$:

    	- Coppia $\{\emptyset,\{a\}\}$:
    		- Infimo: $\emptyset \cap \{a\} = \emptyset$
    		- Supremo: $\emptyset \cup \{a\} = \{a\}$
    	- Coppia $\{\emptyset, \{b\}\}$:
    		- Infimo: $\emptyset \cap \{b\} = \emptyset$
    		- Supremo: $\emptyset \cup \{b\} = \{b\}$
    	- Coppia $\{\emptyset, \{a,b\}\}$:
    		- Infimo: $\emptyset \cap \{a,b\} = \emptyset$
    		- Supremo: $\emptyset \cup \{a,b\} = \{a,b\}$
    	- Coppia $\{\{a\},\{b\}\}$:
    		- Infimo: $\{a\} \cap \{b\} = \emptyset$
    		- Supremo: $\{a\} \cup \{b\} = \{a,b\}$
    	- $\dots$
    - Conclusione: ogni coppia di elementi in $\mathcal{P}(L)$ ha sia un infimo (intersezione) che un supremo (unione). Quindi, $\mathcal{P}(L)$, con la relazione di sottoinsieme $\subseteq$, soddisfa le condizioni per essere un reticolo.

    ---

    - Ora prendiamo come insieme $S = \{2,3,6\}$ e la Relazione di Divisibilità (*$a | b$ se e solo se $a$ è un divisore di $b$*).
    - Costruiamo l'insieme delle parti di $S$:

    $$
    \begin{array}{c}
    	\mathcal{P}(S) = \{\emptyset, \{2\},\{3\}, \{6\},\{2,3\},\{2,6\},\{3,6\}\}
    \end{array}
    $$
    
    - Verifichiamo che la relazione sia parzialmente ordinata:

    $$
    \begin{array}{c}
    	\text{Riflessività: ogni elemento è divisibile per se stesso}  \\
    	\text{Antisimmetria: se } a | b \text{ e } b | a, \text{ allora } a = b \\
    	\text{Transitività: se } a | b \text{ e } b | c, \text{ allora } a | c 
    \end{array}
    $$

    - Calcoliamo infimo e supremo per ogni coppia di sottoinsiemi in $\mathcal{P}(S)$:

    	- Coppia $\{2,3\}$:
    		- Infimo: non esiste un infimo per $2$ e $3$ in $S$, perchè il massimo comune divisore di $2$ e $3$ è $1$, che non appartiene a $S$.
    		- Supremo: non esiste un supremo per $2$ e $3$ in $S$, perchè il minimo comune multiplo di $2$ e $3$ è $6$, che è effettivamente in $S$. Tuttavia, poichè non esiste un infimo, già questo ci impedisce di considerare $S$ come un reticolo.
    	- $\dots$

   	- Conclusione: per la coppia $\{2,3\}$ non esiste un infimo all'interno dell'insieme $S$, quindi l'insieme $S = \{2,3,6\}$ con la relazione di divisibilità non è un reticolo.

!!! abstract "Definizione ― Reticolo Distributivo"
    Un Reticolo Distributivo è un reticolo dove ogni elemento è verificato dalla proprietà distributiva.

??? example "Esempio ― Reticolo non distributivo"

	<figure markdown="1">
    ![image](assets\mod9_reticoloNonDis.png)
    </figure>

    $$
    \begin{array}{c}
    	b \mathop{\vee} c = sup(b,c) = \text{ pallino arancione} \\
    	a \mathop{\wedge} sup(b,c) = inf(a, \text{ pallino arancione}) = a \\
    	\text{quindi..} \\
    	a \mathop{\wedge} (b \mathop{\vee} c) = a \mathop{\wedge} \text{ pallino arancione} = a
    \end{array}
    $$

    $$
    \begin{array}{c}
    	(a \mathop{\wedge} b) = inf(a,b) = \text{ pallino celeste} \\
    	(a \mathop{\wedge} c) = inf(a,c) = \text{ pallino celeste} \\
    	\text{pallino celeste} \mathop{\vee} \text{pallino celeste} = sup(\text{pallino celeste}, \text{pallino celeste}) = \text{pallino celeste} \neq a
    \end{array}
    $$

    - Conclusione: il reticolo non è distributivo altrimenti le due proprietà avrebbero avuto lo stesso risultato.