# Einleitung

Die Verwendung der Clouddienste bei m4models erfolgt mit drei verschiedenen Anwendungen, denen im Arbeitsfluss jeweils unterschiedliche Aufgaben zukommen.

- Verwendung der Direktverbindung über ein **[Netzlaufwerk](netzlaufwerk.md)** im Windows Explorer
- Verwendung von **[WinSCP](winscp.md)**
- Verwendung der **[Website](website.md)**

# Begiffe #

**NAS** (Network Attached Storage, Netzwerkspeicher) ist das Ding im Keller, das in Hamburg auf den Namen NAS-M4 hört (in Berlin auf LG NAS und UCS), und auf das ihr bis vor kurzem fast alles abgespeichert habt.

**Cloud** ist der Speicherbereich im Internet, den ihr jetzt hauptsächlich benutzen sollt und den ihr über drei verschiedene Methoden ansprechen könnt:

1. Per **Netzlaufwerk:** Nach Eingabe von Name und Passwort in das „Verbinden mit m4models Cloud“-Programm habt ihr ein Laufwerk mit dem Buchstaben O, das sich in Windows integriert. Das ist das Netzlaufwerk.

2. Mit **WinSCP (über die Verknüpfung OwnCloudSCP)**: Dieses ist eine Software zum Hoch- und Herunterladen von Dateien auf einen – bzw. von einem – Webserver. Nicht mehr und nicht weniger.

3. Über die **Web-Oberfläche**, die ihr in eurem Browser unter [http://www.m4models-cloud.de/](http://www.m4models-cloud.de) erreicht.

# Vorweg #

Die Cloud ist nur Teilweise ein Ersatz für das NAS, auf die Ihr bis jetzt eure Dateien gespeichert habt. Sie übernimmt einen Teil der Aufgaben, weil sie diesen Teil besser macht, als das NAS. Andere Aufgaben müssen anders gelöst werden.

Ich werde zuerst erklären, was ihr mit der Cloud alles nicht machen solltet.

Als zweites – oder damit verschränkt - werde ich erklären, wie ihr die Cloud sinnvoll verwendet.

Und als drittes, wie ihr die Sachen, die mit der Cloud nicht gehen, stattdessen machen könnt.

# Grundsätzliches #

Ihr solltet euch darüber im Klaren sein, dass alle Dateien, die ihr auf die Cloud speichert, ins Internet hochgeladen werden. Es ist also in etwa so, als ob ihr sie mit WeTransfer oder per Email verschickt. Natürlich ist das langsamer, als das Speichern auf das NAS und erfordert Anpassungen eures Arbeitsablaufs. Es folgt daraus zum Beispiel:

### Die Cloud ist der geeignete Ort… ###

- für Dateien, die **gebrauchsfertig** sind.

Gebrauchsfertig heißt, sie sind auf die **richtige Größe** gebracht, **vernünftig benannt** und **fertig**, um sie an Kunden zu verteilen. Außerdem für **Dokumente** wie Word, PDF o.ä., auf die alle in eurer Firma zugreifen können sollen.

### Die Cloud ist nicht der geeignete Ort… ###

- für Dateien, die noch stark **bearbeitet werden** müssen
- für übergroße Videos, die vor dem Versand noch kleingerechnet werden müssen
- für Bilder die noch im **TIFF**- (.tif), **Photoshop**- (.psd) oder **RAW**- (z.B. cr2) Format sind.

Das heißt auch, dass Ihr Fotos in solchen Formaten, die Ihr von Fotografen zugesandt bekommt, nicht als erstes gleich in die Cloud speichert – zumindest nicht ohne sie vorher ggf. in qualitativ hochwertige JPEGs umzuwandeln, da diese eine um ein Vielfaches kleinere Dateigröße haben und damit auch um ein Vielfaches schneller hochgeladen werden.

**Kurz**: Die Cloud ist **kein** Zwischenspeicher oder Arbeitslaufwerk.

# Was ihr *nicht* machen solltet #

Egal wie ihr auf die Dateien der Cloud zugreift – sie liegen im Internet und nicht auf eurem Rechner. Ihr solltet also in der Regel **nicht Dateien von der Cloud direkt zum Bearbeiten öffnen**. Das Speichern auf die Cloud ist ein Upload, das Öffnen der Datei ein Download und jedes Speichern der Datei ein erneuter Upload. Das ist natürlich langsam und auch fehleranfällig.

Ihr solltet **keine Dateien aus Programmen heraus direkt in die Cloud** speichern. Das steht im Prinzip schon oben, gilt aber auch für Dateien, die Ihr z.B. per Mail geschickt bekommt. Also auch aus Thunderbird heraus nicht direkt in die Cloud uploaden! **Erst lokal speichern, dann Uploaden!**

Niemals Dateien in der Cloud direkt auswählen und per rechter Maustaste z.B. zu einem ZIP-Archiv hinzufügen. Auch hier wäre das Download->Verarbeitung->Upload, und euer Rechner wäre minutenlang blockiert. **Stattdessen: Downloaden->Zippen->Zip-Datei hochladen**. Oder noch besser, wenn geht: Wissen, dass man ein Zip braucht, bevor man die Bilder in der Cloud parkt.

Und das wichtigste: **Nicht unbedacht losspeichern/uploaden.** Bevor ihr etwas in die Cloud speichert – wie auch immer – erst überlegen:
- Ist das **fertig**?
- Ist das nicht in einem **unnötig großen** Format?
- Gehört das überhaupt in die **Cloud** (ist das zur Kommunikation oder wird das noch editiert)?

# Was ihr machen solltet #

**Das ist jetzt ganz wichtig**: Gewöhnt euch einen Arbeitsprozess an, bei dem der Upload der Dateien in die Cloud separat und an letzter Stelle steht! Also zum Beispiel: **Bearbeitung – Kontrolle – Speichern – Upload**, oder: **Empfang – Bewertung – Speichern – Upload**

Und **verwechselt Speichern nicht mit Upload**! Nicht ‚in die Cloud speichern‘, sondern in Hamburg (bzw. in Berlin) speichern und dann in die Cloud hochladen.

**Das Schöne ist**: Es gibt Ausnahmen. Man kann mit *WinSCP* durchaus Textdokumente oder einzelne JPGs direkt zum Bearbeiten öffnen, wenn sie nicht übermäßig groß sind. Das sollte zumindest bei Bildern aber ganz klar die **Ausnahme** sein.

Solltet ihr **mehrere oder große** Dateien aus der Cloud zum Bearbeiten öffnen müssen, was natürlich nicht verboten ist, dann ladet euch diese – ggf. das ganze Verzeichnis – erst herunter, bevor ihr sie öffnet. Danach siehe oben: **Bearbeiten – Speichern – wieder Hochladen**.

# Was ist mit dem Rest, der nicht in die Cloud gehört? #

### Oder anders: Wie kann ich arbeiten? ###

Ich hatte euch versprochen, auf dem NAS ein Arbeitslaufwerk einzurichten, das ihr benutzen könnt, um große Dateien zwischenzeitlich abzulegen, die noch nicht fertig sind oder aus anderen Gründen nicht in die Cloud gehören. Das scheiterte bis jetzt daran, dass auf der NAS noch kein Platz ist. Wir sind immer noch am Dateien abgleichen. Sobald das erledigt ist, und wenn ihr uns **definitiv** und **mit einer Stimme** zusagt, dass keine neuen Model-Dateien mehr von euch auf der NAS abgelegt werden oder wurden, dann mache ich euch dort ein Arbeitslaufwerk zum internen (Hamburg) Gebrauch. Für Berlin gilt das Gleiche.

Bis dahin alles was nicht in die Cloud gehört, bitte **auf eurem Rechner zwischenspeichern**. Macht euch einen Ordner irgendwo unter Dokumente oder Bilder und benutzt diesen für Dateien, die Ihr noch sortieren, bearbeiten oder überdenken müsst.

# Ausblick #

Wir werden einen Termin mit Claudia und allen Mitarbeitern machen, wo wir die neuen Verfahren erläutern werden. Und nochmal erklären werden, was das Ganze soll ;)

