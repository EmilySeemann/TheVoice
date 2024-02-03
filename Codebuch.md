# Karrierewege der The Voice of Germany FinalistInnen

## Welche Verbindungen bestehen zwischen den FinalistInnen und anderen KünstlerInnen, ProduzentInnen, SongwriterInnen, Labels und/oder anderen Shows?

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

# Edge-Attribute

**from**
- iniitierender Knoten, in diesem Fall: Finalist/Coach einer The Voice of Germany Staffel (Staffel 1 bis 13), Staffel/TV-Show 

**to**
- erhaltender Knoten, in diesem Fall: Coach, Plattenlabel, Producer, andere Sänger(mit denen die Kandidaten an einem Lied beteiligt waren), andere TV-Shows

**relation**
- definiert die Art der Beziehung bei multiplexen Netzwerken mit verschiedenen Beziehungsarten, in diesem Fall:

1 = Person hat als Kandidat teilgenommen (gilt sowohl für The Voice, als auch für andere Shows) 

2 = Person hat als Coach teilgenommen (gilt sowohl für The Voice, als auch für andere Shows) 

3 = Kandidat-Kandidat-Beziehung (Kandidaten haben in der gleichen Staffel einer selben Show teilgenommen)

4 = Coach-Kandidat-Beziehung

5 = Arbeitsverhältnis

**year**
- Wann hatten die Akteure (impliziert auch Shows) ab The Voice das erste Mal miteinander Kontakt?
- Jahreszahl wird mit vier Ziffern angegeben 


# Node-Attribute

**id**
- eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird:
- ID setzt sich zusammen aus dem ersten Buchstaben des Vor- und Nachnamens (z.B. Michael Schulte: ms)
- Wenn es die ID schon gibt setzt sich die ID aus den ersten zwei Buchstaben des Vornamens und dem ersten Buchstaben des Nachnamens zusammen (z.B. Max Herre: mah)
- Wenn der Name nur aus einem Wort besteht, dann werden die ersten drei Buchstaben des Wortes verwendet (z.B. Nena: nen)
- Plattenlabels werden immer mit den ersten drei Buchstaben des ersten Wortes identifiziert (z.B. Motor Music: mot)
- Shows werden immer mit den ersten vier Buchstaben des ersten Wortes identifiziert (z.B. The Voice Kids: thev)

**name**
- Name oder Bezeichnung des Knotens

**type**
-  Unterscheidung des Knotentyps (wir beziehen uns hier auf die Rolle, die die jeweilige Person in unserem Netzwerk als erstes hatte):

1 = Kandidat 

2 = Organisation (Plattenlabel)

3 = Show (The Voice of Germany, andere Show, wie Sing meinen Song, Reality TV, ESC, DSDS)

4 = Coach 

5 = Andere (zum Beispiel Producer, andere Sänger, Songwriter)

6 = Staffel

**sex**
-  Geschlecht der Akteure:

1 = weiblich

2 = männlich 

3 = divers (gilt auch für gemischte Teams)

**staffel**
- In welcher Staffel hat der Kandidat/Coach teilgenommen (Staffel 1 bis 13)

**showkategorie**
- Um welche Art von Show handelt es sich?

1 = Musikshows (The Voice Kids, ESC, Sing meinen Song, The Masked Singer, DSDS)

2 = Realityshows (Are you the one, Love Island, Bachelor/Bachelorette, Ex on the Beach, Dschungelcamp, etc... 

3 = Fernsehen/Film (Schauspiel)

**charts**
- Wie viele Songs waren in den deutschen Charts?

1 = 0 Songs in den deutschen Charts

2 = 1-3 Songs in den deutschen Charts

3 = 4-6 Songs in den deutschen Charts

4 = Mehr als 6 Songs in den deutschen Charts

**platz**
- Welchen Platz hat der Kandidat im Finale belegt?

1 = Platz 1

2 = Platz 2

3 = Platz 3

4 = Platz 4 

5 = Platz 5 










