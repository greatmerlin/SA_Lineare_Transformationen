# Semesterarbeit LinAlg: *Lineare Transformationen*

## Aufgaben

- Schreiben Sie ein Jupyter Notebook -> das die Funktion der **zweidimensionalen linearen Abbildungen illustriert.**

- Im Notebook sollte eine Python-Funktion definiert werden
   die als Argument eine Abbildungsmatrix einer zweidimensionalen linearen Abbildung benötigt  
   als optionale Argumente sollten Wertebereiche für die x-Werte und die y-Werte angegeben werden können.  

### Die Funktion sollte dann **eine Graphik** erzeugen mit folgenden Elementen:

1. Gitterlinien des Koordinatensystems (Parallele zu den x- und y-Achsen.
2. Ein Kreis mit Radius 1 und Zentrum in Koordinatenursprung ((0,0)).
3. Ferner sollen die Bilder der Elemente aus 1 und 2 unter der angegebenen Abbildungsmatrix eingezeichnet werden.  


- Das Notebook sollte dann einige Beispiele (mind. 3, einschliesslich einer Komposition) für verschiedene Abbildungsmatrizen enthalten, insbesondere für Dreh-, Spiegelungs-, Scherungs-, Streckungs- und Projektionsmatrizen sowie für Kompositionen davon.

- In einem **Theorieteil** sollten der Begriff der linearen Abblidung sowie die Darstellung von linearen Abbildungen durch Matizen beschreiben werden. Gehen Sie auch auf die Anwendungen der linearen Transformationen ein.

* **Hinweis zur Darstellung des Kreises**  
Das Bild eines Kreises unter linearen Abbildungen ist nicht ganz einfach zu bestimmen.  
Es empfielt sich daher, den Einheitskreis durch ein reguläres Vieleck (z.B. mit 500 Ecken) zu ersetzen. Die Koordinaten einer Ecke sind (cos(φ),sin(φ), wobei φ Winkel zwischen 0 und 2π durchlaufen muss. Die Koordinaten der Ecken können in einem numpy-Array K als Spalten abgelegt werden; das Bild des Vielecks unter einer Abbildung mit Darstellungsmatrix M ist dann M@K.* 