Außerdem schreiben wir an einem Handbuch, das neben diesen grundsätzlichen Dingen auch noch mal die Funktionen der verschiedenen Zugriffsmöglichkeiten und deren Handhabung erklärt.

Es wird bald wieder ein NAS oder ähnlichen Netzwerkspeicher geben, auf dem ihr für den internen Gebrauch Dateien ablegen könnt.

# Software #

### WinSCP (OwnCloudSCP) ###

Wenn ihr Dateien in das WinSCP-Fenster zieht, werden diese in eine Warteschlange eingereit. Ihr müsst euch dann in der Regel nicht mehr darum kümmern und könnt weiterarbeiten. Die Warteschlange wird im Hintergrund abgearbeitet, bis sie fertig ist.

Die Upload-Geschwindigkeit beträgt für euer gesamtes Büro (Hamburg) etwa ein halbes Magabyte pro Sekunde. Das macht in acht Stunden immerhin knapp 14 GigaByte. Wenn ihr also mal eine größere Menge Daten zu übertragen habt, könnt ihr sie kurz vor Feierabend in die Warteschlange ziehen und den Rechner einfach laufen lassen. Am nächsten Morgen ist es dann fertig.

### Das Netzlaufwerk O: ###

... ist zum Kopieren, Verschieben und Hochladen von Dateien eher weniger geeignet, bietet aber gegenüber WinSCP den Vorteil, dass man hier Vorschauen von Bildern und anderen Dokumenten zu sehen bekommt. Bei einzelnen und kleineren Dateien oder Datenmengen aber durchaus auch zum Arbeiten geeignet. 

### Die Web-Oberfläche (m4models-cloud.de) ###

Hier werden Freigaben für Mitarbeiter und Kunden erstellt. Ziel wird sein, dass ihr in Zukunft hauptsächlich Links zu speziell freigegebenen Verzeichnissen versendet, statt die Bilder in Emails zu packen und herumzuschicken.

***

Soweit erst mal. Ich hoffe, es hilft euch.

Bei Fragen bitte melden!

Arne Kronberger,
Viktor Grandgeorg

