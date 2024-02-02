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

3 = Kandidat-Kandidat-Beziehung (Kandidaten haben in der gleichen Staffel teilgenommen)

4 = Coach-Kandidat-Beziehung

5 = Arbeitsverhältnis

**time**
- Wann hatten die Akteure (impliziert auch Shows) das erste Mal miteinander Kontakt?

1 = erstes Jahr nach Beendigung der Show

2 = im zweiten und dritten Jahr nach Beendigung der Show

3 = nach vier Jahren nach Beendigung der Show

# Node-Attribute

**id**
- eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.

**name**
- Name oder Bezeichnung des Knotens

**type**
-  Unterscheidung des Knotentyps:

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










