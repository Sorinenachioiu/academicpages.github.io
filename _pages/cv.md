%-------------------------
% Resume in Latex
% Author : Jake Gutierrez
% Based off of: https://github.com/sb2nov/resume
% License : MIT
%------------------------

\documentclass[letterpaper,11pt]{article}

\usepackage{latexsym}
\usepackage[empty]{fullpage}
\usepackage{titlesec}
\usepackage{marvosym}
\usepackage[usenames,dvipsnames]{color}
\usepackage{verbatim}
\usepackage{enumitem}
\usepackage[hidelinks]{hyperref}
\usepackage{fancyhdr}
\usepackage[english]{babel}
\usepackage{tabularx}
\usepackage{fontawesome5}
\usepackage{multicol}
\setlength{\multicolsep}{-3.0pt}
\setlength{\columnsep}{-1pt}
\input{glyphtounicode}


%----------FONT OPTIONS----------
% sans-serif
% \usepackage[sfdefault]{FiraSans}
% \usepackage[sfdefault]{roboto}
% \usepackage[sfdefault]{noto-sans}
% \usepackage[default]{sourcesanspro}

% serif
% \usepackage{CormorantGaramond}
% \usepackage{charter}


\pagestyle{fancy}
\fancyhf{} % clear all header and footer fields
\fancyfoot{}
\renewcommand{\headrulewidth}{0pt}
\renewcommand{\footrulewidth}{0pt}

% Adjust margins
\addtolength{\oddsidemargin}{-0.6in}
\addtolength{\evensidemargin}{-0.5in}
\addtolength{\textwidth}{1.19in}
\addtolength{\topmargin}{-.7in}
\addtolength{\textheight}{1.4in}

\urlstyle{same}

\raggedbottom
\raggedright
\setlength{\tabcolsep}{0in}

% Sections formatting
\titleformat{\section}{
  \vspace{-4pt}\scshape\raggedright\large\bfseries
}{}{0em}{}[\color{black}\titlerule \vspace{-5pt}]

% Ensure that generate pdf is machine readable/ATS parsable
\pdfgentounicode=1

