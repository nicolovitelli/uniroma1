---
title: Esercizi
---

## Esercizi - Parte XVII

??? question "Domande"

	1. **Assioma di Estensione**: Due insiemi \( A \) e \( B \) sono considerati uguali se e solo se:  
		- [ ] Sono entrambi sottoinsiemi di un insieme \( C \).  
		- [ ] Contengono lo stesso numero di elementi.  
		- [ ] Contengono esattamente gli stessi elementi.  
		- [ ] Sono entrambi infiniti.  

	2. **Relazione e Negazione di Appartenenza**: Se \( x \in U \) e \( x \notin A \), quale delle seguenti affermazioni è sempre vera?  
		- [ ] \( x \in A^c \)  
		- [ ] \( x \in A \)  
		- [ ] \( x \notin U \)  
		- [ ] \( x \in A \cup A^c \)  

	3. **Relazione e Negazione di Sottoinsieme**: Se \( A = \{1, 2, 3\} \) e \( B = \{2, 3, 4\} \), quale affermazione è falsa?  
		- [ ] \( A \subseteq A \cup B \)  
		- [ ] \( A \cap B \subseteq A \)  
		- [ ] \( A \subseteq B \)  
		- [ ] \( A \cap B = \{2, 3\} \)  

	4. **Operatori Insiemistici**: Qual è \( A \cap B \) se \( A = \{a, b, c\} \) e \( B = \{b, c, d\} \)?  
		- [ ] \( \{a, b, c, d\} \)  
		- [ ] \( \{b, c\} \)  
		- [ ] \( \{a, d\} \)  
		- [ ] \( \emptyset \)  

	5. **Complemento**: Se \( U = \{1, 2, 3, 4, 5\} \) è l'universo e \( B = \{1, 3, 5\} \), qual è \( B^c \)?  
		- [ ] \( \{1, 2, 3\} \)  
		- [ ] \( \{2, 4\} \)  
		- [ ] \( \{1, 3, 5\} \)  
		- [ ] \( \emptyset \)  

	6. **Potenza e Cardinalità**: Se un insieme \( A \) ha 3 elementi, qual è la cardinalità dell'insieme potenza di \( A \)?  
		- [ ] 3  
		- [ ] 6  
		- [ ] 8  
		- [ ] 9  

	7. **Prodotto Cartesiano**: Se \( A = \{1, 2, 3\} \) e \( B = \{a, b\} \), quanti elementi ha \( A \times B \)?  
		- [ ] 3  
		- [ ] 5  
		- [ ] 6  
		- [ ] 9  

	8. **Relazioni di un Insieme**: Se un insieme \( X \) ha 4 elementi, quante relazioni binarie possono essere definite su \( X \)?  
		- [ ] 256  
		- [ ] 512  
		- [ ] 2,048  
		- [ ] 65,536  

	9. **Proprietà delle Relazioni**: La relazione "è uguale a" su \( \mathbb{R} \) è:  
		- [ ] Riflessiva ma non simmetrica.  
		- [ ] Riflessiva, simmetrica e transitiva.  
		- [ ] Simmetrica ma non riflessiva.  
		- [ ] Transitiva ma non simmetrica.  

	10. **Reticoli**: In un reticolo, il join (\( \lor \)) di due elementi rappresenta:  
		- [ ] Il massimo tra due elementi.  
		- [ ] Il minimo tra due elementi.  
		- [ ] L’intersezione di due elementi.  
		- [ ] La differenza tra due elementi.  

??? lightbulb "Soluzioni"

	1. **Assioma di Estensione**  
	   Risposta: Contengono esattamente gli stessi elementi.  
		- Spiegazione: L'assioma di estensione stabilisce che due insiemi sono uguali se contengono esattamente gli stessi elementi, indipendentemente dall’ordine o dalla rappresentazione.

	2. **Relazione e Negazione di Appartenenza**  
	   Risposta: \( x \in A^c \).  
		- Spiegazione: Se \( x \notin A \) ma appartiene all'universo \( U \), per definizione appartiene al complemento di \( A \), cioè \( A^c \).

	3. **Relazione e Negazione di Sottoinsieme**  
	   Risposta: \( A \subseteq B \).  
		- Spiegazione: \( A \subseteq B \) è falso, perché \( 1 \in A \) ma \( 1 \notin B \). Le altre affermazioni sono vere.

	4. **Operatori Insiemistici**  
	   Risposta: \( \{b, c\} \).  
		- Spiegazione: L’intersezione \( A \cap B \) contiene gli elementi comuni a \( A \) e \( B \). Qui sono \( b \) e \( c \).

	5. **Complemento**  
	   Risposta: \( \{2, 4\} \).  
		- Spiegazione: Il complemento di \( B \) rispetto a \( U \) contiene tutti gli elementi di \( U \) che non sono in \( B \), cioè \( \{2, 4\} \).

	6. **Potenza e Cardinalità**  
	   Risposta: 8.  
		- Spiegazione: L'insieme delle parti (o insieme potenza) di un insieme con \( n \) elementi ha \( 2^n \) sottoinsiemi. Per \( n = 3 \), abbiamo \( 2^3 = 8 \).

	7. **Prodotto Cartesiano**  
	   Risposta: 6.  
		- Spiegazione: Il prodotto cartesiano \( A \times B \) contiene \( |A| \cdot |B| = 3 \cdot 2 = 6 \) coppie ordinate.

	8. **Relazioni di un Insieme**  
	   Risposta: 65,536.  
		- Spiegazione: Per un insieme con \( n \) elementi, il numero di relazioni binarie possibili è \( 2^{n^2} \). Per \( n = 4 \), abbiamo \( 2^{4^2} = 2^{16} = 65,536 \).

	9. **Proprietà delle Relazioni**  
	   Risposta: Riflessiva, simmetrica e transitiva.  
		- Spiegazione: L'uguaglianza (\( = \)) su \( \mathbb{R} \) soddisfa tutte e tre le proprietà: riflessività (\( a = a \)), simmetria (\( a = b \implies b = a \)) e transitività (\( a = b \land b = c \implies a = c \)).

	10. **Reticoli**  
	    Risposta: Il massimo tra due elementi.  
		- Spiegazione: Nel linguaggio dei reticoli, il join (\( \lor \)) di due elementi rappresenta il massimo comune rispetto alla relazione d'ordine.

---

## Esercizi - Parte XVI

??? question "Domande"

	1. Due insiemi $A$ e $B$ sono uguali se:  
		- [ ] Hanno la stessa cardinalità.  
		- [ ] Contengono esattamente gli stessi elementi.  
		- [ ] Sono entrambi infiniti.  
		- [ ] Sono entrambi sottoinsiemi propri di un insieme $C$.

	2. Se $x \notin A$, quale affermazione è sempre vera?  
		- [ ] $x \notin A^c$  
		- [ ] $x \in A$  
		- [ ] $x \in A^c$  
		- [ ] $x \in A \cap A^c$

	3. Se $A \not\subseteq B$, quale delle seguenti affermazioni è vera?  
		- [ ] Esiste almeno un elemento di $A$ che non è in $B$.  
		- [ ] Tutti gli elementi di $A$ sono anche in $B$.  
		- [ ] $A \cap B = \emptyset$.  
		- [ ] $A = B$.

	4. Quale affermazione descrive l’assioma di specificazione?  
		- [ ] Consente di creare un sottoinsieme specificando una proprietà.  
		- [ ] Consente di creare un insieme vuoto.  
		- [ ] Consente di confrontare due insiemi.  
		- [ ] Consente di unire due insiemi.

	5. Se $A = \{1, 2, 3\}$ e $B = \{2, 3, 4\}$, qual è $A \setminus B$?  
		- [ ] $\{1, 2, 3\}$  
		- [ ] $\{2, 3\}$  
		- [ ] $\{1\}$  
		- [ ] $\{4\}$

	6. Se $U = \{1, 2, 3, 4, 5\}$ è l’universo e $A = \{2, 4\}$, qual è $A^c$?  
		- [ ] $\{1, 2, 3\}$  
		- [ ] $\{1, 3, 5\}$  
		- [ ] $\{2, 4\}$  
		- [ ] $\emptyset$

	7. Qual è la cardinalità dell'insieme potenza di un insieme con 4 elementi?  
		- [ ] 8  
		- [ ] 16  
		- [ ] 32  
		- [ ] 64

	8. Se $A = \{1, 2\}$ e $B = \{x, y, z\}$, quanti elementi ha $A \times B$?  
		- [ ] 5  
		- [ ] 6  
		- [ ] 8  
		- [ ] 9

	9. Quante relazioni binarie possono essere definite su un insieme $A$ con 2 elementi?  
		- [ ] 2  
		- [ ] 4  
		- [ ] 16  
		- [ ] 32

	10. Quale proprietà manca alla relazione "è divisibile per" ($a \mid b$) sui numeri interi?  
		- [ ] Riflessività  
		- [ ] Simmetria  
		- [ ] Transitività  
		- [ ] Antisimmetria

	11. Se $X \subseteq Y$, allora la chiusura di $X$ in $Y$ è:  
		- [ ] $X \cup Y$  
		- [ ] L'intersezione di tutti i chiusi contenenti $X$.  
		- [ ] Il complemento di $X$.  
		- [ ] L'unione di $X$ con tutti gli aperti.

	12. Un insieme è $p$-maggiorabile se:  
		- [ ] Ogni sottoinsieme finito ha un massimo rispetto a una relazione d’ordine.  
		- [ ] Ogni elemento ha un lightbulbore.  
		- [ ] Ogni sottoinsieme ha un massimo.  
		- [ ] Nessun elemento può essere comparato.

	13. Quale delle seguenti è un esempio di ordinamento parziale?  
		- [ ] L’insieme dei numeri interi con $\leq$.  
		- [ ] L’insieme delle parti di un insieme $S$, ordinato per inclusione.  
		- [ ] L’insieme dei numeri reali con $<$.  
		- [ ] L’insieme dei numeri naturali con $>$.

	14. Quale funzione è suriettiva?  
		- [ ] $f: \mathbb{R} \to \mathbb{R}$, $f(x) = x^2$.  
		- [ ] $f: \mathbb{R} \to [0, \infty)$, $f(x) = x^2$.  
		- [ ] $f: \mathbb{R} \to \mathbb{R}$, $f(x) = x + 1$.  
		- [ ] $f: \mathbb{N} \to \mathbb{N}$, $f(x) = 2x$.

	15. In un reticolo, il meet ($\land$) di due elementi rappresenta:  
		- [ ] Il massimo tra due elementi.  
		- [ ] Il minimo tra due elementi.  
		- [ ] L’unione di due elementi.  
		- [ ] La differenza tra due elementi.

