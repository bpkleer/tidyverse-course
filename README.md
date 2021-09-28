# Herzlich Willkommen!

Hier finden Sie alle weiterführenden Kursmaterialien zum Workshop "Daten bändigen und visualisieren in R" an den Methodentagen 2021 (Justus-Liebig-Universität Gießen).

## Zugriff auf die Dateien
Entweder *forken* Sie das Repository, *pullen* die Dateien über ihre lokale git-Installation oder laden die Dateien per ZIP (Button neben *Clone*) herunter, um sie lokal zu öffnen. Der Kurs ist in RStudio Cloud auch als Projekt angelegt, und darüber können die Dateien ebenfalls heruntergeladen werden.

## Aufbau des Workshop
Am Vormittag werden wir gemeinsam grundlegende Funktionen in **tidyverse** kennenlernen und insbesondere mit den Paketen **tidyr**, **dplyr** und **ggplot** arbeiten. Am Nachmittag können eigene Interessenschwerpunkte ausgewählt werden.

### Übersicht Vormittag
| Thema  | Html-/Rmd-File |
|---|---|
| Einführung **dplyr**   |dplyr-grammar.html/.Rmd |
| Datensätze formatieren  |tidyr-grammer.html/.Rmd   |
|Einführung **ggplot**  |ggplot-grammer.html/.Rmd   |

### Übersicht Nachmittag
Am Nachmittag können die Workshopteilnehmende eigene Schwerpunkte wählen und sich mit einem der Themenfelder genauer beschäftigen:

| Schwerpunkt  | Html-/Rmd-File |
|---|---|
|**ggplot** advanced  |ggplot-advanced.html/.Rmd   |
|Textdaten mit **stringr**   |stringr-grammar.html/.Rmd   |
|Tabellen publizieren mit **gt** | gt-grammar.html/.Rmd |
|if-Ausdrücken, Schleifen & Funktionen   |if-loops-functions.html/.Rmd |

### Übungsaufgaben
Zu den Themen am Vor- und am Nachmittag finden sich in der RStudio Cloud Übungsaufgaben. Die RStudio Cloud steht Teilnehmer:innen bis zum 31. Oktober 2021 zur Verfügung. Die Inhalten können auch von dort heruntergeladen werden.

## Running RMDs
Um die *.rmd*-Dateien durchlaufen lassen zu können, muss man die Pakete `xaringan` und `xaringanExtra` installieren.

Hierzu müssen folgende Zeilen ausgeführt werden:

```{r}
# install.packages("remotes")
remotes::install_github("yihui/xaringan")

# install.packages("devtools")
devtools::install_github("gadenbuie/xaringanExtra")

```

Für die Darstllung von Tabellen wird dazu noch das Paket `DT` und `icons` benötigt:

```{r}
install.packages(c("DT","icons"), dependencies = TRUE)
```

