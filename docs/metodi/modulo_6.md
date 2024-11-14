---
title: Modulo 6 e 7
---

## Assioma dell'Infinito
!!! abstract "Definizione ― Assioma dell'Infinito"
    Esiste un insieme che contiene zero e che contiene il successore di ciascuno dei suoi elementi.

!!! abstract "Definizione ― Conseguenza dell'Assioma dell'Infinito"
    L'insieme $\mathcal{N}$ dei numeri naturali è l'intersezione di tutti gli insiemi che contengono zero ed il successore di ciascuno dei loro elementi.

## Assiomi di Peano
!!! abstract "Definizione ― Assiomi di Peano"
    - Esiste un numero che si chiama zero
    - Ogni numero $n$ ha un successore che indichiamo con *succ*($n$)
    - Zero non è successore di nessuno
    - Se *succ*($n$) = *succ*($m$) allora $n = m$
    - Se $A \subseteq \mathcal{N}$ è tale che zero $\in A$ e inoltre $n \in A$ implica *succ*($m$) $\in A$, allora $A = \mathcal{N}$. 

## Induzione
!!! abstract "Definizione ― Principio di Induzione"
    Se $P$ è un predicato su $\mathcal{N}$ tale che vale $P(0)$ e inoltre $P(n)$ implica $P(n+1)$, allora per ogni $n$ vale $P(n)$.

??? example "Esempio"
	
	- Data la seguente equazione, dimostriamo che valga per ogni $n$ attraverso il principio di induzione:
	$$
	\begin{array}{c}
		\sum_{k=0}^{n} a^{k} = \frac{1-a^{n+1}}{1-a}
	\end{array}
	$$

	- Iniziamo con il passo base, quindi verificando che valga per $P(0)$:

	$$
	\begin{array}{c}
		\textcolor{orange}{\sum_{k=0}^{0} a^{k}} = \textcolor{lightblue}{\frac{1-a^{0+1}}{1-a}} \\
        \textcolor{orange}{1} = \textcolor{lightblue}{\frac{1-a}{1-a}} \\
        \textcolor{orange}{1} = \textcolor{lightblue}{1}
	\end{array}
	$$

	- Abbiamo dimostrato che $P(n)$ vale per $P(0)$.
	- Ora il passo induttivo: supponendo che l'equazione valga per un certo $P(n)$, dimostriamo che valga anche per $P(n+1)$.
	- Riscriviamo l'equazione sostituendo $n$ con $n+1$:

	$$
	\begin{array}{c}
		\sum_{k=0}^{n+1} a^{k}
	\end{array}
	$$

	- Sappiamo che $\sum_{k=0}^{n+1} a^{k}$ è uguale alla somma dei numeri naturali $a^{k}$ che partono da $k$ ($0$) fino a $n+1$, quindi:

	$$
	\begin{array}{c}
		\textcolor{orange}{a^0+a^1+\dots+a^n}+\textcolor{lightblue}{a^{n+1}}
	\end{array}
	$$
	 
	- Sappiamo che la prima parte (*in arancione*) corrisponde esattamente a $\sum_{k=0}^{n} a^{k}$ e inoltre per induzione sappiamo che quest'equazione, per qualsiasi $n$, è uguale a 

	$$
	\begin{array}{c}
		\frac{1-a^{n+1}}{1-a}
	\end{array}
	$$

	- Riscrivendo l'equazione completa otteniamo:

	$$
	\begin{array}{c}
		\frac{1-a^{n+1}}{1-a} + a^{n+1}
	\end{array}
	$$

	- Svolgendo i calcoli matematici otteniamo:

	$$
	\begin{array}{c}
		\frac{1-a^{n+1}+(1-a)a^{n+1}}{1-a} \\
		= \frac{1-a^{n+1}+a^{n+1}-a^{n+2}}{1-a} \\
		= \frac{1-a^{n+2}}{1-a}
	\end{array}
	$$

	- Quindi possiamo dire che:

	$$
	\begin{array}{c}
		\sum_{k=0}^{n+1} a^{k} = \frac{1-a^{n+2}}{1-a}
	\end{array}
	$$

	- ... la quale è esattamente la proprietà $P(n+1)$. Possiamo concludere che la proprietà $P(n)$ vale per ogni $n+1$.
