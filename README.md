# IT-Security

In diesem Repo soll es um allgemeine Themen gehen und im deutschsprachigen Raum beheimatet sein. Ich kann zwar englisch lesen, schreiben und verstehen, aber die Muttersprache ist die Muttersprache.

Windows? Vielleicht ein wenig, aber Hauptsächlich Linux wie PiHole, OPNSense, Proxmox und vielleicht wächst das Ganze noch im Laufe der Zeit. Windows wird wahrscheinlich eher eine Randnotiz einnehmen, es sei denn, es sind allgemeine Themen wie Verschlüsselung, Zwei Faktor Authentifizierung usw. die Betriebssystemunabhängig sind.

Du fragst dich wie du mehr Sicherheit bei deinen Geräten erlangst? Ich habe schon einmal einige Punkte aufgelistet. Themen werden später auf einem Blog veröffentlich und hier soll es eingemachte gehen.

1. Nutze möglichst überall zwei Faktor Authentifizierung. Und das ganze per Fido2 Stick (z.B. dem Yubikey)
  * Bei Spotify, Amazon, Github, eurem Mailaccount, zur Anmeldung am Betriebssystem, per SSH Key für SSH Verbindungen zu deinen Services (z.B. PiHole) etc.
2. Schalte deine Tastentöne am Handy ab. Denn ja sie können abgehört werden und auf das getippte zurück schließen
3. Deinstalliere deinen Virenscanner. What denkst du? Security und Virenscanner abschalten? Dazu folgt ein Blogbeitrag
4. Nutze eine richtige Firewall (OPNSense), stell die Fri----ox in die Ecke. Basics macht sie gut, aber nichts wirklich richtig gut. Ähnlich wie ich :-D
  * Sperr am besten gleich den ganzen ausgehenden Traffic auf Port 80 :-;
6. Kauf dir nen Raspberry Pi (4+ reicht vollkommen wenn du noch eine bekommst) und installiere PiHole, konfiguriere unbound und aktiviere DNSSec / DNS over HTTPS
7. Verschlüssel möglichst jeden Datenverkehr. Beim Instant Messenger, baim mailen, beim surfen (https Pflicht, wer es nicht hat gehört nicht besucht. Siehe 4.)
8. Besorg dir ein gutes E-Mailpostfach bei einem guten Anbieter (z.B. Posteo, Protonmail oder mailbox.org) 

**Gute Quellen:
* [Kuketz Blog](www.kuketz-blog.de)
* [Morpheus Tutorials](https://www.youtube.com/channel/UCLGY6_j7kZfA1dmmjR1J_7w)
* [Heise Security](*https://www.heise.de/security/*)
* [Netzpolitik](https://netzpolitik.org)
* [ZDnet Security](https://www.zdnet.de/kategorie/security/)

**Heimnetze | Homelabs
* [SemperVideo](https://www.youtube.com/channel/UCCI6C8hD-hTZi2JEmS7zvQw) (für Basics und zum schmunzeln)
* [teqqyde](https://www.youtube.com/channel/UCnBQ7GosWO57aTpm2wR7Q7Q)
* [Raspberry Pi Cloud](https://www.youtube.com/channel/UC_76XFUys5fTO7u_HqrD7aA) Auch wenn er pfsense user ist, aber Niemand ist perfekt :-D

**Coole Inputs & Webinare (Fachwissen unbedingt notwendig)
* [Morpheus Tutorials](https://www.youtube.com/channel/UCLGY6_j7kZfA1dmmjR1J_7w)
* [Thomas Krenn](https://www.youtube.com/user/ThomasKrenn)
* [Christian Zengel](https://www.youtube.com/user/sysopstv) 
