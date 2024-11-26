# Reddit Topic Modeling und Analysis

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://colab.research.google.com/notebooks/basic_features_overview.ipynb](https://colab.research.google.com/github/flari-gold/IU/blob/main/IU_RedditDataAnalysis.ipynb))

Dieses Script analysiert ein angegebenes Subreddit und extrahiert daraus die diskutierten Themen und weitere Nutzer Statistiken.

## Grundsätzliche Funktionsweise

Beiträge und Kommentare eines Subreddits werden über die PRAW Library abgerufen.

Topic Modeling mit Hilfe des LDA Algorithmus. Hierbei entspricht ein Betrag und seine dazugehörigen Kommentare einem Dokument im Modell.

Ausgabe der ermittelten Themen und Nutzer Statistiken in Text und Bildform.

## Genutze Bibliotheken

PRAW

HanTa

NLTK

Gensim

pyLDAvis

Wordcloud

Matplotlib

## Nutzung

### -API
Um das Skript zu nutzen muss eine Anwendung im Reddit Developer Bereich erstellt werden. Das generierte Secret und ID müssen im Google Colab Secret hinterlegt werden oder auf andere weiße geschützt gespeichert und geladen werden.

### -Paramter
Es muss das zu analysierende Subreddit gesetzt werden. Weitere Paramtere sind ebenfalls anpassbar, falls die Standardwerte zu keinem guten Ergebnis führen.

### -Ausführung
Das Script kann in der Google Colab Umgebung ausgeführt werden. In anderen Umgebungen muss eventuell mit pip weitere Packages installiert werden.


## Anmerkung

Dieses Skript wurde während des Studiums an der IU Internationale Hochschule erstellt und dient nur zum Bildungszweck 