??? lightbulb "Soluzioni"

	1. **Assioma di Estensione**  
	   Risposta: Contengono esattamente gli stessi elementi.  
		- Spiegazione: L'assioma di estensione afferma che due insiemi sono uguali se contengono esattamente gli stessi elementi, indipendentemente da come sono rappresentati.

	2. **Relazione e Negazione di Appartenenza**  
	   Risposta: $x \in A^c$.  
		- Spiegazione: Se $x \notin A$, allora appartiene al complemento di $A$, che contiene tutti gli elementi che non sono in $A$.

	3. **Relazione e Negazione di Sottoinsieme**  
	   Risposta: Esiste almeno un elemento di $A$ che non è in $B$.  
		- Spiegazione: Se $A \not\subseteq B$, significa che c’è almeno un elemento di $A$ che non appartiene a $B$.

	4. **Assioma di Specificazione**  
	   Risposta: Consente di creare un sottoinsieme specificando una proprietà.  
		- Spiegazione: L'assioma di specificazione consente di definire un sottoinsieme di un insieme dato includendo solo gli elementi che soddisfano una proprietà specifica.

	5. **Operatori Insiemistici**  
	   Risposta: $\{1\}$.  
		- Spiegazione: $A \setminus B$ contiene gli elementi di $A$ che non appartengono a $B$. In questo caso, $A \setminus B = \{1\}$.

	6. **Complemento**  
	   Risposta: $\{1, 3, 5\}$.  
		- Spiegazione: Il complemento di $A$ rispetto all’universo $U$ contiene tutti gli elementi di $U$ che non sono in $A$, cioè $A^c = \{1, 3, 5\}$.

	7. **Potenza e Cardinalità**  
	   Risposta: 16.  
		- Spiegazione: L'insieme delle parti (o potenza) di un insieme con $n$ elementi ha $2^n$ sottoinsiemi. Per $n = 4$, abbiamo $2^4 = 16$.

	8. **Prodotto Cartesiano**  
	   Risposta: 6.  
		- Spiegazione: Il prodotto cartesiano $A \times B$ contiene $|A| \cdot |B| = 2 \cdot 3 = 6$ coppie ordinate.

	9. **Relazioni di un Insieme**  
	   Risposta: 16.  
		- Spiegazione: Per un insieme con $n$ elementi, il numero di relazioni binarie è $2^{n^2}$. Per $n = 2$, abbiamo $2^{2^2} = 2^4 = 16$.

	10. **Proprietà delle Relazioni**  
	    Risposta: Simmetria.  
		- Spiegazione: La relazione "è divisibile per" ($a \mid b$) non è simmetrica, perché $2 \mid 4$ ma $4 \nmid 2$.

	11. **Chiusura di un Insieme**  
	    Risposta: L'intersezione di tutti i chiusi contenenti $X$.  
		- Spiegazione: La chiusura di $X$ è il più piccolo chiuso contenente $X$, ottenuto come intersezione di tutti i chiusi che lo contengono.

	12. **P-Maggiorabile**  
	    Risposta: Ogni sottoinsieme finito ha un massimo rispetto a una relazione d’ordine.  
		- Spiegazione: Un insieme $p$-maggiorabile soddisfa la condizione che ogni suo sottoinsieme finito abbia un massimo.

	13. **Ordinamento Parziale**  
	    Risposta: L’insieme delle parti di un insieme $S$, ordinato per inclusione.  
		- Spiegazione: L'inclusione è un esempio classico di ordinamento parziale, poiché non tutti i sottoinsiemi di $S$ sono confrontabili.

	14. **Funzioni Iniettive e Suriettive**  
	    Risposta: $f: \mathbb{R} \to \mathbb{R}$, $f(x) = x + 1$.  
		- Spiegazione: La funzione $f(x) = x + 1$ è suriettiva perché ogni valore reale è raggiunto dal dominio $\mathbb{R}$.

	15. **Reticoli**  
	    Risposta: Il minimo tra due elementi.  
		- Spiegazione: Nel linguaggio dei reticoli, il meet ($\land$) di due elementi rappresenta il loro minimo.

---

## Esercizi - Parte XV

??? question "Domande"

	1. Quale affermazione descrive correttamente l’assioma di specificazione?  
		- [ ] Permette di definire un sottoinsieme specificando una proprietà.  
		- [ ] Permette di aggiungere nuovi elementi a un insieme dato.  
		- [ ] Permette di definire l’insieme vuoto.  
		- [ ] Permette di confrontare la cardinalità di due insiemi.

	2. Se $A = \{1, 2, 3\}$ e $B = \{3, 4, 5\}$, qual è $A \cup B$?  
		- [ ] $\{1, 2, 3\}$  
		- [ ] $\{3\}$  
		- [ ] $\{1, 2, 3, 4, 5\}$  
		- [ ] $\emptyset$

	3. Quante relazioni binarie possono essere definite su un insieme $A$ con 3 elementi?  
		- [ ] 8  
		- [ ] 9  
		- [ ] 27  
		- [ ] 512  

	4. Quale delle seguenti è una funzione suriettiva?  
		- [ ] $f: \mathbb{R} \to \mathbb{R}$, $f(x) = x^2$.  
		- [ ] $f: \mathbb{R} \to \mathbb{R}^+$, $f(x) = x^2$.  
		- [ ] $f: \mathbb{R} \to \mathbb{R}$, $f(x) = x + 1$.  
		- [ ] $f: \mathbb{N} \to \mathbb{N}$, $f(x) = 2x$.

	5. In una relazione di equivalenza su un insieme $A$, il quoziente di $A$ rispetto alla relazione:  
		- [ ] Contiene tutti gli elementi di $A$.  
		- [ ] Contiene le classi di equivalenza.  
		- [ ] È un sottoinsieme proprio di $A$.  
		- [ ] Non ha una struttura definita.

	6. Quale delle seguenti è un ordinamento parziale?  
		- [ ] I numeri interi con l'ordinamento $\leq$.  
		- [ ] L’insieme delle parti di un insieme $S$, ordinato per inclusione.  
		- [ ] I numeri reali con l'ordinamento $\leq$.  
		- [ ] I numeri naturali con l'ordinamento $<$.

	7. Quale dei seguenti passaggi è necessario per applicare il principio di induzione?  
		- [ ] Dimostrare che la proprietà vale per il passo $n + 1$ assumendo che valga per $n$.  
		- [ ] Dimostrare che la proprietà vale per ogni sottoinsieme finito.  
		- [ ] Dimostrare che la proprietà vale per $n = 0$.  
		- [ ] Dimostrare che la proprietà è vera per i numeri pari.

	8. Come viene costruita la polvere di Cantor?  
		- [ ] Eliminando l'intervallo $(1/3, 2/3)$ dall’intervallo $[0, 1]$, e ripetendo l'operazione per ogni intervallo restante.  
		- [ ] Considerando tutti i numeri razionali nell’intervallo $[0, 1]$.  
		- [ ] Rimuovendo tutti i numeri pari dall'intervallo $[0, 1]$.  
		- [ ] Dividendo $[0, 1]$ in intervalli di lunghezza $1/3$ e conservando solo i primi intervalli.

	9. L'hotel infinito di Hilbert è usato per illustrare:  
		- [ ] La cardinalità degli insiemi finiti.  
		- [ ] Il principio di induzione.  
		- [ ] La nozione di infinito numerabile.  
		- [ ] La struttura degli insiemi non numerabili.

	10. Quale delle seguenti affermazioni è vera per un reticolo distributivo?  
		- [ ] Ogni coppia di elementi ha un massimo e un minimo.  
		- [ ] La proprietà distributiva vale per tutte le operazioni.  
		- [ ] Esiste un elemento neutro per $\lor$.  
		- [ ] Gli elementi possono essere confrontati solo parzialmente.

??? lightbulb "Soluzioni"

	1. Risposta: Permette di definire un sottoinsieme specificando una proprietà.  
		- Spiegazione: L'assioma di specificazione consente di definire un sottoinsieme di un insieme dato includendo solo gli elementi che soddisfano una proprietà specifica.

	2. Risposta: $\{1, 2, 3, 4, 5\}$.  
		- Spiegazione: L'unione $A \cup B$ contiene tutti gli elementi di $A$ e $B$, quindi $\{1, 2, 3\} \cup \{3, 4, 5\} = \{1, 2, 3, 4, 5\}$.

	3. Risposta: 512.  
		- Spiegazione: Per un insieme con $n$ elementi, il numero di relazioni binarie possibili è $2^{n^2}$. Per $n = 3$, abbiamo $2^{3^2} = 2^9 = 512$.

	4. Risposta: $f: \mathbb{R} \to \mathbb{R}$, $f(x) = x + 1$.  
		- Spiegazione: $f(x) = x + 1$ è suriettiva perché ogni valore reale è raggiunto. Le altre opzioni non soddisfano questa proprietà.

	5. Risposta: Contiene le classi di equivalenza.  
		- Spiegazione: Il quoziente di un insieme rispetto a una relazione di equivalenza è l'insieme delle classi di equivalenza formate dagli elementi di $A$.

	6. Risposta: L’insieme delle parti di un insieme $S$, ordinato per inclusione.  
		- Spiegazione: L'ordinamento per inclusione è un ordinamento parziale, perché non tutti i sottoinsiemi sono confrontabili.

	7. Risposta: Dimostrare che la proprietà vale per il passo $n + 1$ assumendo che valga per $n$.  
		- Spiegazione: Questo è il passo induttivo del principio di induzione, necessario per dimostrare che la proprietà vale per tutti i numeri naturali.

	8. Risposta: Eliminando l'intervallo $(1/3, 2/3)$ dall’intervallo $[0, 1]$, e ripetendo l'operazione per ogni intervallo restante.  
		- Spiegazione: La polvere di Cantor viene costruita rimuovendo progressivamente il terzo centrale di ogni intervallo.

	9. Risposta: La nozione di infinito numerabile.  
		- Spiegazione: L'hotel infinito di Hilbert illustra che un insieme numerabile può accogliere infiniti nuovi elementi sfruttando la numerabilità.

	10. Risposta: Ogni coppia di elementi ha un massimo e un minimo.  
		- Spiegazione: Un reticolo è una struttura in cui ogni coppia di elementi ha un "join" (massimo) e un "meet" (minimo) definiti.

---

## Esercizi - Parte XIV

??? question "Domande"

	1. Due insiemi $A$ e $B$ sono uguali se:
		- [ ] Hanno lo stesso numero di elementi.
		- [ ] Contengono esattamente gli stessi elementi.
		- [ ] Sono entrambi sottoinsiemi propri di un insieme $C$.
		- [ ] Non contengono l'insieme vuoto.

	2. Se $A \subset B$, quale affermazione è falsa?
		- [ ] Ogni elemento di $A$ appartiene a $B$.
		- [ ] $A \cap B = A$.
		- [ ] $A \cup B = B$.
		- [ ] $A = B$.

	3. Se $U = \{1, 2, 3, 4, 5\}$ è l'universo e $A = \{2, 4\}$, qual è $A^c$?
		- [ ] $\{1, 2, 3\}$
		- [ ] $\{1, 3, 5\}$
		- [ ] $\{2, 4\}$
		- [ ] $\emptyset$

	4. Se $A = \{1, 2\}$ e $B = \{x, y\}$, quanti elementi ha $A \times B$?
		- [ ] 2
		- [ ] 4
		- [ ] 6
		- [ ] 8

	5. La relazione $=$ su $\mathbb{R}$ (uguaglianza) è:
		- [ ] Riflessiva, simmetrica e transitiva.
		- [ ] Simmetrica ma non riflessiva.
		- [ ] Transitiva ma non riflessiva.
		- [ ] Riflessiva e simmetrica ma non transitiva.

	6. Quale dei seguenti esempi rappresenta un ordinamento totale?
		- [ ] L'insieme dei numeri interi con l'ordinamento $\leq$.
		- [ ] L'insieme delle parti di un insieme $S$, ordinato per inclusione.
		- [ ] L'insieme delle classi di equivalenza di una relazione.
		- [ ] L'insieme dei numeri reali con l'ordinamento $>$.

	7. Un insieme è infinito se:
		- [ ] Contiene un numero finito di elementi.
		- [ ] Può essere messo in corrispondenza biunivoca con un suo sottoinsieme proprio.
		- [ ] È numerabile.
		- [ ] Contiene almeno un elemento.

	8. Qual è la base del principio di induzione matematica?
		- [ ] Dimostrare che la proprietà vale per il passo $n+1$.
		- [ ] Dimostrare che la proprietà vale per un numero naturale arbitrario.
		- [ ] Dimostrare che la proprietà vale per $n = 1$.
		- [ ] Dimostrare che la proprietà vale per ogni sottoinsieme finito.

	9. Qual è una caratteristica della polvere di Cantor?
		- [ ] Ha misura nulla ma cardinalità infinita.
		- [ ] È un sottoinsieme dei numeri razionali.
		- [ ] È numerabile e ha misura finita.
		- [ ] Contiene solo numeri interi.

	10. In un reticolo distributivo, qual è una proprietà fondamentale?
		- [ ] $x \lor (y \land z) = (x \lor y) \land (x \lor z)$.
		- [ ] $x \lor (y \lor z) = x \lor z$.
		- [ ] $x \land (y \lor z) = x \land y$.
		- [ ] $x \land y = x \lor y$.

