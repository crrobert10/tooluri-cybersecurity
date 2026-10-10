# tooluri-cybersecurity
Listă de unelte și comenzi utile pentru competițiile de tip CTF

# Repartizare pe categorii

# 🔍 OSINT:

- Reverse Google Image Search = pentru a identifica o imagine
- Reverse username search site sau toolul sherlock de pe terminal = pentru a cauta un username pe Internet
- Flightradar24 / ADS-B Exchange = pentru a verifica istoricul zborurilor trecute sau prezente
- Exif image viewer site cum ar fi exifdata.com sau toolul exiftool de pe terminal = pentru a vedea detalli despre cand a fost facuta o imagine
- Wayback Machine (archive.org) = pentru a vedea versiuni vechi ale unor site-uri sau pagini șterse
- shodan.io = OSINT tool suprem

# 🧩 Steganography:

🖼️ Imagini:

- AperiSolve (aperisolve.com) = rulează automat zsteg, steghide, outguess, exiftool și binwalk dintr-un singur upload, de multe ori siteul este inactiv
- outhorseyourstego.com = varianta alternativa pentru AperiSolve
- exiftool
- binwalk
- binwalk -e = pentru a extrage fisiere ascunse din imagini
- steghide
- stegseek
- stegsolve.jar = pentru a schimba colorizarea imaginilor si a vedea mesaje ascunse
- zsteg = unealtă CLI excelentă pentru analizat imagini PNG/BMP pe layere LSB (Least Significant Bit) 

🔊 Audio:

- Audacity, view spectogram la setari = pentru a vedea mesaje ascunse in vibratiile audio

# ⚙️ Reverse Engineering și Binary Exploitation (Pwn):

- checksec = verifica ce protocoale de securitate are un executabil
- ghidra = tool pentru a vedea codul unui executabil
- gdb = util pentru buffer overflow si pentru a intelege memoria programului
- pwndbg = extensie pentru gdb care adaugă o interfață vizuală în terminal pentru registre, stivă și instrucțiuni Assembly

# 🔬 Forensics:

- Wireshark / tshark = analiza traficului de rețea din fișiere .pcap sau .pcapng
- Volatility 3 = unealta supremă pentru analiza fișierelor de memorie RAM (memory dumps)
- Strings = comanda din terminal (strings <file> | grep -i "flag") pentru a extrage text vizibil dintr-un fișier binar sau necunoscut
- FTK Imager = pentru analiza imaginilor de disc/sisteme de fișiere (Windows/Linux)
- foremost = pentru a repara fisiere png

# 🌐 Web Exploitation

- Burp Suite = proxy esențial pentru interceptarea, modificarea și analiza cererilor HTTP/HTTPS
- OWASP ZAP = alternativă open-source gratuită la Burp Suite, se poate folosi si cu acelasi scop ca gobuster
- gobuster = unealta rapida din terminal pentru fuzzer de directoare, fișiere și subdomenii (gobuster dir -u <URL> -w <wordlist>)
- SQLMap = automatizare pentru detectarea și exploatarea vulnerabilităților de tip SQL Injection (sqlmap -u <URL> --batch)

# 🔐 Cryptography

- CyberChef = pentru cifruri clasice (Caesar, Vigenère, ROT13, Rail Fence)
- dcode.fr = pentru mai multe cifruri
- CrackStation = librarie de hashuri
