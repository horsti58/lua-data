# lua-data

diverse Neutrino Sat-Settings 28.2E, 23.5E, 19.2E, 16.0E, 13.0E, 9.0E

 # Anleitung lua Plugin:

 wegen Sicherheitsänderungen auf github, kann es sein das die Settings nicht ladbar sind,

 dann settingsupdater.lua und cfg Datei erneuern. Die Prüfung des Serverzertifikats ist von Haus aus
 aus, weil nicht jedes Image aktuelle CA-Zertifikate hat; wer sie hat, schaltet sie in den Einstellungen
 (Taste rot) unter "Zertifikat des Servers prüfen" ein.

 settingsupdater.cfg, settingsupdater.lua und settingupdater.svg ins Pluginverzeichnis /var/tuxbox/plugins der Neutrinobox kopieren,

 restarten...

 Settingsupdater Plugin findet man dann in der Box unter Menü, Service

*  Taste rot: Sat/Kabelpositionen auswählen, die man nutzen möchte

*  Taste grün: Settings werden online in die Box geladen


 Sat-Settings bestehen aus satellites.xml, bouquets.xml und service.xml

 keine ubouquets.xml enthalten, denn da gibt es zuviele Geschmäcker :)


29.11.2025