??? lightbulb "Soluzioni"

	1. Risposta: Contengono esattamente gli stessi elementi.  
		- Spiegazione: L'assioma di estensione stabilisce che due insiemi sono uguali se contengono esattamente gli stessi elementi, indipendentemente dall'ordine o dalla rappresentazione.

	2. Risposta: $A = B$.  
		- Spiegazione: Se $A \subset B$ (e non $A = B$), $A$ è un sottoinsieme proprio di $B$, quindi $A = B$ è falso.

	3. Risposta: $\{1, 3, 5\}$.  
		- Spiegazione: Il complemento di $A$ rispetto a $U$ contiene tutti gli elementi di $U$ che non sono in $A$, quindi $A^c = \{1, 3, 5\}$.

	4. Risposta: 4.  
		- Spiegazione: Il prodotto cartesiano $A \times B$ ha $|A| \times |B| = 2 \times 2 = 4$ elementi.

	5. Risposta: Riflessiva, simmetrica e transitiva.  
		- Spiegazione: L'uguaglianza ($=$) soddisfa tutte e tre le proprietà: riflessività ($a = a$), simmetria ($a = b \implies b = a$) e transitività ($a = b \land b = c \implies a = c$).

	6. Risposta: L'insieme dei numeri interi con l'ordinamento $\leq$.  
		- Spiegazione: Un ordinamento totale permette il confronto tra qualsiasi coppia di elementi. $\leq$ sui numeri interi è un esempio classico.

	7. Risposta: Può essere messo in corrispondenza biunivoca con un suo sottoinsieme proprio.  
		- Spiegazione: Questa è una caratteristica fondamentale degli insiemi infiniti (come stabilito da Dedekind).

	8. Risposta: Dimostrare che la proprietà vale per $n = 1$.  
		- Spiegazione: La base dell'induzione consiste nel dimostrare che la proprietà è vera per il primo numero naturale $n = 1$.

	9. Risposta: Ha misura nulla ma cardinalità infinita.  
		- Spiegazione: La polvere di Cantor è un insieme infinito, non numerabile e con misura di Lebesgue pari a zero.

	10. Risposta: $x \lor (y \land z) = (x \lor y) \land (x \lor z)$.  
		- Spiegazione: Nei reticoli distributivi, le operazioni di join ($\lor$) e meet ($\land$) rispettano la proprietà distributiva.

---

## Esercizi - Parte XIII

??? question "Domande"

	1. Un reticolo è una struttura algebrica in cui:
		- [ ] Ogni coppia di elementi ha un massimo e un minimo.
		- [ ] Ogni elemento ha un inverso.
		- [ ] Esiste un solo elemento neutro.
		- [ ] Gli elementi sono disgiunti.

	2. Quale delle seguenti strutture è un esempio di reticolo distributivo?
		- [ ] L'insieme delle parti di un insieme $S$, ordinato per inclusione.
		- [ ] L'insieme dei numeri naturali con l'ordinamento $\leq$.
		- [ ] L'insieme dei numeri reali con l'ordinamento $>$.
		- [ ] L'insieme delle classi di equivalenza rispetto a una relazione di equivalenza.

	3. Vero o falso: ogni reticolo distributivo è anche un reticolo.

	4. In un reticolo distributivo, qual è la proprietà chiave che distingue la distribuzione?
		- [ ] $x \land (y \lor z) = (x \land y) \lor (x \land z)$
		- [ ] $x \lor (y \land z) = (x \lor y) \land (x \lor z)$
		- [ ] Entrambe le precedenti.
		- [ ] Nessuna delle precedenti.

	5. In un reticolo, l'operazione di join ($\lor$) corrisponde a:
		- [ ] Il massimo comune divisore.
		- [ ] Il minimo comune multiplo.
		- [ ] Il massimo tra due elementi.
		- [ ] Il minimo tra due elementi.

	6. Se un insieme $L$ è un reticolo, quale delle seguenti affermazioni è vera?
		- [ ] $L$ ha un massimo ma non un minimo.
		- [ ] Ogni coppia di elementi ha un minimo e un massimo.
		- [ ] Gli elementi di $L$ sono tutti numeri.
		- [ ] $L$ è un sottoinsieme dei numeri naturali.

	7. Quale dei seguenti esempi rappresenta un reticolo distributivo?
		- [ ] L'insieme delle parti di $\{1, 2, 3\}$ con unione e intersezione.
		- [ ] L'insieme dei numeri interi con massimo e minimo.
		- [ ] L'insieme delle classi di equivalenza di una relazione.
		- [ ] L'insieme dei numeri razionali con l'ordinamento $\leq$.

	8. Vero o falso: in un reticolo distributivo, il join e il meet rispettano le proprietà distributive tra loro.

	9. Se $A$ e $B$ sono elementi di un reticolo, quale delle seguenti affermazioni è vera?
		- [ ] $A \lor B = B \land A$
		- [ ] $A \lor A = A$
		- [ ] $A \land B = A \lor B$
		- [ ] $A \lor B = A \land A$

	10. Quale delle seguenti affermazioni descrive un reticolo non distributivo?
		- [ ] La legge distributiva non è valida per tutte le coppie di elementi.
		- [ ] Non esiste un massimo e un minimo.
		- [ ] Gli elementi non possono essere ordinati.
		- [ ] Non esiste un'operazione di join ($\lor$).

??? lightbulb "Soluzioni"

	1. Risposta: Ogni coppia di elementi ha un massimo e un minimo.
		- Spiegazione: Un reticolo è una struttura in cui ogni coppia di elementi ha un "join" ($\lor$, massimo) e un "meet" ($\land$, minimo) definiti.

	2. Risposta: L'insieme delle parti di un insieme $S$, ordinato per inclusione.
		- Spiegazione: L'insieme delle parti di $S$ con operazioni di unione ($\lor$) e intersezione ($\land$) è un esempio classico di reticolo distributivo.

	3. Risposta: Vero
		- Spiegazione: Ogni reticolo distributivo è, per definizione, anche un reticolo. Tuttavia, non tutti i reticoli sono distributivi.

	4. Risposta: Entrambe le precedenti.
		- Spiegazione: Un reticolo distributivo soddisfa entrambe le proprietà distributive:
	     $x \land (y \lor z) = (x \land y) \lor (x \land z)$ e 
	     $x \lor (y \land z) = (x \lor y) \land (x \lor z)$.

	5. Risposta: Il massimo tra due elementi.
		- Spiegazione: Nel linguaggio dei reticoli, il join ($\lor$) di due elementi rappresenta il loro massimo.

	6. Risposta: Ogni coppia di elementi ha un minimo e un massimo.
		- Spiegazione: La definizione di reticolo implica che ogni coppia di elementi ha un join ($\lor$) e un meet ($\land$).

	7. Risposta: L'insieme delle parti di $\{1, 2, 3\}$ con unione e intersezione.
		- Spiegazione: L'insieme delle parti con operazioni di unione e intersezione è un reticolo distributivo, poiché soddisfa entrambe le leggi distributive.

	8. Risposta: Vero
		- Spiegazione: Nei reticoli distributivi, le operazioni di join ($\lor$) e meet ($\land$) rispettano le proprietà distributive.

	9. Risposta: $A \lor A = A$
		- Spiegazione: La proprietà idempotente di un reticolo garantisce che $A \lor A = A$ e $A \land A = A$.

	10. Risposta: La legge distributiva non è valida per tutte le coppie di elementi.
		- Spiegazione: Un reticolo non distributivo non soddisfa le proprietà distributive per tutte le combinazioni di elementi, pur mantenendo le proprietà di meet e join.

---

## Esercizi - Parte XII

??? question "Domande"

	1. Se una funzione $f: A \to B$ è suriettiva, allora quale delle seguenti affermazioni è vera?
		- [ ] Ogni elemento di $A$ ha una preimmagine in $B$.
		- [ ] Ogni elemento di $B$ ha almeno una preimmagine in $A$.
		- [ ] Ogni elemento di $B$ ha esattamente una preimmagine in $A$.
		- [ ] Ogni elemento di $A$ è in corrispondenza biunivoca con $B$.

	2. L'insieme $\mathbb{Q}$ dei numeri razionali è:
		- [ ] Infinito e numerabile.
		- [ ] Infinito e non numerabile.
		- [ ] Finito.
		- [ ] Un sottoinsieme dei numeri reali con cardinalità nulla.

	3. Se $f: \mathbb{R} \to \mathbb{R}$ è definita da $f(x) = x^2$, qual è il codominio di $f$?
		- [ ] $\mathbb{R}$
		- [ ] $\mathbb{R}^+$
		- [ ] $[0, \infty)$
		- [ ] $(-\infty, \infty)$

	4. Qual è la cardinalità dell'insieme $\{1, 2, 3, 4, 5\}$?

	5. Vero o falso: L'insieme delle parti di un insieme finito con $n$ elementi ha cardinalità $2^n$.

	6. Se $R$ è una relazione sull'insieme $A = \{1, 2, 3\}$ definita come $R = \{(1, 1), (2, 2), (3, 3), (1, 2)\}$, quale proprietà manca a $R$ affinché sia una relazione di equivalenza?
		- [ ] Riflessività
		- [ ] Simmetria
		- [ ] Transitività
		- [ ] Antisimmetria

	7. Se $A = \{1, 2, 3\}$ e $B = \{4, 5\}$, quanti elementi ha il prodotto cartesiano $A \times B$?

	8. La relazione "è maggiore di" ($>$) sui numeri naturali è:
		- [ ] Riflessiva
		- [ ] Antisimmetrica
		- [ ] Simmetrica
		- [ ] Transitiva

	9. Qual è la somma degli elementi di un insieme $S = \{2, 4, 6, 8, 10\}$?

	10. Vero o falso: Se $A \subseteq B$, allora $A \cup B = B$.

??? lightbulb "Soluzioni"

	1. Risposta: Ogni elemento di $B$ ha almeno una preimmagine in $A$.
		- Spiegazione: Una funzione è suriettiva se ogni elemento del codominio $B$ è raggiunto da almeno un elemento del dominio $A$.

	2. Risposta: Infinito e numerabile.
		- Spiegazione: L'insieme $\mathbb{Q}$ dei numeri razionali è infinito e numerabile, perché è possibile metterlo in corrispondenza biunivoca con i numeri naturali.

	3. Risposta: $[0, \infty)$
		- Spiegazione: La funzione $f(x) = x^2$ mappa ogni numero reale in un numero reale non negativo, quindi il suo codominio è $[0, \infty)$.

	4. Risposta: 5
		- Spiegazione: L'insieme $\{1, 2, 3, 4, 5\}$ ha 5 elementi, quindi la sua cardinalità è 5.

	5. Risposta: Vero
		- Spiegazione: L'insieme delle parti (insieme potenza) di un insieme con $n$ elementi ha $2^n$ sottoinsiemi, compresi l'insieme vuoto e l'insieme stesso.

	6. Risposta: Simmetria
		- Spiegazione: La relazione $R$ non è simmetrica perché, ad esempio, $(1, 2) \in R$ ma $(2, 1) \notin R$.

	7. Risposta: 6
		- Spiegazione: Il prodotto cartesiano $A \times B$ ha $|A| \cdot |B| = 3 \cdot 2 = 6$ elementi.

	8. Risposta: Transitiva
		- Spiegazione: La relazione $>$ è transitiva, perché se $a > b$ e $b > c$, allora $a > c$.

	9. Risposta: 30
		- Spiegazione: La somma degli elementi di $S = \{2, 4, 6, 8, 10\}$ è $2 + 4 + 6 + 8 + 10 = 30$.

	10. Risposta: Vero
		- Spiegazione: Se $A \subseteq B$, allora $A \cup B$ contiene tutti gli elementi di $A$ e $B$, che sono esattamente quelli di $B$.

