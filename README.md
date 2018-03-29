# TikZ-Images

In this repository, we will include code for creating certain TikZ images that have been of use for PLU faculty over the years.


****

![](./src/lightsoutgrid.png)

  <!--- * [anotacoes_intersecao.pgf](https://github.com/walmes/Tikz/blob/master/src/anotacoes_intersecao.pgf) --->

```tex

\begin{tikzpicture}[thick]
   \draw[black,thick] (0,0) grid (5,5); %draws the five-by-five grid where (0,0) is lower left corner
   \draw[fill=black!20!white] (1,1) rectangle (2,2); %draws a shaded rectangle in the 2,2 spot of the 
   \draw[fill=black!20!white] (4,0) rectangle (5,1); %draws a shaded rectangle at the bottom right corner
   \draw[fill=black!20!white] (3,1) rectangle (4,2);
   \draw[fill=black!20!white] (2,4) rectangle (3,5);
   \draw[fill=black!20!white] (0,3) rectangle (1,4);
\end{tikzpicture}

```
