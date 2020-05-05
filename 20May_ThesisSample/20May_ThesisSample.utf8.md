---
title: "Dissertating for USU"
author: "Emily G. Mantin"
geometry: [top=1in, bottom=1in, right=1in, left=1.5in]
year: "2020"
degree: "Doctor of Philosophy"
field: "Applied Science"
department: "Your Department"
uni: "Saint Mary's University"
location: "Halifax, Nova Scotia, Canada"
chair: "Chair Person"
committee2: "Committee Member 1"
committee3: "Committee Member 2"
committee4: "Committee Member 3"
committee5: "Committee Member 4"
gradschool: "Richard S. Inouye, Ph.D."
gradschoollabel: "Vice Provost for Graduate Studies"
bibliography: yourbibfile.bib
output:
  dissertateUSU::dissertateUSU:
    latex_engine: xelatex
    keep_tex: yes
    pandoc_args: [ "--csl", "apa7.csl" ]
---




<!-- Abstract -->
\newpage
\pagestyle{plain} <!-- can use \pagestyle{fancy} for a horizontal line in header -->
\fancyhead[R]{\thepage}
\fancyfoot[C]{}
\chapter*{ABSTRACT}
\addcontentsline{toc}{section}{Abstract}

\abstracttitle
\doublespacing

Your abstract words go here. The line below puts the total number of pages at the end of your abstract (as required).

\begin{flushright}(\pageref{LastPage} pages)\end{flushright}


<!-- Public Abstract -->
\newpage
\fancyhead[R]{\thepage}
\fancyfoot[C]{}
\chapter*{PUBLIC ABSTRACT}
\addcontentsline{toc}{section}{Public Abstract}
\doublespacing

Your publicly abstracted words go here.


<!-- Dedication -->
\newpage
\fancyhead[R]{\thepage}
\fancyfoot[C]{}
\chapter*{DEDICATION}
\addcontentsline{toc}{section}{Dedication}

Dedicate it.


<!-- Acknowledgments -->
\newpage
\fancyhead[R]{\thepage}
\fancyfoot[C]{}
\chapter*{ACKNOWLEDGMENTS}
\addcontentsline{toc}{section}{Acknowledgments}

Acknowledge those acknowledgable individuals and things.


<!-- Front Matter -->
\newpage
\fancyhead[R]{\thepage}
\fancyfoot[C]{}
\tableofcontents

\newpage
\fancyhead[R]{\thepage}
\fancyfoot[C]{}
\listoftables

\newpage
\fancyhead[R]{\thepage}
\fancyfoot[C]{}
\listoffigures


\newpage
\pagenumbering{arabic}

<!-- Chapter 1 -->
\newpage
\fancyhead[R]{\thepage}
\fancyfoot[C]{}

\chapter{INTRODUCTION}


\doublespacing

Write your Chapter 1 in this file. Generally this chapter is the introduction. We may have several citations [@RCoreTeam; @dissertateUSU]. Go ahead and erase all the text in this chapter (and the other chapter files, as they are just trying to fill up space for the example). Just keep the `\\doublespacing` at the beginning of this document.

\lipsum




<!-- Chapter 2 -->
\FloatBarrier
\newpage
\fancyhead[R]{\thepage}
\fancyfoot[C]{}

\chapter{Chapter 2's Title}


\doublespacing

Write your Chapter 2 in this file. Go ahead and erase all the text in this chapter (and the other chapter files, as they are just trying to fill up space for the example)

\lipsum


<!-- Chapter 3 -->
\FloatBarrier
\newpage
\fancyhead[R]{\thepage}
\fancyfoot[C]{}

\chapter{Chapter 3's Title}


\doublespacing

Write your Chapter 3 in this file. Go ahead and erase all the text in this chapter (and the other chapter files, as they are just trying to fill up space for the example)

\lipsum


<!-- Chapter 4 -->
\FloatBarrier
\newpage
\fancyhead[R]{\thepage}
\fancyfoot[C]{}

\chapter{Chapter 4's Title}


\doublespacing

Write your Chapter 4 in this file. Go ahead and erase all the text in this chapter (and the other chapter files, as they are just trying to fill up space for the example)

\lipsum


<!-- Chapter 5 -->
\FloatBarrier
\newpage
\fancyhead[R]{\thepage}
\fancyfoot[C]{}

\chapter{Chapter 5's Title}


\doublespacing

Write your Chapter 5 in this file. Go ahead and erase all the text in this chapter (and the other chapter files, as they are just trying to fill up space for the example)

\lipsum


<!-- References -->
\FloatBarrier
\newpage
\fancyhead[R]{\thepage}
\fancyfoot[C]{}

\chapter*{REFERENCES}

\setlength{\parindent}{-0.5in}
\setlength{\leftskip}{0.4in}
\setlength{\parskip}{6pt}
\noindent
