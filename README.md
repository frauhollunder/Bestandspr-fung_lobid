# Bestandspr-fung_lobid
Anhand der ISBN kann geprüft werden, ob es Bestand in einer Bibliothek gibt.

1. Den Namen der Eingabedatei eingeben (Excel mit einem Blatt)
2. Das Sigel der besitzenden Bibliothek eingeben
3. Den Name der ISBN-Spalte anpassen an 5 Stellen (am Besten mit replace austauschen)


wenn man eine csv hat, dann kopiert man statt 
pd.read_excel('Eingabedatei.xlsx')
pr.read_csv ('Eingabedatei.csv', sep=';')

bei sep= kann man den Seperator der vorliegenden Datei angeben
