# texformat
load as subtree:

```shell
git subtree add --prefix=https://github.com/jeffreyhingstman/texformat master --squash

git subtree pull --prefix=https://github.com/jeffreyhingstman/texformat master --squash
```



```latex
\documentclass[a4paper, 12pt]{article}
\input{format/preamble.tex}

\begin{document}
	\title{Format} 
	\date{\today}
	\author{Jeffrey Hingstman, s4590465}	\maketitle
\end{document}
```



