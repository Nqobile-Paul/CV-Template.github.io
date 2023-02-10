\documentclass{article}
\usepackage[left=1in,right=1in,top=1in,bottom=1in]{geometry}
\usepackage{fontawesome}
\usepackage[prologue]{ titlesec }
\titleformat{\section}{\Large\bfseries}{\thesection.}{1em}{}
\renewcommand\thesection{\arabic{section}}
\begin{document}

\section{Personal Information}
\begin{tabular}{ p{3cm} p{10cm} }
\textbf{Name:} & John Doe \\
\textbf{Address:} & 123 Main Street, Anytown, USA \\
\textbf{Phone:} & (123) 456-7890 \\
\textbf{Email:} & john.doe@email.com \\
\textbf{Website:} & \href{https://johndoe.com}{johndoe.com} \\
\textbf{LinkedIn:} & \href{https://linkedin.com/in/johndoe}{linkedin.com/in/johndoe} \\
\end{tabular}

\section{Summary}
A highly motivated and results-driven individual with a strong background in computer science. Possesses excellent problem-solving skills and the ability to work effectively in a team environment.

\section{Education}
\begin{tabular}{ p{3cm} p{10cm} }
\textbf{Degree:} & Bachelor of Science in Computer Science \\
\textbf{University:} & University of ABC \\
\textbf{Graduation Date:} & May 2020 \\
\textbf{GPA:} & 3.5/4.0 \\
\end{tabular}

\section{Technical Skills}
\begin{tabular}{ p{3cm} p{10cm} }
\textbf{Languages:} & Python, C++, Java \\
\textbf{Tools:} & Git, GitHub, JIRA, Trello \\
\textbf{Platforms:} & Windows, Linux, macOS \\
\end{tabular}

\section{Work Experience}
\begin{tabular}{ p{3cm} p{10cm} }
\textbf{Position:} & Software Engineer \\
\textbf{Company:} & XYZ Inc. \\
\textbf{Duration:} & June 2020 - Present \\
\textbf{Responsibilities:} &
\begin{itemize}
\item Developed and maintained software applications using Python and C++
\item Contributed to the design and implementation of new features
\item Fixed bugs and resolved technical issues in a timely manner
\item Participated in code reviews and provided constructive feedback to team members
\end{itemize}
\end{tabular}

\section{Projects}
\begin{tabular}{ p{3cm} p{10cm} }
\textbf{Project:} & Image Classification \\
\textbf{Description:} &
Developed a deep learning model for classifying images of handwritten digits using the MNIST dataset. The model achieved an accuracy of 98\%.
\end{tabular}

\end{document}
