---
title: Domande
---

- Come dimostrare che l'insieme dei numeri naturali $N$ e l'insieme dei numeri razionali $Q$ hanno la stessa Cardinalità?

??? example "Esempio - Dimostrazione"
	1. **Rappresentazione dei numeri razionali**  
   	L'insieme $\mathbb{Q}$ dei numeri razionali può essere scritto come:  

	   	$$
	    \begin{array}{c}
	        \mathbb{Q} = \left\{ \frac{p}{q} \mid p \in \mathbb{Z}, q \in \mathbb{N}^+ \right\}
	    \end{array}
	    $$
 
   	dove $p$ è il numeratore (intero) e $q$ il denominatore (naturale positivo).
	
	2. **Organizzazione in una griglia bidimensionale**  
   	Organizziamo i numeri razionali in una tabella bidimensionale:  
	   	- Ogni riga rappresenta $q$, il denominatore (positivo).  
	   	- Ogni colonna rappresenta $p$, il numeratore (può essere positivo o negativo).
	
   	La griglia ha questa forma:
	
   	| $q \backslash p$ | -2       | -1       | 0        | 1        | 2        |
   	|----------------------|----------|----------|----------|----------|----------|
   	| 1                    | -2/1     | -1/1     | 0/1      | 1/1      | 2/1      |
   	| 2                    | -2/2     | -1/2     | 0/2      | 1/2      | 2/2      |
   	| 3                    | -2/3     | -1/3     | 0/3      | 1/3      | 2/3      |
   	| 4                    | -2/4     | -1/4     | 0/4      | 1/4      | 2/4      |
	
	3. **Evitare duplicati**  
   	Consideriamo solo i numeri razionali in forma ridotta (es. $\text{MCD}(p, q) = 1$). Questo elimina elementi come $\frac{2}{4} = \frac{1}{2}$.
	
	4. **Enumerazione della griglia**  
   	Usiamo una **camminata diagonale** per attraversare la griglia, visitando ogni elemento:  
   		- Partiamo da $\frac{0}{1}$, poi $\frac{1}{1}$, $\frac{-1}{1}$, $\frac{1}{2}$, $\frac{0}{2}$, $\frac{-1}{2}$, $\frac{2}{1}$, e così via.
	
   	Seguiamo il percorso diagonale:
	
   	| Passo | Numero Razionale | Forma Ridotta |
   	|-------|------------------|---------------|
   	| 1     | $\frac{0}{1}$ | $\frac{0}{1}$ |
   	| 2     | $\frac{1}{1}$ | $\frac{1}{1}$ |
   	| 3     | $\frac{-1}{1}$ | $\frac{-1}{1}$ |
   	| 4     | $\frac{1}{2}$ | $\frac{1}{2}$ |
   	| 5     | $\frac{0}{2}$ | $\frac{0}{1}$ (duplicato, escluso) |
   	| 6     | $\frac{-1}{2}$ | $\frac{-1}{2}$ |
   	| 7     | $\frac{2}{1}$ | $\frac{2}{1}$ |
	
	5. **Definizione di una funzione biunivoca**  
   	Associare ogni razionale ridotto a un numero naturale $n$ garantisce una corrispondenza biunivoca. Ad esempio:
	   	- $\frac{0}{1} \to 1$,  
	   	- $\frac{1}{1} \to 2$,  
	   	- $\frac{-1}{1} \to 3$,  
	   	- $\frac{1}{2} \to 4$, e così via.
	
	6. **Conclusione**  
   	Poiché possiamo elencare $\mathbb{Q}$ in una sequenza ordinata, è numerabile.  
   	Quindi, $\mathbb{N}$ e $\mathbb{Q}$ hanno la stessa cardinalità:

   		$$
	    \begin{array}{c}
	        |\mathbb{Q}| = |\mathbb{N}|
	    \end{array}
	    $$


- La differenza fra $\emptyset, \{ \, \}, \{\emptyset\}$
- Perchè in un insieme infinitamente discendente ($A = \{\dots \leq a_2 \leq a_1 \leq a_0\}$) non è presente un elemento $\bot$?
- Data una Relazione $\mathcal{R} = \{a + b = 0\}$ sull'insieme $\mathcal{N} \times \mathcal{N}$, la Relazione è Antisimmetrica e Transitiva?