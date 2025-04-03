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

erweist sich bei genauerer numerischer Analyse als **nicht korrekt**. Stattdessen zeigt sich, dass der Fehlerterm 

$$
\varepsilon(n) := \sum_{k=1}^{n} \beta(k) - \log(p_n)
$$

**nicht konstant**, sondern ein **strukturierte

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

## Lizenz

Open Review | CC BY-SA 4.0

---

## Zielsetzung

Dieses Projekt verfolgt das Ziel einer **ZFC-konformen Ableitung der RH** durch modulare Operatorstruktur mit transparent dokumentierten Rechenschritten, visualisiert und überprüfbar durch Jupyter-Notebooks.

---

## Lizenz

[MIT License](LICENSE)

---

## Autor

[freese-math](https://github.com/freese-math)
