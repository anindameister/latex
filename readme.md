- special characters

https://tex.stackexchange.com/questions/34580/escape-character-in-latex

- student@LabtainersVM:\textasciitilde/labtainer/labtainer-student\$ 

- insertting images

- https://www.overleaf.com/learn/latex/Inserting_Images

- fitting to screen

- https://tex.stackexchange.com/questions/32886/how-to-fit-a-large-figure-to-page
```
\usepackage{graphicx}
\graphicspath{ {./images/} }
\includegraphics[width=\textwidth,height=\textheight,keepaspectratio]{Screenshot from 2020-09-30 02-20-21.png}
```

- readme.md way of writing code is as follows

```
\usepackage{listings}

\begin{lstlisting}
less sampleMath.c
\end{lstlisting}
```
- readme.md's - is equivalent to below
- https://tex.stackexchange.com/questions/74279/how-to-add-bullets-to-description-lists
- https://www.overleaf.com/learn/latex/code_listing

```
\begin{itemize}
\item now compiling
\end{itemize}
```
- https://www.overleaf.com/learn/latex/bibliography_management_with_bibtex
- citation
```
\begin{itemize}
    \item let's break up the program for sampleMath2.c
    \item in order to breakup the program let's create a file named sampleMath2breakup.c
    \item gedit sampleMath2breakup.c \cite{latexcompanion}

\end{itemize}

\begin{thebibliography}{9}
\bibitem{latexcompanion} 
\\\texttt{https://vitux.com/how-to-write-and-run-a-c-program-in-linux/}. 

\end{thebibliography}
\end{document}
```

https://tex.stackexchange.com/questions/312/correctly-typesetting-a-tilde

https://www.youtube.com/watch?v=7XhyqqUftl0
- some symbols
