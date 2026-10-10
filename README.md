# tooluri-cybersecurity
Listă de unelte și comenzi utile pentru competițiile de tip CTF

# Repartizare pe categorii

#OSINT:

-Pentru a identifica o imagine: - Reverse Google Image Search
-Pentru a cauta un username pe Internet: - reverse username search site sau toolul sherlock de pe terminal
-Pentru a verifica istoricul zborurilor trecute sau prezente : - ADS-B Exchange
-Pentru a vedea detalli despre cand a fost facuta o imagine: - exif image viewer site cum ar fi exifdata.com sau toolul exiftool de pe terminal
-OSINT tool suprem: shodan.io

#Steganography:
Imagini:
-outhorseyourstego.com - varianta alternativa pentru AperiSolve
-exiftool pe terminal
-binwalk
-binwalk -e -- pentru a extrage fisiere ascunse din imagini
-steghide
-stegseek
-stegsolve.jar -- pentru a schimba colorizarea imaginilor si a vedea mesaje ascunse 

Audio:
-Audacity, view spectogram la setari -- pentru a vedea mesaje ascunse in vibratiile audio
-Reverse Engineering:
-checksec -- verifica ce protocoale de securitate are un executabil
-ghidra -- tool pentru a vedea code-ul unui executabil
-gdb -- util pentru buffer overflow si pentru a intelege memoria programului

#Forensics:
-foremost -- pentru a repara fisiere png
