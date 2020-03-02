# Calliope-Mini Tips und Tricks


# Tools

- [TigerJython](http://www.tigerjython.ch) als Code-Editor und zum Flashen von MicroPython
- [putty](https://the.earth.li/~sgtatham/putty/latest/w64/putty.exe) um interaktiv mit Callipe zu arbeiten.
  - Großer Vorteil ggü TigerJython: In Putty kann man per TAB das eingetippte Kommando vervollständigen.
    Zum schnellen Ausprobieren ist das super.
  - Nachteil ggü TigerJython: Was man eintippt ist nur temporär, also "weg", sobald man Calliope neu startet/Strom abstellt/...
- Um unter Windows den aktuellen COM-Port herauszufinden, um mit Calliope zu sprechen, in der Powershell folgendes eingeben:

        Get-WmiObject Win32_SerialPort | Select -ExpandProperty Name
        
    Das sollte eine Ausgabe wie bspw.
    
        Intel(R) Active Management Technology - SOL (COM3)
        USB Serial Device (COM4)
        
    ergeben -- das `USB Serial Device` ist Calliope, also hier am `COM4`.


## Installationstips

Zur Installation unter Windows auch ohne Admin-Rechte siehe
[hier](https://gist.github.com/kopp/74856887e17e10605d56f1a088455464).



# Wichtige Seiten

- [TigerJython4Kids.ch](https://www.tigerjython4kids.ch/index.php?inhalt_links=robotik/navigation.inc.php&inhalt_mitte=robotik/calliope/calliope.inc.php)
