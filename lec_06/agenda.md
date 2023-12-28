# Asymmetric cryptography: DHKE some other key-exhange protocols

\begin{frame}{Discrete logarithm problem in $\mathbb{Z}^*_n$}
	\section{Discrete logarithm problem in $\mathbb{Z}^*_n$}
	%since $\mathbb{Z}^*_n$ indeed forms a group, we can construct the discrete log problem
	\begin{block}{}
		For given $n \in \mathbb{N}_+$ the discrete logarithm problem in $\mathbb{Z}^*_n$ can be formulated the 
		following way:
	\end{block}
	
	\begin{block}{}
		For any $a, b \in \mathbb{Z}^*_n$ find $x : a^x = b \mod n$. If such $x$ exists, it is called the discrete 
		logarithm of $b$ with respect to base $a$.
	\end{block}
	
	\begin{example}[DLP in $\mathbb{Z}^*_{13}$]
		\begin{tabular}{>{\small}c>{\small}c>{\small}c}
			$2^0 = 1$ & $2^4 = 3$ & $2^8 = 9$ \\
			$2^1 = 2$ & $2^5 = 6$ & $2^9 = 5$ \\
			$2^2 = 4$ & $2^6 = 12$ & $2^{10} = 10$ \\
			$2^3 = 8$ & $2^7 = 11$ & $2^{11} = 7$
		\end{tabular}
	\end{example}
	% on the whiteboard example when DLP does not have any solutions
\end{frame}


- DLP
- DHP, (note! the DLP and DHP can be applied anywhere, where it is hard to find the DLP)

- Example of group where it is easy to find DLP
    - $(\mathbb{Z}_p, +)

- Recap on attacks

- 2DH key exchange
- SIG DH key exchange

# HW
Посмотреть на cryptohack https://cryptohack.org/challenges/diffie-hellman/