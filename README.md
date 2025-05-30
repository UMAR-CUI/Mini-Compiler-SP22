\documentclass{article}
\usepackage[utf8]{inputenc}
\usepackage{hyperref}

\title{Mini Compiler for Compiler Construction}
\author{Umar Farooq \and Abdullah ``GayNigger'' Qaisar}
\date{}

\begin{document}

\maketitle

\section*{Project Description}
This repository contains a mini compiler implementation developed for the Compiler Construction course. The compiler is implemented entirely in C\# and is designed to be executed using the .NET CLI.

\section*{Features}
\begin{itemize}
    \item Lexical analysis (scanning)
    \item Syntax analysis (parsing)
    \item Semantic analysis
    \item Code generation (for a target architecture/virtual machine)
    \item Error handling and reporting
\end{itemize}

\section*{Requirements}
\begin{itemize}
    \item .NET SDK (version X.X or higher)
\end{itemize}

\section*{Usage}
\begin{enumerate}
    \item Clone the repository
    \item Navigate to the project directory
    \item Run using the .NET CLI:
    \begin{verbatim}
    dotnet run [input_file]
    \end{verbatim}
\end{enumerate}

\section*{Contribution}
This project was developed collaboratively by:
\begin{itemize}
    \item Umar Farooq
    \item Abdullah ``GayNigger'' Qaisar
\end{itemize}

\end{document}