---

## Esercizi - Parte XI

??? question "Domande"

	1. Sia $f: \mathbb{R} \to \mathbb{R}$ una funzione definita da $f(x) = 3x - 5$. Qual è l'inversa di $f(x)$?
		- [ ] $f^{-1}(x) = \frac{x + 5}{3}$
		- [ ] $f^{-1}(x) = 3x + 5$
		- [ ] $f^{-1}(x) = \frac{x - 5}{3}$
		- [ ] $f^{-1}(x) = 5 - 3x$

	2. Quale delle seguenti proprietà non è soddisfatta dalla relazione "è divisibile per" sui numeri interi?
		- [ ] Riflessività
		- [ ] Simmetria
		- [ ] Transitività
		- [ ] Antisimmetria

	3. Vero o falso: ogni classe di equivalenza in una relazione di equivalenza su un insieme non vuoto contiene almeno un elemento.

	4. Se un insieme è ben ordinato rispetto a una certa relazione d'ordine, quale delle seguenti affermazioni è vera?
		- [ ] Ogni coppia di elementi è confrontabile.
		- [ ] L’insieme contiene solo elementi distinti.
		- [ ] Ogni sottoinsieme non vuoto ha un massimo.
		- [ ] Ogni sottoinsieme non vuoto ha un minimo.

	5. L'inversa di una relazione $R$ su un insieme $A$ è definita come:
		- [ ] L’insieme delle coppie $(a, b)$ tali che $b \, R \, a$.
		- [ ] L’insieme delle coppie $(a, b)$ tali che $a \, R \, b$.
		- [ ] L’insieme delle coppie $(a, a)$ per ogni $a \in A$.
		- [ ] L’insieme di tutte le coppie possibili di elementi di $A$.

	6. Quale delle seguenti è una funzione identità su $\mathbb{R}$?
		- [ ] $f(x) = x + 1$
		- [ ] $f(x) = x^2$
		- [ ] $f(x) = x$
		- [ ] $f(x) = 0$

	7. Vero o falso: secondo gli assiomi di Peano, esiste un numero naturale che non ha lightbulbore.

	8. Se un insieme è infinito e numerabile, quale delle seguenti affermazioni è vera?
		- [ ] È un sottoinsieme proprio dell'insieme dei numeri reali.
		- [ ] Contiene solo numeri interi.
		- [ ] Ha la stessa cardinalità dell’insieme dei numeri naturali.
		- [ ] Ha una cardinalità maggiore di quella dell’insieme dei numeri naturali.

	9. Qual è la cardinalità della polvere di Cantor?
		- [ ] Numerabile
		- [ ] Non numerabile
		- [ ] Finita
		- [ ] Nulla

	10. Vero o falso: il principio di induzione completa richiede di dimostrare due basi di induzione.

??? lightbulb "Soluzioni"

	1. Risposta: $f^{-1}(x) = \frac{x + 5}{3}$
		- Spiegazione: Per trovare l'inversa, risolviamo $y = 3x - 5$ per $x$: $x = \frac{y + 5}{3}$, quindi $f^{-1}(x) = \frac{x + 5}{3}$.

	2. Risposta: Simmetria
		- Spiegazione: La relazione "è divisibile per" non è simmetrica. Ad esempio, $2 \mid 4$ ma $4 \nmid 2$.

	3. Risposta: Vero
		- Spiegazione: Ogni classe di equivalenza contiene almeno un elemento, poiché contiene tutti gli elementi equivalenti a un dato elemento secondo la relazione di equivalenza.

	4. Risposta: Ogni sottoinsieme non vuoto ha un minimo.
		- Spiegazione: Un insieme ben ordinato ha la proprietà che ogni sottoinsieme non vuoto ha un elemento minimo rispetto alla relazione d'ordine.

	5. Risposta: L’insieme delle coppie $(a, b)$ tali che $b \, R \, a$.
		- Spiegazione: L'inversa di una relazione $R$ su un insieme $A$ è l'insieme delle coppie $(a, b)$ per cui $b \, R \, a$.

	6. Risposta: $f(x) = x$
		- Spiegazione: La funzione identità su $\mathbb{R}$ è definita come $f(x) = x$, poiché ogni elemento è mappato su sé stesso.

	7. Risposta: Falso
		- Spiegazione: Secondo gli assiomi di Peano, ogni numero naturale ha un lightbulbore, quindi non esiste un numero naturale senza lightbulbore.

	8. Risposta: Ha la stessa cardinalità dell’insieme dei numeri naturali.
		- Spiegazione: Un insieme infinito e numerabile ha la stessa cardinalità dell'insieme dei numeri naturali, il che significa che i suoi elementi possono essere messi in corrispondenza biunivoca con i numeri naturali.

	9. Risposta: Non numerabile
		- Spiegazione: La polvere di Cantor è un insieme non numerabile, poiché ha la stessa cardinalità dell'insieme dei numeri reali nell'intervallo $[0, 1]$.

	10. Risposta: Falso
		- Spiegazione: Il principio di induzione completa richiede una sola base di induzione, ma può richiedere di dimostrare la validità di una proposizione fino a un certo passo per dimostrare che è vera per tutti i numeri naturali lightbulbivi.

---

## Esercizi - Parte X

??? question "Domande"

	1. Se una funzione $f: \mathbb{R} \to \mathbb{R}$ ha una funzione inversa, allora:
		- [ ] $f$ è suriettiva ma non iniettiva.
		- [ ] $f$ è iniettiva ma non suriettiva.
		- [ ] $f$ è sia iniettiva che suriettiva.
		- [ ] $f$ non è né iniettiva né suriettiva.

	2. Qual è l'identità di una funzione $f: A \to A$?
		- [ ] La funzione inversa di $f$.
		- [ ] La funzione che mappa ogni elemento di $A$ su sé stesso.
		- [ ] La funzione che mappa ogni elemento di $A$ sull'elemento neutro.
		- [ ] Una funzione suriettiva da $A$ in $A$.

	3. Vero o falso: gli assiomi di Peano sono usati per definire formalmente i numeri naturali.

	4. Se una funzione $f: \mathbb{N} \to \mathbb{N}$ è definita come $f(n) = n + 1$, qual è il valore di $f^3(2)$ (cioè $f$ applicata tre volte a 2)?

	5. Quale delle seguenti affermazioni descrive correttamente la polvere di Cantor?
		- [ ] Un insieme finito di punti.
		- [ ] Un insieme di punti densi sull'intervallo $[0, 1]$.
		- [ ] Un insieme infinito, non numerabile e con misura nulla.
		- [ ] Un sottoinsieme dei numeri razionali.

	6. L'Hotel Infinito di Hilbert è usato come esempio per illustrare:
		- [ ] La cardinalità degli insiemi finiti.
		- [ ] Il principio di induzione.
		- [ ] La nozione di infinito numerabile.
		- [ ] La definizione di insieme potenza.

	7. Vero o falso: un insieme è p-maggiorabile se ogni sottoinsieme finito ha un massimo rispetto a una relazione d'ordine.

	8. Quale dei seguenti esempi rappresenta un ordinamento parziale?
		- [ ] I numeri interi con l'ordinamento usuale $\leq$.
		- [ ] L'insieme delle parti di un insieme $S$, ordinato per inclusione.
		- [ ] L'insieme dei numeri razionali con l'ordinamento $<$.
		- [ ] L'insieme dei numeri reali con l'ordinamento $\leq$.

	9. Vero o falso: Se un insieme è ben ordinato, allora ogni sottoinsieme ha un elemento minimo.

	10. In una relazione di equivalenza, una classe di equivalenza:
		- [ ] Contiene sempre un solo elemento.
		- [ ] Contiene elementi tutti equivalenti tra loro.
		- [ ] È sempre un sottoinsieme proprio dell’insieme originale.
		- [ ] È l’insieme delle immagini di una funzione suriettiva.

??? lightbulb "Soluzioni"

	1. Risposta: $f$ è sia iniettiva che suriettiva.
		- Spiegazione: Perché una funzione abbia un'inversa, deve essere biiettiva, cioè sia iniettiva (ogni elemento dell'immagine ha una preimmagine unica) che suriettiva (ogni elemento del codominio è raggiunto).

	2. Risposta: La funzione che mappa ogni elemento di $A$ su sé stesso.
		- Spiegazione: L'identità su $A$ è la funzione che manda ogni elemento di $A$ su sé stesso, denotata di solito come $\text{id}_A(x) = x$ per ogni $x \in A$.

	3. Risposta: Vero
		- Spiegazione: Gli assiomi di Peano sono un sistema di assiomi che definisce formalmente le proprietà dei numeri naturali.

	4. Risposta: 5
		- Spiegazione: $f(n) = n + 1$, quindi $f^3(2) = f(f(f(2))) = f(f(3)) = f(4) = 5$.

	5. Risposta: Un insieme infinito, non numerabile e con misura nulla.
		- Spiegazione: La polvere di Cantor è un esempio di insieme infinito con misura di Lebesgue nulla e non è numerabile, ma ha struttura frattale.

	6. Risposta: La nozione di infinito numerabile.
		- Spiegazione: L'Hotel Infinito di Hilbert illustra il concetto di infinito numerabile, dimostrando che è possibile "ospitare" infiniti nuovi ospiti in un hotel già pieno se le stanze sono numerabili.

	7. Risposta: Vero
		- Spiegazione: Un insieme è p-maggiorabile se ogni suo sottoinsieme finito ha un massimo rispetto a una data relazione d'ordine.

	8. Risposta: L'insieme delle parti di un insieme $S$, ordinato per inclusione.
		- Spiegazione: L'ordinamento per inclusione è un esempio di ordinamento parziale, poiché non tutti i sottoinsiemi di $S$ sono confrontabili.

	9. Risposta: Vero
		- Spiegazione: In un insieme ben ordinato, ogni sottoinsieme ha un elemento minimo per definizione.

	10. Risposta: Contiene elementi tutti equivalenti tra loro.
		- Spiegazione: Una classe di equivalenza è costituita dagli elementi che sono tutti in relazione di equivalenza tra loro, secondo la relazione definita.

---

## Esercizi - Parte IX

??? question "Domande"

	1. Dati due insiemi $A$ e $B$ tali che $A \subset B$ e $A \neq B$, quale affermazione è vera?
		- [ ] $A$ è un sottoinsieme proprio di $B$
		- [ ] $B$ è un sottoinsieme proprio di $A$
		- [ ] $A = B$
		- [ ] $A \cap B = \emptyset$

	2. Se $x \notin A$ e $x \notin B$, quale delle seguenti affermazioni è vera?
		- [ ] $x \in A \cup B$
		- [ ] $x \notin A \cap B$
		- [ ] $x \in A \cap B$
		- [ ] $x \in A$

	3. L'assioma di estensione afferma che:
		- [ ] Due insiemi sono uguali se hanno la stessa cardinalità.
		- [ ] Due insiemi sono uguali se contengono esattamente gli stessi elementi.
		- [ ] Un insieme contiene solo elementi distinti.
		- [ ] Ogni insieme ha un sottoinsieme proprio.

	4. Qual è la cardinalità dell'insieme potenza di un insieme con 5 elementi?

	5. Se $A = \{1, 2\}$ e $B = \{3, 4\}$, qual è il numero di elementi nel prodotto cartesiano $B \times A$?
		- [ ] 2
		- [ ] 4
		- [ ] 6
		- [ ] 8

	6. La relazione di divisibilità sui numeri interi positivi è:
		- [ ] Riflessiva, antisimmetrica e transitiva
		- [ ] Riflessiva, simmetrica e transitiva
		- [ ] Simmetrica, antisimmetrica e riflessiva
		- [ ] Solo antisimmetrica e transitiva

	7. Qual è il complemento dell'insieme dei numeri pari rispetto all'insieme dei numeri interi?
		- [ ] L'insieme dei numeri dispari
		- [ ] L'insieme dei numeri razionali
		- [ ] L'insieme vuoto
		- [ ] L'insieme dei numeri naturali

	8. Una relazione d'equivalenza su un insieme:
		- [ ] Partiziona l'insieme in classi di equivalenza.
		- [ ] Partiziona l'insieme in coppie ordinate.
		- [ ] Partiziona l'insieme in sottoinsiemi propri.
		- [ ] Non è riflessiva.

	9. Una funzione $f: \mathbb{N} \to \mathbb{N}$ è iniettiva se:
		- [ ] Immagini diverse hanno preimmagini diverse.
		- [ ] Immagini uguali hanno preimmagini diverse.
		- [ ] Ogni numero naturale è mappato su sé stesso.
		- [ ] Ogni numero naturale è mappato su un numero diverso.

	10. Vero o falso: Il principio di induzione può essere usato per dimostrare una proprietà valida per ogni numero reale.

