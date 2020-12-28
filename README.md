Problem:
Die Daten, die bei der Kommunikation mit einer Behörde ausgetauscht werden, sind oft gleichzeitig strukturierte Daten (Metadaten, Angaben in einem Formular), als auch unstrukturierte Daten (z.B. Textdokumente, Begründungen, Beschreibung eines Verwendungszwecks). Für die Transformation der unstrukturierten Daten in numerische Werte sind Funktionen wie das OneHotEncoding unzureichend.

Lösung:
Ein möglicher Ansatz ist die Transformation der unstrukturierten Text-Daten zu einem Vektor, wobei die einzelnen Dimensionen/Features die Ausprägungen eines „Themas“ repräsentieren. Für die Erstellung eines entsprechenden Modells genügen Daten ohne „Label“. Die Anzahl der Dimensionen/Features bzw. die Anzahl der „Themen“ kann frei definiert werden.

