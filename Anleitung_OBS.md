---
tags: KIT_corona, Anleitung
---
![](https://i.imgur.com/eAg9Fgb.png)

# Videos mit Open Broardcaster Software aufnehmen 
```
letzte Aktualisierung: 31.03.2020
```
Wenn Sie ihre Lehrinhalte in digitaler Form auf Ihrem Computer vorliegen haben, können Sie einen Vortrag und diesen digitalen Inhalten mit einer speziellen Broardcaster Software aufzeichnen. Diese Anleitung zeigt, welche Schritte in Open Broardcaster Software (OBS) dafür nötig sind.

#### Übersicht
[TOC]

---

:::warning
Wichtige Hinweise sind gelb gekennzeichnet.
:::

:::info
Zusatzinformationen sind blau gekennzeichnet.
:::

---

### Benötigte Ausstattung
* PC oder Mac mit:
    * Mikrofon (am besten ein Headset) 
    * optional: (integrierte) Webcam
* Open Broadcaster Software (OBS)
* Ihre Lehrinhalte in digitaler Form

## Schritt 1: OBS installieren
1. Bitte laden Sie sich OBS von der offiziellen Webseite: [OBS herunterladen](https://obsproject.com)
:::info
OBS ist eine Open Source Software, die es für alle gängigen Betriebssysteme gibt: Windows, macOS und Linux.
:::
2. Installieren Sie OBS auf Ihrem Computer. Ggf. müssen Sie hierzu Ihren ITB bzw. Administrator um Hilfe bitten, sofern Ihr eigener Benutzeraccount nicht über die dafür notwendigen Rechte verfügt.
    * Sie brauchen keine zusätzlichen Plugins installieren.

## Schritt 2: OBS konfigurieren

1.	Führen Sie den Autokonfigurationsassistenten durch, den OBS nach dem ersten Starten anbietet.
![](https://i.imgur.com/XbxBcDl.jpg)
3.	Wählen Sie aus, dass sie vornehmlich **aufzeichnen** wollen.
![](https://i.imgur.com/PH7F3ho.jpg)
4.	Geben Sie für die Basis-(Leinwand)-Auflösung bitte 1280x720 an. Für die FPS (Frames per Second) 30. 
![](https://i.imgur.com/mjukTGW.jpg)
* **Je nach Betriebssystem** testet OBS anschließend ihr System und prüft dabei, ob die gewählten Einstellungen mit der Leistung Ihres Computers funktionieren:
![](https://i.imgur.com/86Q0k8S.jpg)
4. Wenden Sie die Einstellungen an.
![](https://i.imgur.com/NS1RhCC.jpg)

:::danger
Sollten Sie an dieser Stelle eine Fehlermeldung erhalten, kontaktieren Sie bitte das ZML.
:::


## Schritt 3: Aufnahme einrichten
1. Wählen Sie unter „Quellen” mit einem Klick auf das Plus-Symbol „Bildschirmaufnahme”
![](https://i.imgur.com/4C9vjZp.jpg)
2. Wählen Sie den Monitor, dessen Bildschirminhalt Sie aufzeichnen möchten. Wenn Sie nur einen Monitor haben, wird in der Auswahlliste nur eine Quelle angezeigt.
![](https://i.imgur.com/9SFSYgO.jpg)

:::warning
### Zusätzliche Einstellungen unter macOS:

Sie müssen der Software OBS über die Systemeinstellungen erlauben, Bildschirmaufnahmen anzufertigen. Die Einstellung finden Sie unter

**Systemeinstellungen - Sicherheit - Datenschutz.**

![](https://i.imgur.com/SsiuQ2y.jpg)

![](https://i.imgur.com/1E9HPvM.jpg)
:::

4.	Wenn Ihr Bildschirm eine höhere Auflösung hat als die Basis-Leinwand, müssen Sie den Bildschirm (virtuell) verkleinern, indem Sie an den roten Rahmen um das Bild skalieren, bis es in die Leinwand passt.
![](https://i.imgur.com/b3XdPZa.jpg)

* Fassen Sie dazu die roten Kontrollpunkte an, das Seitenverhältnis des Bildes wird dabei nicht verändert.
:::warning
* Sollten Sie nur den oberen linken Punkt sehen, können Sie diesen in die Mitte der Leinwand ziehen und danach mit einem Klick mitten in das Videobild den Bildschirminhalt neu positionieren. Wiederholen Sie dieses Vorgehen solange, bis Sie alle Kontrollpunkte sehen und den Bildschirminhalt korrekt in die Leinwand eingepasst haben!
* Die Leinwand hat ein Seitenverhältnis von 16:9. Einige Notebooks haben eine Monitor-Seitenverhältnis von 16:10 – Sie müssen dann also etwas vom oberen/unteren Ende „abschneiden”. 
:::

![](https://i.imgur.com/ypjgZOE.jpg)

5.	Öffnen Sie die **Einstellungen** 
![](https://i.imgur.com/VxDH7Pb.jpg)
6. Wählen Sie unter dem Reiter „Ausgabe”:
    * den Ausgabepfad, wo Sie die Aufnahmen abspeichern wollen. OBS nimmt Datum und Uhrzeit automatisch als Dateinamen.
    * die Aufnahmequalität **Hohe Qualität, mittelgroße Dateien**
    * das Ausgabeformat **mp4**
![](https://i.imgur.com/0jVMp1E.jpg)
6. Speichern Sie die Einstellungen mit einem Klick auf den Button **Okay**
7.	Im Audio-Mixer sollte Ihr Mikrofon / Headset zu sehen sein. Deaktivieren Sie ggfs. alle anderen Signalquellen, es sei denn Sie möchten ein Video mit Ton in Ihrer Präsentation abspielen (dann muss Desktop-Audio aktiviert werden).
![](https://i.imgur.com/jQW5Tjo.jpg)
8.	Testen Sie eine kurze Aufnahme ob alles nach Ihrer Vorstellung funktioniert
![](https://i.imgur.com/DJiQKua.jpg)

## Schritt 4: Weitere Aufnahmequellen hinzufügen
Sie können weitere Bildquellen für Ihre Aufnahme hinzufügen, z.B. eine Webcam oder einen zweiten Bildschirm. Beachten Sie dabei, dass Ihnen nur eine Leinwand zur Verfügung steht, auf denen Ihre Inhalte dargestellt werden. Sollte Schrift gut lesbar sein, stellen Sie bitte sicher, dass die Schriftgröße entsprechend gewählt ist.

**Für das Beispiel einer zusätzlichen Webcam**: 
1. Fügen Sie unter „Quellen” eine Weitere Quelle hinzu.
2. Wählen Sie „Videoaufnahmegerät”.
![](https://i.imgur.com/Du6MoN9.jpg)
3. Benennen Sie die Quelle für Ihr Aufnahmesetting. Diese Benennung dient ausschließlich dazu, die Quellen in OBS zu organisieren.
![](https://i.imgur.com/9TaDr9Z.jpg)
4. Wählen Sie im Auswahlfeld „Gerät” Ihre Webcam aus.
![](https://i.imgur.com/imQJ6HT.jpg)
5. Skalieren und positionieren Sie das Bild der Webcam auf Ihrer Leinwand wie Sie es bereits mit Ihrem Bildschirminhalt getan haben.
![](https://i.imgur.com/mK1FJGW.jpg)

:::danger
* Sollten Sie mehrere Bildquellen aufzeichnen, postitionieren Sie sie so, dass keine Inhalte der jeweils anderen Quelle verdeckt werden!
:::

## Einige Tipps
* Nehmen Sie keine 90 Minuten Vorlesung am Stück auf! Unterteilen Sie die Aufnahmen in **kleinere Abschnitte von etwa 10-20 Minuten**. So können Sie sich jedes Mal neu sammeln, Pausen einlegen und müssen bei Fehlern nicht alles neu aufzeichnen.
* Sie sollten nach Möglichkeit **frei und nicht zu leise sprechen**. Stellen Sie sich vor die Studierenden säßen Ihnen gegenüber: Verwenden Sie eine direkte Ansprache und **vermeiden Sie lange und komplexe Sätze**.
* OBS speichert Dateien mit Datum und Uhrzeit als Dateinamen. Benennen Sie die Videodateien auf Ihrem Computer nach einer einheitlichen Nomenklatur um und organisieren Sie sie in einer durchdachten Ordnerstruktur. Das hilft Ihnen, die einzelnen Lerneinheiten später besser wiederzufinden und bereitzustellen. 


## Nächste Schritte
* Wie Sie die Aufnahmen für den Upload vorbereiten und dafür möglichst kleine Dateien bei gleichbleibender Qualität erzeugen, zeigt diese Anleitung: [Anleitung zu Videokomprimierung](https://s.kit.edu/tutorial-videokomprimierung).
* Wie Sie die Aufnahmen Ihren Studierenden über ILIAS bereitstellen, erfahren Sie in einer gesonderten Anleitung.



---
## Infos & Kontakt

### Lizenzhinweis
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Diese Anleitung für die Erstellung von digitalem Lehrmaterial</span> des <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Zentrum für Mediales Lernen (ZML) am Karlsruher Instituts für Technologie (KIT)</span> ist lizenziert unter einer <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Namensnennung 4.0 International Lizenz</a>.

### Impressum

**Herausgeber**
Karlsruher Institut für Technologie (KIT)
Kaiserstraße 12
76131 Karlsruhe

**Kontakt**
Karl-Friedrich-Str. 17
76133 Karlsruhe
Deutschland
Tel.: +49 721 608-48200
Fax: +49 721 608-48210
E-Mail: info@zml.kit.edu