??? lightbulb "Soluzioni"

	1. $A$ è un sottoinsieme proprio di $B$
		- Spiegazione: Se $A \subseteq B$ e $A \neq B$, allora $A$ è contenuto in $B$ ma non uguale a $B$, quindi è un sottoinsieme proprio di $B$.

	2. $x \notin A \cap B$
		- Spiegazione: Se $x \notin A$ e $x \notin B$, allora $x$ non può appartenere all'intersezione $A \cap B$, che contiene solo gli elementi comuni a $A$ e $B$.

	3. Due insiemi sono uguali se contengono esattamente gli stessi elementi.
		- Spiegazione: L'assioma di estensione stabilisce che due insiemi sono uguali se contengono gli stessi elementi, indipendentemente dall'ordine.

	4. 32
		- Spiegazione: L'insieme delle parti di un insieme con $n$ elementi ha $2^n$ sottoinsiemi. Con 5 elementi, la cardinalità dell'insieme potenza è $2^5 = 32$.

	5. Risposta: 4
		- Spiegazione: Il prodotto cartesiano $B \times A$ ha $|B| \times |A| = 2 \times 2 = 4$ elementi.

	6. Risposta: Riflessiva, antisimmetrica e transitiva
		- Spiegazione: La divisibilità è riflessiva (ogni numero divide sé stesso), antisimmetrica (se $a \mid b$ e $b \mid a$, allora $a = b$) e transitiva (se $a \mid b$ e $b \mid c$, allora $a \mid c$).

	7. Risposta: L'insieme dei numeri dispari
		- Spiegazione: Il complemento dell'insieme dei numeri pari rispetto ai numeri interi è l'insieme dei numeri dispari, poiché ogni numero intero è o pari o dispari.

	8. Risposta: Partiziona l'insieme in classi di equivalenza.
		- Spiegazione: Una relazione d'equivalenza divide un insieme in classi di equivalenza, che sono sottoinsiemi disgiunti e coprono l'intero insieme.

	9. Risposta: Immagini diverse hanno preimmagini diverse.
		- Spiegazione: Una funzione è iniettiva se ogni immagine ha una preimmagine unica. Ciò implica che immagini diverse non possono avere la stessa preimmagine.

	10. Risposta: Falso
		- Spiegazione: Il principio di induzione matematica si applica ai numeri naturali (o interi positivi), non ai numeri reali in generale.

---

## Esercizi - Parte VIII

??? question "Domande"

	1. Secondo l'assioma di estensione, quale delle seguenti affermazioni è vera per due insiemi $A$ e $B$ se $A = B$?
		- [ ] Hanno lo stesso numero di elementi.
		- [ ] Sono entrambi infiniti.
		- [ ] Contengono esattamente gli stessi elementi.
		- [ ] Sono sottoinsiemi l'uno dell'altro.

	2. Se $x \in A$ e $A \subseteq B$, quale delle seguenti affermazioni è vera?
		- [ ] $x \in B$
		- [ ] $x \notin B$
		- [ ] $x \in A \cap B$
		- [ ] $x \in A \cup B$

	3. Dato un insieme $X$ e una proprietà $P(x)$, l'assioma di specificazione consente di:
		- [ ] Costruire un insieme che contiene solo gli elementi di $X$ che soddisfano $P(x)$.
		- [ ] Costruire un insieme con qualsiasi elemento che soddisfa $P(x)$, anche se non è in $X$.
		- [ ] Costruire un insieme che contiene tutti gli elementi di $X$ e $P(x)$.
		- [ ] Costruire un insieme che esclude gli elementi di $X$ che soddisfano $P(x)$.

	4. Se $A = \{1, 2, 3, 4\}$ e $B = \{3, 4, 5, 6\}$, qual è $A \setminus B$?
		- [ ] \(\{1, 2\}\)
		- [ ] \(\{3, 4\}\)
		- [ ] \(\{5, 6\}\)
		- [ ] \(\{1, 2, 5, 6\}\)

	5. Se $A = \{1, 2, 3\}$ e $B = \{4, 5\}$, qual è il numero di elementi nell'insieme potenza di $A \times B$?

	6. La relazione di uguaglianza su un insieme $A$ è:
		- [ ] Riflessiva e simmetrica, ma non transitiva.
		- [ ] Simmetrica e transitiva, ma non riflessiva.
		- [ ] Riflessiva, simmetrica e transitiva.
		- [ ] Antisimmetrica e transitiva.

	7. Se una relazione $R$ è una relazione d'ordine parziale su un insieme $A$, allora:
		- [ ] È sempre riflessiva, antisimmetrica e transitiva.
		- [ ] È sempre riflessiva, simmetrica e transitiva.
		- [ ] È sempre antisimmetrica e simmetrica.
		- [ ] È sempre simmetrica, riflessiva e antisimmetrica.

	8. La classe di equivalenza di un elemento $a$ rispetto a una relazione di equivalenza $R$ su un insieme $A$:
		- [ ] È un insieme che contiene solo $a$.
		- [ ] È l'insieme di tutti gli elementi in $A$ in relazione con $a$ tramite $R$.
		- [ ] Contiene tutti gli elementi che non sono in $A$.
		- [ ] È l'insieme di tutti gli elementi in $A$ non in relazione con $a$ tramite $R$.

	9. Una funzione $f: A \to B$ è biiettiva se:
		- [ ] È iniettiva ma non suriettiva.
		- [ ] È suriettiva ma non iniettiva.
		- [ ] È sia iniettiva che suriettiva.
		- [ ] Non è né iniettiva né suriettiva.

	10. Vero o falso: Il principio di induzione matematica è usato per dimostrare proposizioni valide per tutti i numeri interi positivi.

??? lightbulb "Soluzioni"

	1. Risposta: Contengono esattamente gli stessi elementi.
		- Spiegazione: L'assioma di estensione afferma che due insiemi sono uguali se e solo se contengono gli stessi elementi, indipendentemente dall'ordine o da come sono rappresentati.

	2. Risposta: $x \in B$
		- Spiegazione: Se $x \in A$ e $A \subseteq B$, allora $x$ deve appartenere anche a $B$ perché tutti gli elementi di $A$ sono anche elementi di $B$.

	3. Risposta: Costruire un insieme che contiene solo gli elementi di $X$ che soddisfano $P(x)$.
		- Spiegazione: L'assioma di specificazione permette di creare un sottoinsieme di $X$ contenente solo gli elementi che soddisfano la proprietà specifica $P(x)$.

	4. Risposta: \(\{1, 2\}\)
		- Spiegazione: L'insieme differenza $A \setminus B$ contiene gli elementi di $A$ che non sono in $B$, quindi $A \setminus B = \{1, 2\}$.

	5. Risposta: 32
		- Spiegazione: $A \times B$ ha $3 \times 2 = 6$ elementi. L'insieme delle parti di un insieme con $n$ elementi ha $2^n$ sottoinsiemi, quindi l'insieme potenza di $A \times B$ ha $2^6 = 64$ elementi.

	6. Risposta: Riflessiva, simmetrica e transitiva.
		- Spiegazione: La relazione di uguaglianza è una relazione di equivalenza che soddisfa tutte e tre queste proprietà.

	7. Risposta: È sempre riflessiva, antisimmetrica e transitiva.
		- Spiegazione: Una relazione d'ordine parziale deve soddisfare la riflessività, l'antisimmetria e la transitività, ma non necessariamente la simmetria.

	8. Risposta: È l'insieme di tutti gli elementi in $A$ in relazione con $a$ tramite $R$.
		- Spiegazione: La classe di equivalenza di un elemento $a$ contiene tutti gli elementi che sono in relazione con $a$ secondo $R$.

	9. Risposta: È sia iniettiva che suriettiva.
		- Spiegazione: Una funzione è biiettiva se è sia iniettiva (ogni elemento dell'immagine ha un'unica preimmagine) che suriettiva (ogni elemento del codominio è raggiunto).

	10. Risposta: Vero
		- Spiegazione: Il principio di induzione matematica è utilizzato per dimostrare che una proposizione è vera per tutti i numeri interi positivi.

---

## Esercizi - Parte VII

??? question "Domande"

	1. Secondo l'assioma di estensione, due insiemi $A$ e $B$ sono uguali se:
		- [ ] Contengono esattamente gli stessi elementi.
		- [ ] Hanno la stessa cardinalità.
		- [ ] Sono sottoinsiemi l'uno dell'altro.
		- [ ] Hanno lo stesso complemento.

	2. Se $x \notin A$, cosa possiamo concludere?
		- [ ] $x$ è un elemento di $A$.
		- [ ] $x$ non appartiene ad alcun sottoinsieme di $A$.
		- [ ] $x$ è nell'insieme complemento di $A$.
		- [ ] $x$ appartiene all'universo.

	3. Sia $A = \{1, 2, 3\}$ e $B = \{2, 3\}$. Quale delle seguenti affermazioni è corretta?
		- [ ] $A \subseteq B$
		- [ ] $B \subseteq A$
		- [ ] $A = B$
		- [ ] $A \cap B = \emptyset$

	4. Vero o falso: l'assioma di specificazione afferma che, dato un insieme e una proprietà, esiste un sottoinsieme costituito solo dagli elementi che soddisfano tale proprietà.

	5. Qual è la cardinalità dell'insieme potenza di un insieme con 4 elementi?

	6. Se $A$ e $B$ sono insiemi con $A \cap B = \emptyset$, quale delle seguenti affermazioni è vera?
		- [ ] $A \cup B = \emptyset$
		- [ ] $A \cap B = A$
		- [ ] $A \cap B = B$
		- [ ] $A \cap B$ è l'insieme vuoto.

	7. Siano dati due insiemi $A$ e $B$ tali che $A \subseteq B$ e $B \subseteq A$. Quale delle seguenti affermazioni è corretta?
		- [ ] $A$ e $B$ hanno lo stesso numero di elementi.
		- [ ] $A$ e $B$ sono lo stesso insieme.
		- [ ] $B$ ha un numero maggiore di elementi rispetto ad $A$.
		- [ ] $A$ è un sottoinsieme proprio di $B$.

	8. Qual è il numero di elementi nel prodotto cartesiano $A \times B$ se $|A| = 3$ e $|B| = 5$?

	9. Se una relazione $R$ su un insieme $A$ è antisimmetrica, quale delle seguenti affermazioni è vera?
		- [ ] Se $a \, R \, b$ e $b \, R \, a$, allora $a = b$.
		- [ ] Se $a \, R \, b$, allora $b \, R \, a$.
		- [ ] Se $a = b$, allora $a \, R \, b$.
		- [ ] Se $a \neq b$, allora $a \, R \, b$.

	10. Vero o falso: Un ordine totale su un insieme richiede che ogni coppia di elementi sia confrontabile.

