# Moodle-Plugin „Random User enroll“ - Randomisierung von authentifizierten Usern in zwei oder mehr Kursen

Im Rahmen der Masterarbeit „*Digitales Escape Game zu OER: Kognitive Belastung und Selbstwirksamkeit beim Lernen*“ von Martina Rüter (03/2021, http://dx.doi.org/10.13140/RG.2.2.10471.16808/1) wurde zur Datenerhebung ein Online-Experiment mit zwei randomisierten Gruppen durchgeführt. Hierfür wurde ein Plugin für die **Moodle-Version 3.10** entwickelt, dass eine gleichmäßige Zuteilung von authentifizierten Usern zu zwei (oder mehr) definierten Kursen ermöglichte. Um dieses Ziel zu erreichen wurde entweder der Kurs mit den wenigsten Teilnehmenden oder der erste in der Liste gewählt. Die Randomisierung ergab sich somit aus dem Zeitpunkt, zu dem die authentifizierten User das Moodle-Dashboard aufriefen, also auf den per E-Mail erhaltenen Authentifzierungslink klickten. 

Da die Randomisierung von Gruppen in der quantitativen Forschung ein Standardverfahren ist, wird das für diesen spezielle Zweck entwickelte Moodle-Plugin „**Random User enroll**“ unter der Lizenz CC0 (https://creativecommons.org/publicdomain/zero/1.0/deed.de) – **ohne Anspruch auf Support** – zur freien Nutzung und Weiterentwicklung angeboten. 

## Installation

Das Verzeichnis „autosubscripton“ herunterladen, entpacken und per FTP in das Moodle-Verzeichnis „blocks“ kopieren. 

## Konfiguration

Wählen Sie in der Website-Administration „Darstellung“ > „Dashboard für alle anpassen“. Fügen Sie den Block „HTML block für automatische Kurseinschreibung“ hinzu. Wählen Sie die Block-Einstellung „Automatische Kurseinschreibung konfigurieren“. Unter „AUTO-Kurse auswählen“ markieren Sie zwei oder mehr Kurse, denen randomisiert authentifizierte User zugeteilt werden sollen. Um die Einstellungen zu speichern, klicken Sie auf den Button „Dashboard für alle Nutzer/innen übernehmen“. 

**Hinweise:**

1. In der Website-Administration muss die „E-Mail basierte Selbstregistrierung“ aktiviert sein.
2. Bei den Kursen muss als Einschreibemethode die Selbsteinschreibung aktiviert und es darf kein Einschreibeschlüssel hinterlegt sein.
