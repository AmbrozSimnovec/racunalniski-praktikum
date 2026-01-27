# Računalniški praktikum
Ctrl + Shift P = Odpri bližnjice / ukazna vrstica
Ctrl + Tab = Naslednji zavihek (Tab)
Alt + Tab = Odpri okno z zavihki
Alt + W = Zapri zavihek
Alt + F4 = Zapri vse
Ctrl + Z= Undo
Ctrl + S = Save
Ctrl + F = Iskanje besed VScode
Shift + Home = Označi celo vrstico nazaj
Shift + End = Označi celo vrstico naprej
Home ali End = Na začetek ali konec vrstice
Ctrl + Home ali End = Na začetek ali konec besedila
Ctrl + K Ctrl + O = Zamenjaj repozitorij
Ctrl + Shift + M = Problems VSCode
Ctrl + Alt + X = Latex commands
Ctrl + Delete = Delete v desno
Ctrl + Shift + V = opoen preview html
Alt + Z = koda ne gre pod preview
Ctrl + R = osveži brskalnik
Ctrl + Alt + R = hard refresh

Ukazi:
    HTML:
    Wrap
    Format document = poravna razdelke

    LATEX:
    Surround
    \qquad - presledek

REGEX - Na browserju, da vidiš kaj delaš

Ruslan rešitve link: github.com/iruspro/rp


Prehajanje med izvorno kodo v .tex datoteki in PDF datoteko v VSCode:   
    Windows:
        iz .tex v PDF:
            Ctrl + Alt + J
    
        iz PDF v .tex:
            Ctrl + klik


EXCEL:
Ctrl + Shift + down = Označi cel stolpec
Ctrl + A = Označi vse polne celice

LATEX:
simbol v command (Deexify)
https://detexify.kirelabs.org/classify.html

Prikazni način:
\[...\], ali $$...$$
Vrstični način:
\(...\) ali $...$



\theoremstyle{stil npr. plain}
\newtheorem{envirnment name}{Printed text}[section = resetira oštevilčenje za vsako sekcijo]

\newcommand{\command}[število argumentov, ki jih lahko sprejme, optional][default = če ne vstaviš argumenta latex vstavi default arg., optional]{kaj bo pisalo namesto \command}

\input{datoteka} ukaz za vključevanje vsebine druge .tex datoteke v trenutno datoteko.

\begin{array}{c|c|c|c}

\begin{itemize}
    \item ...
    \item ...

\begin{magic}{Magični kvadrat reda 3}{table:mag3}{3}
   8 & 1 & 6 \\ \hline
   3 & 5 & 7 \\ \hline
   4 & 9 & 2 \\ \hline
\end{magic}


%konec dokumenta%
\bibliographystyle{stil}

%datoteka za Bibtex%
\bibliography{magic.bib}


\usepackage{...}
| Paket                  | Namen                                              |
| ---------------------- | -------------------------------------------------- |
| `amsmath`              | napredna matematična okolja                        |
| `amssymb`              | dodatni matematični simboli                        |
| `amsthm`               | izreki, definicije, dokazi                         |
| `hyperref`             | klikalni sklici in povezave v PDF                  |
| `booktabs`             | profesionalne tabele                               |
| `graphicx`             | vstavljanje slik                                   |
| `tikz`                 | risanje diagramov in slik                          |
| `pgfplots`             | grafi funkcij in podatkov                          |
| `natbib`               | citiranje (author–year ali numerično)              |
| `biblatex`             | sodobno upravljanje bibliografije                  |
| `biblatex + biber`     | napredna bibliografija (priporočeno)               |
| `cite`                 | izboljšani numerični citati                        |
| `url`                  | pravilni prelomi URL-jev (pogosto že v `hyperref`) |
| `array`                | custom matrike, {c|c|c}                            |