??? lightbulb "Soluzioni"

	1. Contengono esattamente gli stessi elementi.
		- Spiegazione: Secondo l'assioma di estensione, due insiemi sono uguali se e solo se contengono gli stessi elementi, indipendentemente da come sono definiti o rappresentati.

	2. $x$ è nell'insieme complemento di $A$.
		- Spiegazione: Se $x \notin A$, significa che $x$ appartiene all'insieme complementare di $A$, cioè all'insieme di tutti gli elementi che non sono in $A$.

	3. $B \subseteq A$
		- Spiegazione: Tutti gli elementi di $B$ (cioè 2 e 3) sono contenuti in $A$, ma $A$ ha anche altri elementi, quindi $B \subseteq A$.

	4. Vero
		- Spiegazione: L'assioma di specificazione (o di separazione) afferma che, dato un insieme e una proprietà, è possibile costruire un sottoinsieme costituito solo dagli elementi che soddisfano quella proprietà.

	5. 16
		- Spiegazione: L'insieme delle parti di un insieme con $n$ elementi ha $2^n$ sottoinsiemi. Per un insieme con 4 elementi, la cardinalità è $2^4 = 16$.

	6. $A \cap B$ è l'insieme vuoto.
		- Spiegazione: Se $A$ e $B$ sono disgiunti, cioè $A \cap B = \emptyset$, significa che non hanno elementi in comune, quindi l'intersezione è l'insieme vuoto.

	7. $A$ e $B$ sono lo stesso insieme.
		- Spiegazione: Se $A \subset B$ e $B \subseteq A$, significa che ogni elemento di $A$ è in $B$ e viceversa, quindi $A$ e $B$ contengono esattamente gli stessi elementi.

	8. 15
		- Spiegazione: Il prodotto cartesiano $A \times B$ ha un numero di elementi pari al prodotto delle cardinalità di $A$ e $B$. Con $|A| = 3$ e $|B| = 5$, ci sono $3 \times 5 = 15$ elementi.

	9. Se $a \, R \, b$ e $b \, R \, a$, allora $a = b$.
		- Spiegazione: Una relazione è antisimmetrica se, per qualsiasi coppia $(a, b)$, il fatto che $a \, R \, b$ e $b \, R \, a$ implica necessariamente $a = b$.

	10. Vero
		- Spiegazione: Un ordine totale richiede che ogni coppia di elementi dell'insieme possa essere confrontata. Questo significa che, dati due elementi qualsiasi $a$ e $b$, o $a \leq b$ oppure $b \leq a$.


---

## Esercizi - Parte VI

??? question "Domande"

	1. Sia $A = \{1, 2, 3\}$ e $B = \{2, 3, 4\}$. Qual è $A \cap B$?
		- [ ] $\{1, 4\}$
		- [ ] $\{2, 3\}$
		- [ ] $\{1, 2, 3, 4\}$
		- [ ] $\emptyset$

	2. Se $A \subseteq B$, è sempre vero che $A \cap B = A$?

	3. Vero o falso: il complemento di un insieme $A$ rispetto all'universo $U$ contiene tutti gli elementi che non sono in $A$.

	4. Considerando i numeri interi $\mathbb{Z}$, la relazione di divisibilità ($a \mid b$ se $b$ è divisibile per $a$) è una relazione di ordine parziale?
		- [ ] Sì, perché è riflessiva, antisimmetrica e transitiva.
		- [ ] No, perché è riflessiva e simmetrica ma non transitiva.
		- [ ] No, perché non è riflessiva.
		- [ ] Sì, perché è simmetrica e transitiva.

	5. Se $A = \{1, 2\}$ e $B = \{3, 4\}$, qual è il numero di elementi del prodotto cartesiano $A \times B$?
		- [ ] 2
		- [ ] 4
		- [ ] 6
		- [ ] 8

	6. Siano $R = \{(1, 1), (2, 2), (3, 3), (1, 2), (2, 1)\}$ una relazione sull'insieme $\{1, 2, 3\}$. La relazione $R$ è simmetrica?
		- [ ] Sì
		- [ ] No

	7. Se una relazione $R$ è riflessiva su un insieme $A$, quale delle seguenti affermazioni è vera?
		- [ ] Ogni elemento di $A$ è in relazione con sé stesso.
		- [ ] Ogni elemento di $A$ è in relazione con un elemento diverso.
		- [ ] Nessun elemento di $A$ è in

	   8. Una funzione $f: A \to B$ è suriettiva se:
		- [ ] Ogni elemento di $A$ è mappato su un unico elemento di $B$.
		- [ ] Ogni elemento di $B$ ha almeno una preimmagine in $A$.
		- [ ] Ogni elemento di $A$ è mappato su sé stesso.
	   	- [ ] Ogni elemento di $A$ è mappato su un elemento diverso di $B$.

	9. Qual è la cardinalità dell'insieme delle parti (insieme potenza) di un insieme $A$ con 3 elementi?

	10. Vero o falso: una relazione d'equivalenza su un insieme induce una partizione dell'insieme stesso in classi di equivalenza.

??? lightbulb "Soluzioni"

	1. Risposta: $\{2, 3\}$
		- Spiegazione: L'intersezione di $A$ e $B$ contiene solo gli elementi comuni ai due insiemi, quindi $\{2, 3\}$.

	2. Risposta: Sì
		- Spiegazione: Se $A \subseteq B$, tutti gli elementi di $A$ sono anche in $B$, quindi l'intersezione $A \cap B$ contiene esattamente gli elementi di $A$.

	3. Risposta: Vero
		- Spiegazione: Per definizione, il complemento di un insieme $A$ rispetto all'universo $U$ include tutti gli elementi di $U$ che non appartengono a $A$.

	4. Risposta: Sì, perché è riflessiva, antisimmetrica e transitiva.
		- Spiegazione: La relazione di divisibilità sui numeri interi è un ordine parziale poiché è riflessiva (ogni numero è divisibile per sé stesso), antisimmetrica (se $a \mid b$ e $b \mid a$, allora $a = b$) e transitiva (se $a \mid b$ e $b \mid c$, allora $a \mid c$).

	5. Risposta: 4
		- Spiegazione: Il prodotto cartesiano $A \times B$ è l'insieme delle coppie ordinate formate da un elemento di $A$ e uno di $B$. Con 2 elementi in $A$ e 2 in $B$, il prodotto contiene $2 \times 2 = 4$ elementi.

	6. Risposta: Sì
		- Spiegazione: Una relazione è simmetrica se per ogni coppia $(a, b) \in R$ anche $(b, a) \in R$. Dato che ogni coppia in $R$ soddisfa questa condizione, $R$ è simmetrica.

	7. Risposta: Ogni elemento di $A$ è in relazione con sé stesso.
		- Spiegazione: Una relazione è riflessiva se ogni elemento dell'insieme è in relazione con sé stesso, cioè $(a, a) \in R$ per ogni $a \in A$.

	8. Risposta: Ogni elemento di $B$ ha almeno una preimmagine in $A$.
		- Spiegazione: Una funzione è suriettiva se ogni elemento del codominio $B$ è associato ad almeno un elemento del dominio $A$.

	9. Risposta: 8
		- Spiegazione: L'insieme delle parti (o insieme potenza) di un insieme con $n$ elementi ha $2^n$ sottoinsiemi. Con 3 elementi, la cardinalità è $2^3 = 8$.

	10. Risposta: Vero
   		- Spiegazione: Una relazione di equivalenza su un insieme crea delle classi di equivalenza, che costituiscono una partizione dell'insieme, ossia lo suddividono in sottoinsiemi disgiunti.


---

## Esercizi - Parte V

??? question "Domande"

	1. La differenza simmetrica tra due insiemi $A$ e $B$ contiene elementi:
	    - A: Solo in $A$
	    - B: Solo in $B$
	    - C: In $A$ o $B$ ma non in entrambi

	2. Se una relazione $R$ su un insieme è riflessiva e simmetrica, è necessariamente una relazione di equivalenza?

	3. Quale delle seguenti condizioni deve soddisfare un insieme parzialmente ordinato?
	    - A: Riflessività, antisimmetria e transitività
	    - B: Simmetria, antisimmetria e transitività
	    - C: Riflessività, simmetria e transitività

	4. La relazione di appartenenza $\in$ è transitiva?

	5. Se una funzione ha un dominio finito con $n$ elementi ed è iniettiva, qual è il numero minimo di elementi necessari nel codominio?
	    - A: $n$
	    - B: $n-1$
	    - C: $2n$

	6. Se $A \cap B = B$, quale delle seguenti affermazioni è vera?
	    - A: $A \subseteq B$
	    - B: $B \subseteq A$
	    - C: $A = B$

	7. Se una funzione non è iniettiva, può essere suriettiva?

	8. Due insiemi con la stessa cardinalità hanno sempre la stessa potenza?

	9. La composizione di due funzioni biiettive è:
	    - A: Iniettiva
	    - B: Suriettiva
	    - C: Biiettiva

	10. Se $A \subset B$, allora la cardinalità di $A$ è strettamente minore della cardinalità di $B$?

??? lightbulb "Soluzioni"

	1. **C.** La differenza simmetrica tra $A$ e $B$ contiene gli elementi che sono in $A$ o in $B$, ma non in entrambi.
	2. **No.** La riflessività e la simmetria non sono sufficienti; è necessaria anche la transitività per avere una relazione di equivalenza.
	3. **A.** Un insieme parzialmente ordinato deve soddisfare riflessività, antisimmetria e transitività.
	4. **No.** La relazione di appartenenza non è transitiva; ad esempio, se $a \in A$ e $A \in B$, non segue che $a \in B$.
	5. **A.** Per garantire l'iniettività, ci devono essere almeno $n$ elementi nel codominio.
	6. **B.** Se $A \cap B = B$, allora $B \subseteq A$ poiché tutti gli elementi di $B$ sono in $A$.
	7. **Sì.** Una funzione può essere suriettiva anche senza essere iniettiva, poiché potrebbe coprire tutto il codominio ma avere elementi ripetuti.
	8. **Sì.** Due insiemi con la stessa cardinalità hanno la stessa cardinalità dell'insieme potenza, quindi la stessa potenza.
	9. **C.** La composizione di due funzioni biiettive è anch'essa biiettiva.
	10. **Sì.** Se $A \subset B$ (e quindi $A \neq B$), allora la cardinalità di $A$ è strettamente minore di quella di $B$.

---

## Esercizi - Parte IV

??? question "Domande"

	1. Se $A \cap B = \emptyset$, quali dei seguenti termini descrivono $A$ e $B$?
	    - A: Sottoinsiemi
	    - B: Insiemi complementari
	    - C: Insiemi disgiunti

	2. Una funzione che associa ad ogni elemento del dominio un elemento unico e distinto del codominio è:
	    - A: Iniettiva
	    - B: Suriettiva
	    - C: Biiettiva

	3. Se una funzione è biiettiva, ammette un'inversa?

	4. La relazione di equivalenza può essere interpretata come una partizione dell'insieme?

	5. Quale delle seguenti operazioni insiemistiche è associativa?
	    - A: Intersezione
	    - B: Differenza
	    - C: Prodotto cartesiano

	6. Se $A \subseteq B$ e $B \subseteq C$, allora è vero che $A \subseteq C$?

	7. Un ordinamento totale è sempre un ordinamento parziale?

	8. Quale di queste proprietà è necessaria affinché una relazione sia di equivalenza?
	    - A: Riflessività
	    - B: Antisimmetria
	    - C: Asimmetria

	9. In un insieme finito con $n$ elementi, quante possibili partizioni ci sono?
	    - A: $2^n$
	    - B: Numero di Bell per $n$
	    - C: $n!$

	10. Due classi di equivalenza rispetto a una relazione di equivalenza su $A$:
	    - A: Sono sempre uguali
	    - B: Sono sempre disgiunte
	    - C: Possono sovrapporsi

