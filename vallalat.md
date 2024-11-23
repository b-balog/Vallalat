---
title: "Vállalat"
author: "Adatbázisok kötelező feladat"
header-includes: |
  \usepackage{fancyhdr}
  \pagestyle{fancy}
  \fancyhf{}
  \fancyhead[R]{\textbf{Név: Balog Benedek Zsolt \\ Neptun kód: JUDZOJ}}
  \renewcommand{\headrulewidth}{0.4pt}
  \usepackage{etoolbox}
  \AtBeginDocument{\thispagestyle{fancy}}
geometry: a4paper,textwidth=16cm
mainfont: "Times New Roman"
output: pdf_document
---

Egy vállalati nyilvántartó rendszerben tárolják a cég dolgozóinak, osztályainak,
részlegeinek és projektjeinek adatait. Az új dolgozóknak regisztrálniuk kell a
rendszerbe, majd bejelentkezés után használhatják azt. Az adminok aktualizálhatják az
adatokat, a többi dolgozó csak megtekintheti azokat, és beszámolót írhat azon
projektekhez, amelyekben részt vesz vagy vett.

# Egyed-kapcsolat modell

\noindent\rule{\textwidth}{0.4pt}

![E-K diagram](E-K.png)

A Department (részleg), Division (osztály) és Project gyenge egyedek. 
Az azonosításukra a manager-ük id-ját fogjuk használni.



# Relációs adatbázisséma

\noindent\rule{\textwidth}{0.4pt}

# Normalizálás

\noindent\rule{\textwidth}{0.4pt}

# Összetett lekérdezés

\noindent\rule{\textwidth}{0.4pt}

# Megvalósítás, funkciók

\noindent\rule{\textwidth}{0.4pt}