# Codebuch
Wie haben sich die Karrieren der Harry Potter Schauspieler seit ihrem Debüt in der Filmreihe entwickelt?

## Inhalt 

edgelist.csv 

nodelist.csv

# EDGE-Attribute

**from**

ID der initiierenden Knoten der Schauspieler, Film, Produktionsfirma, Regisseur, Kooperation, Engagement

**to**

ID der erhaltenden Knoten Schauspieler, Film, Produktionsfirma, Regisseur, Kooperation, Engagement 

**relation**

1=Darsteller

2=Produzent

3=Regie

4=Werbepartner

5=Engagement

6=Synchronsprecher

# NODE-Attribute
**id**

IDs aus der Edgelist (from & to Spalte)

**name**

Voller Name/Bezeichnung

**type**

1=Person 

2=keine Person 

**age**

Alter des Schauspielers bei Erscheinung des Films

**year**

Erscheinungsjahr des Films

**sector**

1=Film

2=Serie

3=Werbung

4=Theater

5=Musik

6=Sonstiges

7=Darsteller

8=Regisseur

9=Produktion

(macht es Sinn hier für die Personen noch 2 Sektoren hin wie Schauspieler und Regie/Produktion?) Weil sonst kann man alle Personen gar nicht einordnen

**genre**

1=Action

2=Drama

3=Thriller

4=Horror

5=Fantasy

6=Komödie

7=Dokumentation

8=Animation

9=Sonstiges

**land**

Land aus dem Produktionsfirma kommt oder Herkunft des Films/Serie

Beispiel Abkürzung:
DE
UK
US
FR
SK


