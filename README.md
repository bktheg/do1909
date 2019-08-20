# Dortmund 1909 - 3D Modelle (Blender)

Die hier bereitgestellten Modelle gehören größtenteils zum Projekt Dortmund 1909, einem Nachbau des Markts und einer Umgebung in der Zeitschicht von 1909. Zum Teil handelt es sich aber auch um einzelne Projekte zu bestimmten historischen Gebäuden Dortmunds oder auch nur um projektierte, aber nie realisierte Bauvorhaben. Gerade diese Modelle sind in der Regel unvollständig, d.h. ich habe nur einzelne Fassaden erstellt. 
Alle hier bereitgestellten Modelle sind bereinigte Versionen der von mir selbst verwendeten. Es handelt sich nur um ausgewählte Modelle und nicht um den gesamten Dortmunder Markt mit seiner Umgebung. Die Modelle werden unregemäßig aktualisiert und um weitere Objekte ergänzt. Texturen/Materialien fehlen möglicherweise. Die Auswahl der hier veröffentlichen Modelle ist teilweise zufällig, teilweise bestimmt durch den momentanen Fertigstellungsgrad.

## Aufbau
Die Modelle sind grob nach ihrer Anschrift organisiert. Das historische Rathaus hatte die Anschrift Markt 14, das Modell findet sich also unter "3d/modelle/markt/markt 14". Allgemeine Ressourcen finden sich in der Regel unter "3d/blender/"..
Eine Ausnahme stellen die Projektmodelle dar. Diese sind aus historischen Gründen mal unter "3d" und mal unter "3d projekte" einsortiert.

## Aufbau der einzelnen Blender-Dateien
Die meisten Modelle bestehen aus einem high-poly und einem low-poly model. Ersteres ist für das Rendering in Blender bestimmt, letzteres für Echtzeitengines wie UE4. Das high-poly model befindet sich in Blender im Layer 0, das low-poly model im Layer 5. Grob gesagt ist der erste 5x2 Layerblock für high-, der zweite Block für low-poly vorgesehen. Das high-poly model ist zuden einer Gruppe zugeordnet, die der Straßenbezeichnung entspricht (z.B. "Markt 12"). Diese Gruppe wird dann in der Hauptszene mittels linking eingebunden. Daneben gibt es noch eine Vielzahl an Export_*-Gruppen. Diese dienen zum Export nach Substance Painter, um dort dann die Materialien für das low-poly model zu generieren. Die Substance Painter-Dateien werde ich nicht hier einstellen, da sie schlicht viel zu groß sind.
Manche Modelle haben evt. auch eine Beleuchtung. Die Lampen befinden sich dann in Layer 10 und sind über eine separate Gruppe in die Hauptszene einbindbar.
Sehr komplexe Modelle wie das Rathaus sind hiervon etwas abweichend (und eher "gewachsen") organisiert.

## Vorhandene Modelle (1909)
* Hiltropwall
	* Synagoge
* Markt
    * Markt 4 (Adlerapotheke)
    * Markt 10 (Krone am Markt)
    * Markt 12 (Haus zum Spiegel)
	* Markt 13
    * Markt 14 (Historisches Rathaus)
    * Markt 17
    * Markt - Kandelaber
    * Markt - Kiosk
    * Markt - Marktstand
* Schwarze Brüderstraße
    * Schwarze Brüderstraße 8 (Gasthaus zum Drachen)
    * Schwarze Brüderstraße 12
* Straßenmöblierung
    * Kleine Laterne (Markt)
    * Litfaßsäule
    * Großer Mast
* Westenhellweg
	* Westenhellweg 2
	* Westenhellweg 4
	* Westenhellweg 5
	* Westenhellweg 7

## Sonstige Modelle 
* Markt 14 - Neubauprojekt von 1891 (Wiethase)
* Nicolaikirche an der Wißstraße
* Kuckelketor
* Palenturm und Pulverturm

## Lizenz
Alle Modelle können im Rahmen der CC BY 4.0 verwendet werden.
