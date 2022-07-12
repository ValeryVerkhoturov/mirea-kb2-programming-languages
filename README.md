XeLaTeX шаблон по учебно-методическому пособию [&laquo;Методические рекомендации по выполнению курсовой работы по дисциплине &#8222;Языки программирования&#8221;&raquo; А.А.&nbsp;Мерсов, А.М.&nbsp;Русаков, В.В.&nbsp;Филатов 2022](https://library.mirea.ru/share/4488)

[Документация к классу документа, пример скомпилированного документа](/document.pdf).

Шаблон документа:
```TeX
\documentclass{mirea-prog-lang}

\usepackage{hyperref}
\hypersetup{pdftitle={Языки программирования}, pdfauthor={И. О. Фамилия}, colorlinks=false, pdfborder={0 0 0}}

\begin{document}
  \begin{titlepage}
    ...
  \end{titlepage}
  
  \begin{abstract}
    ...
  \end{abstract}
  
  \tableofcontents
  
  \section*{Введение}
  \phantomsection 
  \addcontentsline{toc}{section}{Введение}
  ...
  
  \section{...}
  ...
  
  \appendix
  \section{...}
  ...
  
\end{document}
```