%-------------------------
% Custom commands
\newcommand{\resumeItem}[1]{
  \item\small{
    {#1 \vspace{-2pt}}
  }
}

\newcommand{\classesList}[4]{
    \item\small{
        {#1 #2 #3 #4 \vspace{-2pt}}
  }
}

\newcommand{\resumeSubheading}[4]{
  \vspace{-2pt}\item
    \begin{tabular*}{1.0\textwidth}[t]{l@{\extracolsep{\fill}}r}
      \textbf{#1} & \textbf{\small #2} \\
      \textit{\small#3} & \textit{\small #4} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubSubheading}[2]{
    \item
    \begin{tabular*}{0.97\textwidth}{l@{\extracolsep{\fill}}r}
      \textit{\small#1} & \textit{\small #2} \\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeProjectHeading}[2]{
    \item
    \begin{tabular*}{1.001\textwidth}{l@{\extracolsep{\fill}}r}
      \small#1 & \textbf{\small #2}\\
    \end{tabular*}\vspace{-7pt}
}

\newcommand{\resumeSubItem}[1]{\resumeItem{#1}\vspace{-4pt}}

\renewcommand\labelitemi{$\vcenter{\hbox{\tiny$\bullet$}}$}
\renewcommand\labelitemii{$\vcenter{\hbox{\tiny$\bullet$}}$}

\newcommand{\resumeSubHeadingListStart}{\begin{itemize}[leftmargin=0.0in, label={}]}
\newcommand{\resumeSubHeadingListEnd}{\end{itemize}}
\newcommand{\resumeItemListStart}{\begin{itemize}}
\newcommand{\resumeItemListEnd}{\end{itemize}\vspace{-5pt}}

%-------------------------------------------
%%%%%%  RESUME STARTS HERE  %%%%%%%%%%%%%%%%%%%%%%%%%%%%


\begin{document}

%----------HEADING----------
% \begin{tabular*}{\textwidth}{l@{\extracolsep{\fill}}r}
%   \textbf{\href{http://sourabhbajaj.com/}{\Large Sourabh Bajaj}} & Email : \href{mailto:sourabh@sourabhbajaj.com}{sourabh@sourabhbajaj.com}\\
%   \href{http://sourabhbajaj.com/}{http://www.sourabhbajaj.com} & Mobile : +1-123-456-7890 \\
% \end{tabular*}

\begin{center}
    {\Huge \scshape Sorin-Catalin Enachioiu} \\ \vspace{1pt}
    Barbarasteeg 2, Delft, The Netherlands \\ \vspace{1pt}
    \small \raisebox{-0.1\height}\faPhone\ +40 725 576 145 ~ \href{mailto:x@gmail.com}{\raisebox{-0.2\height}\faEnvelope\  \underline{sorinenachioiu@yahoo.com}} ~ 
    \href{https://linkedin.com/in//}{\raisebox{-0.2\height}\faLinkedin\ \underline{https://www.linkedin.com/in/senachioiu/}}  ~ \\
    \href{https://github.com/}  {\raisebox{-0.2\height}\faGithub\ \underline{https://github.com/Sorinenachioiu}}
    \vspace{-8pt}
\end{center}


%-----------EDUCATION-----------
\section{Education}
  \resumeSubHeadingListStart
    \resumeSubheading
      {Delft University of Technology}{September 2022 - June 2025}
      {Bachelor of Science in Computer Science and Engineering}{Delft, The Netherlands}
     
  \resumeSubHeadingListEnd

\resumeItemListStart
    \resumeItem{\textbf{Honours Programme} participant researching \textbf{Electronic (Personal) Medical Health Records Sharing} in a \textbf{Distributed Network of Medical Data}. Enabling medical data to be transmitted in a privacy-preserving manner using blockchain technology and state-of-the-art privacy-enhancing technologies.}
\resumeItemListEnd

%------RELEVANT COURSEWORK-------
\section{Relevant Coursework}
    %\resumeSubHeadingListStart
        \begin{multicols}{4}
            \begin{itemize}[itemsep=-5pt, parsep=3pt]
                \item\small Data Structures
                \item Machine Learning  
                \item Data Mining
                \item Algorithm Design
                \item Computer Networks
                \item Big data processing  
                \item Object Oriented Programming
            \end{itemize}
        \end{multicols}
        \vspace*{2.0\multicolsep}
    %\resumeSubHeadingListEnd

%-----------PROJECTS-----------
\section{Projects}
    \vspace{-5pt}
    \resumeSubHeadingListStart
      \resumeProjectHeading
          {\textbf{Task Manager} $|$ \textbf{JavaFx, Spring Boot, JUnit, jqwik}}{January 2023}
          \resumeItemListStart
            \resumeItem{Developed a RESTful task list application using \textbf{Java}}
            \resumeItem{Enabled users to easily create and manage custom boards and their respective task lists}
            \resumeItem{Designed an intuitive and engaging frontend experience with \textbf{JavaFX}'s user interface components}
            \resumeItem{Developed a scalable and secure backend using  \textbf{Spring Boot}}
          \resumeItemListEnd
          \vspace{-13pt}
      \resumeProjectHeading
          {\textbf{Graphical representation of a hash function} $|$ \textbf{C++, p5.js}}{November 2021}
          \resumeItemListStart
            \resumeItem{Developed a way to display a hash in a graphic manner, starting from a text input and \\ being able to choose the size of the  generated image}
            \resumeItem{Used \textbf{C++} to generate the desired RGB values of the pixels and the \textbf{p5.js} library to \\ display them }
          \resumeItemListEnd 
          \vspace{-13pt}
          \resumeProjectHeading
          {\textbf{Arduino Car using Lee's Algorithm to Traverse a Room} $|$ \textbf{C++}}{August 2021}
          \resumeItemListStart
            \resumeItem{Aimed to implement an algorithm in a physical setting}
            \resumeItem{Used to find the minimum path a car should take in a room with obstacles}
          \resumeItemListEnd 
           \vspace{-13pt}
          \resumeProjectHeading
          {\textbf{Password Manager} $|$ \textbf{C++}}{August 2020}
          \resumeItemListStart
            \resumeItem{Implemented The Vigenere Cipher, an Autofill algorithm, and  a Password Generator algorithm}
            \resumeItem{Acquired important knowledge in the \textbf{C++} programming language, as well as an understanding \\  of Cryptography concepts}
          \resumeItemListEnd 
    \resumeSubHeadingListEnd
\vspace{-15pt}


%
%-----------PROGRAMMING SKILLS-----------
\section{Technical Skills}
 \begin{itemize}[leftmargin=0.15in, label={}]
    \small{\item{
     \textit{Programming Languages}{: \textbf{ Java, C++, Python, Scala, JavaScript, SQL, Bash Scripting}} \\
     \textit{Collaboration tools}{: \textbf{Git}} \\
    }}
 \end{itemize}
 \vspace{-16pt}


%-----------INVOLVEMENT---------------
\section{Leadership / Extracurricular}
    \resumeSubHeadingListStart
        
        \resumeSubheading{Center of Excellence in Informatics}{2019-2022}{eMAG}{}
            \resumeItemListStart
                \resumeItem{Gained a comprehensive understanding of various topics related to algorithms, data structures, \\ and competitive programming}
            \resumeItemListEnd
        \resumeSubheading{Project Management and Leadership Course}{2018-2019}{Proedus}{}
            \resumeItemListStart
                \resumeItem{Enhanced my understanding of the importance of organization }
                \resumeItem{Improved my skills in working in teams, including coordination and  leadership }
            \resumeItemListEnd
        \resumeSubheading{Handball}{2013 -- 2022}{Dinamo Bucharest Junior Club}{}
        
        
    \resumeSubHeadingListEnd

\section{Competitions}

\begin{itemize}[leftmargin=*, label={}]
\small
\item
\begin{tabular}[t]{@{}l@{}}
    \textbf{37th place at the CLOUDFLIGHT CODING CONTEST Classic, The Web} \\
    \textbf{4th place at TU Delft's Freshmen Programming Competition} \\
    \textbf{4th place at JetBrains University Challenge in The Netherlands} \\
    \textbf{2nd place at the Romanian Olympiad in Informatics Regional Stage} \\
    \textbf{Participant at the Romanian Olympiad in Informatics} \\
    \textbf{3rd place at the ASUS Challenge}
\end{tabular}
\hfill
\begin{tabular}[t]{@{}r@{}}
    \textbf{March 2023} \\
    \textbf{May 2023} \\
    \textbf{June 2023} \\
    \textbf{March 2021} \\
    \textbf{March 2020} \\
    \textbf{March 2021}
\end{tabular}
\end{itemize}
 \vspace{-16pt}

\end{document}
