# linanbeamer

Beamer for my presentations adapted from [mtheme](https://github.com/matze/mtheme) and using [solarized](http://ethanschoonover.com/solarized) colors.

## Quick Start

No hassle way:

```
\documentclass[9pt, compress]{beamer}
\usepackage{linanbeamer}

\begin{document}
\title{Literature Review and Data} 
\author{Linan Qiu} 
\date{\today} 

\frame{\titlepage} 

\frame{\frametitle{Table of contents}\tableofcontents} 

\section{Introduction}

\begin{frame}[fragile]
\frametitle{Data Collection}
We have collected substantial data amounting to more than 20GB. These include
\begin{itemize}
\item Reddit data for the past 1 year on these topics: \texttt{bitcoin} \texttt{silkroad} \texttt{cryptocurrency}
\item Individual trades for most exchanges in most currencies for \textbf{Bitcoins} for the past 3 years
\item Leaked MtGox data
\item Standard public data on Bitcoins (daily prices, volumes etc) including Google Trends
\end{itemize}
\end{frame}
```

Long winded way

```
\documentclass[9pt, compress]{beamer}
\usetheme{msolarized}

\usepackage{booktabs}
\usepackage[scale=2]{ccicons}
\usepackage{multicol}

\begin{document}
\title{Literature Review and Data} 
\author{Linan Qiu} 
\date{\today} 

\frame{\titlepage} 

\frame{\frametitle{Table of contents}\tableofcontents} 

\section{Introduction}


\begin{frame}[fragile]
\frametitle{Data Collection}
We have collected substantial data amounting to more than 20GB. These include
\begin{itemize}
\item Reddit data for the past 1 year on these topics: \texttt{bitcoin} \texttt{silkroad} \texttt{cryptocurrency}
\item Individual trades for most exchanges in most currencies for \textbf{Bitcoins} for the past 3 years
\item Leaked MtGox data
\item Standard public data on Bitcoins (daily prices, volumes etc) including Google Trends
\end{itemize}
\end{frame}
```