??? lightbulb "Soluzioni"

	1. **C.** Se $A \cap B = \emptyset$, allora $A$ e $B$ sono insiemi disgiunti, cioè non hanno elementi in comune.
	2. **C.** Una funzione che è sia iniettiva che suriettiva è detta biiettiva, il che implica che ogni elemento del dominio ha un'immagine distinta nel codominio.
	3. **Sì.** Se una funzione è biiettiva, esiste una funzione inversa che associa ogni elemento del codominio al suo preimmagine.
	4. **Sì.** Una relazione di equivalenza partiziona un insieme in classi di equivalenza disgiunte, ciascuna delle quali rappresenta un gruppo di elementi equivalenti.
	5. **A.** L'operazione di intersezione è associativa: $(A \cap B) \cap C = A \cap (B \cap C)$.
	6. **Sì.** Se $A \subseteq B$ e $B \subseteq C$, allora $A \subseteq C$ per la proprietà transitiva dell'inclusione.
	7. **Sì.** Un ordinamento totale è anche un ordinamento parziale, poiché soddisfa le proprietà richieste da quest'ultimo e in più impone un confronto tra tutti gli elementi.
	8. **A.** Per essere una relazione di equivalenza, deve essere riflessiva, simmetrica e transitiva.
	9. **B.** Il numero di possibili partizioni di un insieme finito di $n$ elementi è dato dal Numero di Bell per $n$.
	10. **B.** Due classi di equivalenza rispetto a una relazione di equivalenza su $A$ sono sempre disgiunte.

---

## Esercizi - Parte III

??? question "Domande"

	1. Se un insieme $A$ ha $n$ elementi, quanti elementi ha l'insieme potenza di $A$?
	    1. A: $2n$
	    2. B: $n^2$
	    3. C: $2^n$

	2. Se $A \subseteq B$ e $B \subseteq A$, allora $A$ è uguale a $B$?

	3. Quale delle seguenti operazioni insiemistiche risulta sempre commutativa?
	    1. A: Intersezione
	    2. B: Differenza
	    3. C: Prodotto cartesiano

	4. Un insieme vuoto ha cardinalità zero?

	5. Qual è il complemento dell'unione di due insiemi?
	    1. A: Unione dei complementi
	    2. B: Intersezione dei complementi
	    3. C: Differenza tra i complementi

	6. Siano dati gli insiemi $A = \{1, 2\}$ e $B = \{x, y\}$. Qual è il numero totale di elementi nel prodotto cartesiano $A \times B$?

		1. 2
		2. 4
		3. 6
		4. 8

	7. La relazione di ordine stretto $<$ è transitiva?

	8. Se una funzione è suriettiva, il suo codominio coincide con il suo insieme immagine?

	9. Due insiemi sono detti disgiunti se:
	    1. A: Uno è sottoinsieme dell'altro
	    2. B: Non hanno elementi in comune
	    3. C: Hanno esattamente un elemento in comune

	10. In una relazione antisimmetrica, se $a R b$ e $b R a$, cosa possiamo concludere su $a$ e $b$?
	    1. A: $a$ e $b$ sono uguali
	    2. B: $a$ e $b$ sono diversi
	    3. C: Nulla, dipende dalla relazione

??? lightbulb "Soluzioni"

	1. **C.** L'insieme potenza di $A$ ha $2^n$ elementi, dove $n$ è la cardinalità di $A$.
	2. **Sì.** Se $A \subseteq B$ e $B \subseteq A$, per definizione $A$ e $B$ devono essere uguali.
	3. **A.** L'intersezione è commutativa: $A \cap B = B \cap A$.
	4. **Sì.** L'insieme vuoto non contiene elementi, quindi la sua cardinalità è zero.
	5. **B.** Il complemento dell'unione di due insiemi è l'intersezione dei complementi, secondo la legge di De Morgan.
	6. **4.** Il prodotto cartesiano $A \times B$ è l'insieme di tutte le coppie ordinate $(a, b)$ con $a \in A$ e $b \in B$. Poiché $A$ ha 2 elementi e $B$ ha 2 elementi, il numero totale di coppie è $2 \times 2 = 4$. Quindi, $A \times B = \{ (1, x), (1, y), (2, x), (2, y) \}$, che contiene 4 elementi.

	7. **Sì.** La relazione di ordine stretto $<$ è transitiva: se $a < b$ e $b < c$, allora $a < c$.
	8. **Sì.** In una funzione suriettiva, ogni elemento del codominio è coperto dall'immagine, quindi codominio e immagine coincidono.
	9. **B.** Due insiemi sono detti disgiunti se non hanno elementi in comune.
	10. **A.** In una relazione antisimmetrica, se $a R b$ e $b R a$, allora $a = b$.

---

## Esercizi - Parte II

??? question "Domande"

	1. Un insieme può essere sottoinsieme di sé stesso?
	2. Quale degli insiemi seguenti ha cardinalità maggiore?
		1. $A: \{1, 2, 3, 4\}$
		2. $B: \{2, 4, 6, 8, 10\}$
		3. $C: \{3, 5, 7\}$
	3. Il prodotto cartesiano tra due insiemi finiti è sempre finito?
	4. Se una funzione è iniettiva e suriettiva, è anche biiettiva?
	5. Quale delle seguenti è una proprietà riflessiva?
		1. $\leq$
		2. $<$
		3. $\neq$
	6. La relazione di appartenenza $\in$ è simmetrica?
	7. Qual è il complemento dell'intersezione di due insiemi?
		1. Unione dei complementi
		2. Intersezione dei complementi
		3. Differenza tra i complementi
	8. Se $A$ è un insieme con $|A| = 5$, qual è la cardinalità dell'insieme potenza di $A$?
	9. La relazione di equivalenza su un insieme lo divide in classi disgiunte?
	10. Una funzione identità può essere suriettiva?

??? lightbulb "Soluzioni"

	1. **Sì** — Ogni insieme è sottoinsieme di sé stesso per definizione.
	2. **B** — L'insieme B ha 5 elementi, che è la cardinalità maggiore rispetto agli altri.
	3. **Sì** — Il prodotto cartesiano tra insiemi finiti ha cardinalità data dal prodotto delle cardinalità dei singoli insiemi.
	4. **Sì** — Una funzione iniettiva e suriettiva soddisfa la definizione di funzione biiettiva.
	5. **A** — La relazione $\leq$ è riflessiva perché ogni elemento è minore o uguale a sé stesso.
	6. **No** — La relazione di appartenenza non è simmetrica, perché se $a \in A$, non segue che $A \in a$.
	7. **A** — Il complemento dell'intersezione di due insiemi è l'unione dei complementi.
	8. **32** — L'insieme potenza di $A$ ha $2^5 = 32$ elementi.
	9. **Sì** — Una relazione di equivalenza crea classi di equivalenza che partizionano l'insieme in modo disgiunto.
	10. **Sì** — La funzione identità associa ogni elemento a sé stesso, coprendo tutto l'insieme.

---

## Esercizi - Parte I

??? question "Domande"

	1. Data l'uguaglianza $A = \{x \in \mathbb{N} : x < 5\}$, si tratta di un'estensione o di una specificazione di insieme?
		1. Estensione  
		2. Specificazione

	2. L'intersezione di due insiemi disgiunti è l'insieme vuoto.
		1. Vero
		2. Falso

	3. Se $A = \{1, 2, 3\}$ e $B = \{3, 4, 5\}$, qual è $A \cap B$?

	4. Esiste una relazione d'ordine totale tra gli elementi di $\{a, b, c\}$ in cui $a < b < c$?

	5. Considera la funzione $f: \mathbb{R} \to \mathbb{R}$ definita da $f(x) = x^2$. È iniettiva?

	6. Se $R$ è una relazione d'ordine parziale su un insieme $X$, quale delle seguenti proprietà deve soddisfare?
		1. Riflessività, simmetria e transitività
		2. Antisimmetria, riflessività e transitività
		3. Antisimmetria e transitività

	7. Data l'uguaglianza $\{x \in \mathbb{Z} : x \text{ è pari}\} \cap \{x \in \mathbb{Z} : x \text{ è dispari}\}$, qual è il risultato?
		1. L'insieme dei numeri pari
		2. L'insieme dei numeri dispari
		3. L'insieme vuoto

	8. Se $A = \{1, 2, 3\}$, qual è il numero totale di sottoinsiemi di $A$?

	9. Una funzione suriettiva è anche iniettiva.
		1. Vero
		2. Falso

	10. Dati due insiemi $A$ e $B$ tali che $A \subseteq B$, l'unione di $A$ e $B$ coincide con $B$?