| Ukaz / Okolje                  | Kratek opis lastnosti |
|--------------------------------|---------------------|
| `\title{...}`                  | Določi naslov dokumenta |
| `\author{...}`                 | Določi avtorja dokumenta |
| `\date{...}`                   | Določi datum dokumenta |
| `\maketitle`                   | Ustvari naslovno stran z naslovom, avtorjem in datumom |
| `\input{file}`                 | Vključi vsebino druge LaTeX datoteke |
| `\begin{abstract}...\end{abstract}` | Povzetek dokumenta |
| `\tableofcontents`             | Ustvari kazalo vsebine |
| `\section{...}`                | Ustvari glavni razdelek |
| `\subsection{...}`             | Ustvari podrazdelek |
| `\subsubsection{...}`          | Ustvari še manjši podrazdelek |
| `\emph{...}`                   | Poudari besedilo (po navadi ležeče) |
| `\textbf{...}`                 | Naredi besedilo krepko |
| `\textit{...}`                 | Naredi besedilo ležeče |
| `\texttt{...}`                 | Besedilo v tipkovni pisavi (monospace) |
| `\verb|...|`                    | Neposredno vključi besedilo brez obdelave LaTeX ukazov |
| `\url{...}`                     | Vključi URL povezavo |
| `\noindent`                     | Odstrani zamik prve vrstice |
| `\centering`                    | Poravna besedilo ali elemente na sredino |
| `\begin{center}...\end{center}` | Poravna besedilo ali elemente na sredino (okolje) |
| `\begin{verbatim}...\end{verbatim}` | Prikaže besedilo nespremenjeno, vključno z ukazi |
| `\begin{itemize}...\end{itemize}` | Ustvari seznam z oznakami (bullet points) |
| `\begin{enumerate}...\end{enumerate}` | Ustvari oštevilčen seznam |
| `\item`                         | Doda posamezen element seznama |
| `\begin{table}...\end{table}`  | Ustvari tabelo z opisom in pozicioniranjem |
| `\begin{tabular}...\end{tabular}` | Ustvari tabelo z določenim številom stolpcev |
| `\hline`                        | Vstavi horizontalno črto v tabeli |
| `\toprule`                      | Vstavi zgornjo črto (booktabs paket) |
| `\midrule`                      | Vstavi sredinsko črto (booktabs paket) |
| `\bottomrule`                   | Vstavi spodnjo črto (booktabs paket) |
| `\multicolumn{n}{alignment}{...}` | Združi n stolpcev v tabeli |
| `\begin{figure}...\end{figure}` | Ustvari plavajočo sliko z opcijami za oznake in pozicioniranje |
| `\includegraphics{file}`       | Vključi grafično datoteko (sliko) |
| `\begin{tikzpicture}...\end{tikzpicture}` | Ustvari TikZ diagram (risbo) |
| `\label{...}`                   | Doda oznako za kasnejše sklice |
| `\ref{...}`                     | Sklic na oznako (številka razdelka, tabele, slike) |
| `\eqref{...}`                   | Sklic na enačbo s številko v oklepajih |
| `\pageref{...}`                 | Sklic na stran, kjer se oznaka nahaja |
| `\cite{...}`                     | Vstavi citat iz bibliografije |
| `\nocite{...}`                   | Vključi citat v bibliografijo, tudi če ni sklican v besedilu |
| `\bibliographystyle{...}`        | Določi slog bibliografije (npr. plain, unsrt) |
| `\bibliography{file}`            | Vključi bibliografijo iz datoteke `.bib` |


