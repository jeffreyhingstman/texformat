# texformat
load as subtree:

```shell
git subtree add --prefix=format https://github.com/jeffreyhingstman/texformat master --squash

git subtree pull --prefix=format https://github.com/jeffreyhingstman/texformat master --squash

git subtree push --prefix=format https://github.com/jeffreyhingstman/texformat master --squash
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



