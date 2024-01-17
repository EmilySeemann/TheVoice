# Karrierewege der The Voice of Germany Kandidaten

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

# Edge-Attribute

**from**
- iniitierender Knoten, in diesem Fall: Halbfinalist/Coach einer The Voice of Germany Staffel (Staffel 1 bis 10) 

**to**
- erhaltender Knoten, in diesem Fall: Coach, Plattenlabel, Producer, Songwriter, andere TV-Shows

**relation**
- definiert die Art der Beziehung bei multiplexen Netzwerken mit verschiedenen Beziehungsarten, in diesem Fall:
  
1 = Kandidaten haben in derselben The Voice Staffel teilgenommen

2 = Coaches haben in derselben The Voice Staffel teilgenommen

3 = Coach-Kandidat-Beziehung

4 = Arbeitsverhältnis

# Node-Attribute

**id**
- eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird.

**name**
- Name oder Bezeichnung des Knotens

**type**
-  Unterscheidung des Knotentyps:

1 = Person (Kandidat, Coach, Producer, Songwriter)

2 = Organisation (Plattenlabel)

3 = Show (andere Show, wie Sing meinen Song, Reality TV, ESC, DSDS)