| Ukaz / Okolje             | Namen / Primer                                                                |
|---------------------------|-------------------------------------------------------------------------------|
| `\usetheme{tema}`         | Nastavi Beamer temo (`\usetheme{Madrid}`)                                     |
| `\begin{frame}{Naslov}...\end{frame}` | Nov okvir / slide                                                 |
| `\titlepage`              | Prikaže naslovnico                                                            |
| `\begin{block}{Naslov}...\end{block}` | Standardni blok (`\begin{block}{Definicija}...`)                  |
| `\begin{exampleblock}{Naslov}...\end{exampleblock}` | Blok za primere                                     |
| `\begin{alertblock}{Naslov}...\end{alertblock}` | Blok za opozorila                                       |
| `\pause`                  | Postopno odkrivanje vsebine po vrstah                                         |
| `\onslide<spec>`          | Prikaže vsebino le na določenih slide-ih (`\onslide<2->{Vsebina}`)            |
| `\only<spec>{...}`        | Prikaže vsebino le na določenih slide-ih, ne vpliva na layout                 |
| `<spec>`                  | Specifikacija za postopno odkrivanje (`<+->` na seznamih)                     |
| `\begin{columns}...\end{columns}` | Ustvari stolpce                                                       |
| `\column{width}`          | Določa širino posameznega stolpca (`\column{0.5\textwidth}`)                  |



| Kategorija | Ukaz | Kratek opis | Primer |
|------------|------|-------------|--------|
| **Posebni prikazi** |
| | `\frac{a}{b}` | Ulomek | $\frac{a}{b}$ |
| | `\sqrt{x}` | Kvadratni koren | $\sqrt{x}$ |
| | `\binom{n}{k}` | Binomski koeficient | $\binom{n}{k}$ |
| | `\begin{cases} ... \end{cases}` | Funkcija po primerih | $\begin{cases} x^2,& x\ge0\\ -x,& x<0\end{cases}$ |
| | `\begin{matrix}...\end{matrix}` | Matrika brez oklepajev | $\begin{matrix}1 & 2\\3 & 4\end{matrix}$ |
| | `\begin{pmatrix}...\end{pmatrix}` | Matrika z okroglimi oklepaji | $\begin{pmatrix}1 & 2\\3 & 4\end{pmatrix}$ |
| | `\begin{bmatrix}...\end{bmatrix}` | Matrika z oglatimi oklepaji | $\begin{bmatrix}1 & 2\\3 & 4\end{bmatrix}$ |
| **Vgrajene funkcije** |
| | `\sin, \cos, \tan` | Trig. funkcije | $\sin x, \cos y$ |
| | `\log, \ln, \exp` | Logaritmi in eksponent | $\log x, \ln y, \exp(z)$ |
| | `\lim, \sup, \inf` | Limite in ekstremi | $\lim_{x\to0} f(x), \sup A$ |
| | `\max, \min` | Maksimum in minimum | $\max(x,y), \min(a,b)$ |
| **Prikazna okolja** |
| | `equation` | Enačba s številko | $$E=mc^2$$ |
| | `equation*` | Enačba brez številke | $$E=mc^2$$ |
| | `align` | Poravnane enačbe, več vrstic | $$\begin{align}a&=b+c\\d&=e+f\end{align}$$ |
| | `align*` | Poravnane enačbe brez številk | $$\begin{align*}a&=b+c\\d&=e+f\end{align*}$$ |
| | `multline` | Enačba čez več vrstic | $$\begin{multline}a+b+c+d+e\\+f+g+h\end{multline}$$ |
| | `multline*` | Enačba čez več vrstic brez številk | $$\begin{multline*}a+b+c+d+e\\+f+g+h\end{multline*}$$ |
| **Pisave** |
| | `\mathsf{ABC}` | Sans-serif | $\mathsf{ABC}$ |
| | `\mathtt{ABC}` | Monospace | $\mathtt{ABC}$ |
| | `\mathrm{ABC}` | Rimljanska | $\mathrm{ABC}$ |
| | `\mathbb{R}` | Blackboard bold (številčne množice) | $\mathbb{R}, \mathbb{Z}, \mathbb{Q}$ |
| | `\mathcal{F}` | Kaligrafske črke | $\mathcal{F}, \mathcal{L}$ |
| **Besedilo v matematičnem načinu** |
| | `\text{Besedilo}` | Vstavi besedilo | $\text{če } x>0\text{, potem } y>0$ |


dopolni README

file:///C:/Users/as81000/RP/racunalniski-praktikum/03-html/stran.html