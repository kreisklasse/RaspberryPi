# SD-Karte wieder in Ausgangszustand herstellen
# http://www.einplatinencomputer.com/raspberry-pi-sd-karte-ausgangszustand-wiederherstellen/

# unter Windows
cmd

# im neuen Shell Fenster
diskpart

# im neuen Shell Fenster
list disk

# SD-Karten Nummer heraussuchen, dann ...
select disk SD-KARTE (Nummer)

clean

create partition primary

select partition=1

active

format fs=fat32 QUICK

assign
# jetzt kann die SD_Karte normal ausgeworfen werden
