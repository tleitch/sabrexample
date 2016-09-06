---
title: Introduction to General Swaption Vlaution with SabrSwaption
author:
  - name: Terry Leitch
    affiliation: Ruxton Advisors
    address:
    - line 1
    - line 2
    email:  tleitch1@jhu.edu
  - name: Author Two
    affiliation: Affiliation
    address:
    - line 1
    - line 2
    email:  author2@work
abstract: >
  An abstract of less than 150 words.
preamble: >
  % Any extra latex you need in the preamble
output: rticles::rjournal_article
---

## Introduction

Introductory section which may include references in parentheses
\citep{R}, or cite a reference such as \citet{R} in the text.

## Section title in sentence case

This section may contain a figure such as Figure \ref{figure:rlogo}.

\begin{figure}[htbp]
  \centering
  \includegraphics{Rlogo}
  \caption{The logo of R.}
  \label{figure:rlogo}
\end{figure}

## Another section

There will likely be several sections, perhaps including code snippets, such as:


```r
x <- 1:10
x
```

```
##  [1]  1  2  3  4  5  6  7  8  9 10
```

## Summary

This file is only a basic article template. For full details of _The R Journal_ style and information on how to prepare your article for submission, see the [Instructions for Authors](https://journal.r-project.org/share/author-guide.pdf).
\bibliography{RJreferences}
