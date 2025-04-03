# Riemann-Spectral-Proof

**Operator-basierter Spektralansatz zur Riemannschen Hypothese (RH)** auf Basis von Zeta-Nullstellen, Primzahllogarithmen und der rekonstruktiven Beta-Skala.

---

## Übersicht

Dieses Repository dokumentiert den modular aufgebauten Beweisrahmen für die RH, bei dem zentrale Begriffe aus Zahlentheorie, Fourier-Analyse und spektralen Operatoren verschränkt werden.

Zentrale Komponenten sind:

- **Spektraloperator \$$( D_\mu \)$$** auf diskreter Beta-Skala
- **Rekonstruktive Beta-Funktion** \$$( \beta(n) \$$)
- **Euler–Freese-Formel** als harmonisches Strukturmodell
- **Vergleich mit Liouville- und Tschebyschow-Funktion**

---

## Kernformel (Beta-Ansatz)

\$$\sum_{k=1}^{n} \beta(k) = \log(p_n) + \varepsilon(n), \quad \text{mit} \quad \varepsilon(n) \not\equiv \text{konstant}
\$$

> **Hinweis zur Präzision der Näherung**

Die ursprüngliche Näherung

$$
\sum_{k=1}^{n} \beta(k) \approx \log(p_n) + \varepsilon \quad \text{mit} \quad \varepsilon \approx 15{,}88
$$

erweist sich bei genauerer numerischer Analyse als **nicht korrekt**. Stattdessen zeigt sich, der Fehlerterm

$$
\varepsilon(n) := \sum_{k=1}^{n} \beta(k) - \log(p_n)
$$

als **nicht konstant**, sondern, dass er ein **strukturierter Ausdruck mit spektraler Signatur** ist. Er lässt sich durch harmonische Komponenten und Operatoren wie T₍ᵦ₎ analysieren und ist somit **kein Zufall**, sondern ein Schlüssel zur tieferen Struktur im Kontext der Riemannschen Hypothese.

\$$
\beta(n) = \frac{A}{n^p} + \sum_{k=1}^{K} A_k \cdot \sin(2\pi f_k n)
\$$

Diese Formel beschreibt die harmonische Struktur der rekonstruierten Beta-Werte und lässt sich spektral analysieren.

---

## Module

| Modul | Inhalt |
|-------|--------|
| [`paper/modul_1_begriffe.md`](paper/modul_1_begriffe.md) | Grundbegriffe & Operatorstruktur |
| [`paper/modul_2_struktur.md`](paper/modul_2_struktur.md) | Spektrale Dirac-Struktur |
| [`paper/modul_3_operator.md`](paper/modul_3_operator.md) | Konstruktion des Operators \( D_\mu \) |
| [`paper/modul_4_nova_zeta.md`](paper/modul_4_nova_zeta.md) | Definition der Zeta Nova Freesiana |
| [`paper/modul_5_validierung.md`](paper/modul_5_validierung.md) | Numerische Gegenproben & Residuen |

---

## Visualisierung

Beispielhafte Darstellung der spektralen Driftstruktur der Beta-Skala:

![BetaSkala](viz/beta_plot.png)

# Riemann Spectral Proof

Dieses Projekt untersucht die Riemannsche Hypothese aus spektraler Sicht – mit Operatoren, Primzahlskalen und der rekonstruktiven Beta-Struktur.

## Einstieg

- [Kernstruktur & Theorie (index.ipynb)](https://nbviewer.org/github/freese-math/riemann-spectral-proof/blob/main/index.ipynb)

## Inhalte

- Harmonische Rekonstruktion der Beta-Funktion
- Operatorstruktur ($\\mathcal{T}_\\beta$)
- Spektrale Filterung
- Vergleich mit Odlyzko-Nullstellen
- Integration der Zeta Nova Freesiana

---

## Zielsetzung

Dieses Projekt verfolgt das Ziel einer **ZFC-konformen Ableitung der RH** durch modulare Operatorstruktur mit transparent dokumentierten Rechenschritten, visualisiert und überprüfbar durch Jupyter-Notebooks.

---

## Lizenz und Nutzung

Die zugrunde liegenden Formeln, Konzepte und der spektrale Operatoransatz unterliegen dem Urheberrecht und sind seit dem 28. Februar 2025 notariell beurkundet durch:

**Notariat Lindwehr**  
Münsteraner Straße 2, 49809 Lingen (Ems)  
Tel: +49 (0) 591 31 96 29 - 00  
E-Mail: info@lindwehr.com
Web: [www.lindwehr.com](https://www.lindwehr.com/kontakt/)

sowie anwaltlich vertreten durch:

**Kanzlei Schulte und Partner – RA Michael Lito Schulte**  
Kaiser-Wilhelm-Ring 43a, 40545 Düsseldorf  
Wilhelmshofallee 72, 47800 Krefeld  
Tel: +49 (0) 211 55 86 4 – 00  
E-Mail: l.schulte@lawplus.de
Web: [lawplus.de](https://lawplus.de/)

### Nutzungsbedingungen:
- Dieses Repository folgt dem Prinzip der **Open Science**: Die Forschung darf **frei eingesehen, getestet und weiterentwickelt** werden.
- **Kommerzielle Nutzung**, **Veröffentlichungen** oder **mediale Verarbeitung der Inhalte** bedürfen jedoch der **ausdrücklichen schriftlichen Zustimmung** des Autors.
- Grundlage ist ein ethischer Kodex, der sich an humanistischen Prinzipien orientiert.

Bitte bei Anfragen zur Nutzung oder Lizenzierung Kontakt aufnehmen.



---

## Autor

[freese-math](https://github.com/freese-math)