??? lightbulb "Soluzioni"

	1. **B** — La definizione tramite proprietà come $x < 5$ identifica un insieme senza elencarne direttamente gli elementi, perciò è una specificazione.

	2. **Vero** — Due insiemi disgiunti non hanno elementi in comune, quindi la loro intersezione è l'insieme vuoto.	

	3. **$A \cap B = \{3\}$** — L'elemento comune tra $A$ e $B$ è solo il numero 3, quindi l'intersezione è $\{3\}$.

	4. **Sì** — Una relazione d'ordine totale richiede che gli elementi siano ordinati in una sequenza lineare come $a < b < c$, quindi è possibile definirla su $\{a, b, c\}$.

	5. **No** — La funzione $f(x) = x^2$ non è iniettiva perché due valori diversi, come $x = 2$ e $x = -2$, possono avere lo stesso valore $f(x) = 4$.

	6. **B** — Una relazione d'ordine parziale deve essere riflessiva (ogni elemento è in relazione con sé stesso), transitiva (se $a \leq b$ e $b \leq c$, allora $a \leq c$) e antisimmetrica (se $a \leq b$ e $b \leq a$, allora $a = b$).

	7. **C** — Non ci sono numeri interi che siano sia pari che dispari, quindi l'intersezione dei due insiemi è vuota.

	8. **8** — Un insieme di $n$ elementi ha $2^n$ sottoinsiemi. Per $A = \{1, 2, 3\}$, ci sono $2^3 = 8$ sottoinsiemi.

	9. **Falso** — Una funzione suriettiva (che copre tutto il codominio) non è necessariamente iniettiva (cioè ogni elemento dell'immagine è unico); esistono funzioni suriettive che non sono iniettive.

	10. **Sì** — Se $A \subseteq B$, ogni elemento di $A$ è già in $B$, quindi $A \cup B = B$.

---

## Esercizi del Libro

??? question "Domande"

	1. Dato $M = \{1, 2, 3\}$, determinare se le seguenti proposizioni sono corrette e perché.
		- (a) $1 \in M$
		- (b) $1 \subseteq M$
		- (c) $\{1\} \in M$
		- (d) $\{1\} \subseteq M$
	2. Quali dei seguenti insiemi sono uguali?
		- $\{x: x \text{ è una lettera della parola "reattore"}\}$;
		- l'insieme delle lettere che compaiono nella parola "teatro";
		- $\{x: x \text{ è una lettera della parola "attore"}\}$;
		- l'insieme formato dalle lettere $\text{a, e, o, r, t}$.
	3. Quali dei seguenti insiemi sono differenti: $\emptyset, \{0\}, \{\emptyset\}$?
	4. Siano $A = \{1, 2, 3, 4\}, B = \{2, 4, 6, 8\}$, e $C = \{3, 4, 5, 6\}$.
	Trovare:
		- (a) $A \cup B$
		- (b) $B \cup B$
		- (c) $(A \cup B) \cup C$
		- (d) $A \cap B$
		- (e) $B \cap B$
		- (f) $(A \cap B) \cap C$
		- (g) $A - B$
		- (h) $B - B$
		- (i) $(A - B) - C$
	5. Sia $U = \{a, b, c, d, e\}$ un insieme universo e siano $A = \{a, b, d \}$ e $B = \{b, d, e\}$ due insiemi definiti in tale universo. Trovare:
		- $B^\prime$
		- $A^\prime \cap B$
		- $A \cup B^\prime$
		- $A^\prime \cap B^\prime$
		- $B^\prime - A^\prime$
		- $(A \cap B)^\prime$
	6. Dimostrare la proprietà commutativa dell'unione insiemistica, cioè che, comunque si prendano due insiemi $A$ e $B$, si ha che $A \cup B = B \cup A$.
	7. Dimostrare che $\emptyset$ è l'elemento neutro per l'unione, cioè che, comunque si prenda un insieme $A$, si ha che $A \cup \emptyset = A$.
	8. Dimostrare che la differenza insiemistica non gode della proprietà commutativa.
	9. Siano $A = \{1, (2, 3)\}$ e $B = \{2, 4\}$. Si calcoli il prodotto cartesiano $A \times B$.
	10. Si calcoli il prodotto cartesiano tra l'insieme $A = \{1, 2, 3\}$ e l'insieme $B = \{x : \frac{x}{0} = 3\}$.
	11. Si dimostri che il prodotto cartesiano non è commutativo.
	12. Sia $A = \{2, \{4, 5\}, 4\}$. Quali delle seguenti proposizioni sono sbagliate e perché?

		- (a) $\{4, 5\} \subseteq A$
		- (b) $\{4, 5\} \in A$
		- (c) $\{\{4, 5\}\} \subseteq A$
		- (d) $5 \in A$
		- (e) $\{5\} \in A$
		- (f) $\{5\} \subseteq A$
	13. Sia $B = \{1, 0\}$. Dire se ciascuna delle seguenti proposizioni è giusta o sbagliata:

		- (a) $\{0\} \in B$
		- (b) $\emptyset \in B$
		- (c) $\{0\} \subseteq B$
		- (d) $0 \in B$
		- (e) $0 \subseteq B$
	14. Siano $A = \{1, 2, 3, 4\}$, $B = \{2, 4, 6, 8\}$, e $C = \{3, 4, 5, 6\}$. Trovare:

		- (a) $A \cup C$
		- (b) $B \cup C$
		- (c) $C \cup C$
		- (d) $A \cup (B \cup C)$
		- (e) $A \cap C$
		- (f) $B \cap C$
		- (g) $C \cap C$
		- (h) $A \cap (B \cup C)$
		- (i) $A - C$
		- (l) $B - C$
		- (m) $C - C$
		- (n) $A - (B - C)$
	15. Sia $U = \{a, b, c, d, e, f, g\}$ un insieme universo e siano $A = \{a, b, c, d, e\}$, $B = \{a, c, e, g\}$ e $C = \{b, e, f, g\}$ tre insiemi definiti in tale universo. Trovare:

		- (a) $B^\prime$
		- (b) $A^\prime - B$
		- (c) $B^\prime \cup C$
		- (d) $(A - C)^\prime$
		- (e) $C^\prime \cap A$
		- (f) $(A - B^\prime)^\prime$
		- (g) $(A \cap A^\prime)^\prime$
	16. Dimostrare per doppia inclusione la proprietà commutativa dell'intersezione insiemistica. 
	17. Dimostrare per doppia inclusione la proprietà associativativa dell'intersezione insiemistica, cioè che, comunque si prendano tre insiemi $A$, $B$ e $C$, si ha che $A \cap (B \cap C) = (A \cap B) \cap C$.
	18. Dimostrare che $\emptyset$ è l'elemento azzeratore dell'intersezione, cioè che, comunque si prende un insieme $A$, si ha che $A$ \cap \emptyset = \emptyset$.
	19. Dimostrare che la differenza insiemistica non gode della proprietà associativa.
	20. Dati gli insiemi $A = \{x \in \mathbb{Z} : −1 \leq x \leq 2\}$ e $B = \{x \in \mathbb{Z} : 3 < x < 6\}$, si calcolino:
		- (a) $A \times B$
		- (b) $B \times A$
		- (c) $A \times A$
		- (d) $B \times B$
	21. Si dimostri (per doppia inclusione) che $A \times (B \cup C) = (A \times B) \cup (A \cap C)$.
	22. Si dimostri (per doppia inclusione) che $A \times (B - C) = (A \times B) \ (A \times C)$.

??? lightbulb "Soluzioni"

	1. La (a) è corretta: $1$ è un elemento di $M$ e quindi $1$ appartiene a $M$, mentre l'insieme che contiene $1$ non è un elemento di $M$ (e quindi la (c) è sbagliata). La (b) è sbagliata: essendo un elemento di $M$, $1$ non ne è un sottoinsieme; invece $\{1\}$ è un sottoinsieme di $M$, e quindi la (d) è corretta.
	2. Due insiemi sono uguali se contengono gli stessi elementi. Pertanto, gli insiemi dati sono tutti uguali. Ricordiamo che, quando lavoriamo con un insieme, né l'ordine in cui i suoi elementi sono elencati né eventuali ripetizioni di uno stesso elemento contano.
	3. Sono tutti diversi: $\emptyset$ è un insieme senza elementi; $\{0\}$ è un insieme che contiene un solo elemento, il numero $0$; $\{\emptyset\}$ è anch'esso un insieme che contiene un solo elemento, ma questo elemento è a sua volta un insieme (in particolare, l'insieme vuoto).
	4. L'unione di due insiemi $X$ e $Y$ è l'insieme che contiene tutti gli elementi di $X$ e tutti gli elementi di $Y$ (senza ripetizioni e in un qualsiasi ordine); pertanto, $A \cup B = \{1, 2, 3, 4, 6, 8\}$, $B \cup B = \{2, 4, 6, 8\}$ e $(A \cup B) \cup C = \{1, 2, 3, 4, 5, 6, 8\}$.
	L'intersezione di due insiemi $X$ e $Y$ è l'insieme che contiene tutti gli elementi comuni a $X$ e $Y$; pertanto, $A \cap B = \{2, 4\}$, $B \cap B = \{2, 4, 6, 8\}$ e $(A \cap B) \cap C = {4}$. Infine, la differenza di due insiemi $X$ e $Y$ è l'insieme che contiene tutti gli elementi di $X$ che non appartengono a $Y$; pertanto, $A - B = \{1, 3\}$, $B - B = \emptyset$ e $(A - B) - C = \{1\}$.
	5.  Il complementare di un insieme $X$ rispetto a un universo $U$ è definito come la differenza tra $U$ e $X$, scritta $U - X$; pertanto:
		- $B^\prime = \{a,c\}, A^\prime \cap B = \{e\}$
		- $A \cup B^\prime = \{a,b,c,d\}, A^\prime \cap B^\prime = \{c\}$
		- $B^\prime - A^\prime = \{a\}$
		- $(A \cap B)^\prime = \{a,c,e\}$
    6. Useremo qui e in seguito una tecnica di prova standard per dimostrare l'uguaglianza di due insiemi $X$ e $Y$. Come già più volte detto, $X$ e $Y$ sono lo stesso insieme se hanno gli stessi elementi; pertanto, per dimostrare che $X$ è uguale a $Y$, dobbiamo dimostrare che ogni elemento di $X$ è anche un elemento di $Y$ e viceversa (in simboli, che $X \subseteq Y$ e $Y \subseteq X$). Questa tecnica di prova è chiamata doppia inclusione. Per definizione $A \cup B = \{x: x \in A \text{ o } x \in B\}$ e $B \cup A = \{x: x \in B \text{ o } x \in A\}$. Si deve dimostrare che $A \cup B \subseteq B \cup A$ e che $B \cup A \subseteq A \cup B$. Se $x \in A \cup B$, allora $x \in A$ oppure $x \in B$; quindi $x \in B \cup A$. L'inclusione opposta è simmetrica.
    7. Per definizione $A \cup \emptyset = \{x: x \in A \text{ o } x \in \emptyset\}$. Per definizione $x \in \emptyset$ non è mai verificata; quindi $\{x: x \in A \text{ o } x \in \emptyset\} = \{x: x \in A\} = A$, da cui $A \cup \emptyset = A$.
    8. Se valesse, la proprietà commutativa della differenza insiemistica affermerebbe che, comunque si prendono due insiemi $A$ e $B$, si ha che $A - B = B - A$. Per alcune scelte di $A$ e $B$ questo vale: per esempio, basta prendere $A = B$; ma in generale questo non vale. Si prendano per esempio $A = \{1, 2, 3\}$ e $B = \{3, 4\}$: per definizione, $A - B = \{1, 2\}$ mentre $B - A = \{4\}$. Poiché abbiamo mostrato che la proprietà non è verificata per un'opportuna scelta di $A$ e $B$, otteniamo che la differenza insiemistica non è commutativa.
    9. Il prodotto cartesiano di due insiemi $X$ e $Y$ è formato da tutte e sole le coppie $(x, y)$ tali che $x$ è un qualsiasi elemento di $X$ e $y$ è un qualsiasi elemento di $Y$. Pertanto, $A \times B = \{(1, 2), (1, 4), ((2, 3), 2), ((2, 3), 4)\}$. Si noti, infatti, che $A$ contiene due elementi: uno è il numero $1$, l'altro è la coppia $(2, 3)$.
    10. Essendo l'insieme B vuoto, si ha che anche $A \times B$ è vuoto.
    11. Consideriamo $A = \{1\}$ e $B = \{2\}$; allora, $A \times B = \{(1, 2)\}$ e $B \times A = \{(2, 1)\}$. Si osservi che la coppia $(1, 2)$ è diversa dalla coppia $(2, 1)$: infatti, mentre negli insiemi l'ordine con cui gli elementi vengono dati non conta, nelle coppie (e, in generale, nelle n-ple) l'ordine conta! Quindi, $A \times B \neq B \times A$.
    12. L'insieme $A$ ha esattamente tre elementi: l'elemento $2$, l'elemento $4$ e l'insieme che contiene l'elemento $4$ e l'elemento $5$. Quindi:
    	- (a) $\{4, 5\} \subseteq A$ è sbagliata in quanto l'insieme $5$ non è un elemento di $A$;
    	- (b) $\{4, 5\} \in A$ è giusta in quanto l'insieme che contiene l'elemento $4$ e l'elemento $5$ è un elemento di $A$;
    	- (c) $\{\{4, 5\}\} \subseteq A$ è giusta per lo stesso motivo del punto (b);
    	- (d) $5 \in A$ è sbagliata perchè $5$ non è un elemento di $A$;
    	- (e) $\{5\} \in A$ è sbagliata perchè l'insieme che contiene l'elemento $5$ non è un elemento di $A$;
    	- (f) $\{5\} \subseteq A$ è sbagliata per lo stesso motivo del punto (d).
    13. L'insieme $B$ ha esattamente due elementi: l'elemento $1$ e l'elemento $0$. Quindi:
    	- (a) $\{0\} \in B$ è sbagliata in quanto l'insieme che contiene l'elemento $0$ non è un elemento di $B$;
    	- (b) $\emptyset \in B$ è sbagliata perchè l'insieme vuoto non è un elemento di $B$ (per essere giusta, l'insieme B sarebbe dovuto essere uguale a $\{1, 0, \emptyset\}$ che è diverso da $\{1, 0\}$);
    	- (c) $\{0\} \subseteq B$ è giusta dato che $0$ è un elemento di $B$;
    	- (d) $0 \in B$ è giusta per lo stesso motivo del punto (c);
    	- (e) $0 \subseteq B$ è sbagliata dato che non ha senso chiedersi se un elemento è sottoinsieme di un insieme (invece ha senso chiedersi se un insieme è sottoinsieme di un altro).
    14. 
    	- (a) $A \cup C = \{1,2,3,4,5,6\}$
    	- (b) $B \cup C = \{2,3,4,5,6,8\}$
    	- (c) $C \cup C = \{3,4,5,6\} = C$
    	- (d) $A \cup (B \cup C) = \{1,2,3,4,5,6,8\}$
    	- (e) $A \cap C = \{3,4\}$
    	- (f) $B \cap C = \{4,6\}$
    	- (g) $C \cap C = \{3,4,5,6\} = C$
    	- (h) $A \cap (B \cap C) = \{4\}$
    	- (i) $A - C = \{1,2\}$
    	- (l) $B - C = \{2,8\}$
    	- (m) $C - C = \{\emptyset\}$
    	- (n) $A - (B - C) = \{1,3,4\}$