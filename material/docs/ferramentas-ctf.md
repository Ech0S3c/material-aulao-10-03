# Habilidades, Ferramentas e Material de Estudo

## Habilidades exigidas no CTF
### 🕵️ Forense Digital (Forensics)
Forense digital envolve **analisar arquivos, imagens de disco, logs e pacotes de rede** para encontrar informações ocultas ou evidências de um ataque. Em um CTF, os desafios podem envolver a recuperação de arquivos deletados, análise de tráfego de rede ou extração de metadados de imagens.

 **🛠️ Ferramentas úteis**

🔹 `Wireshark` – Analisar pacotes de rede.  
🔹 `strings` – Extrair strings legíveis de arquivos binários.  
🔹 `exiftool` – Verificar metadados de imagens e documentos.  
🔹 `binwalk` – Extrair e analisar arquivos binários.  
🔹 `foremost` – Recuperação de arquivos deletados.  
🔹 `Volatility` – Análise forense de memória RAM.

---

### 🔐 Criptografia

A criptografia protege informações por meio de **códigos e cifras**. Em CTFs, os desafios testam o conhecimento em **decodificação, quebra de hashes, análise de cifragem e esteganografia**.

 **🛠️ Ferramentas úteis**

🔹 `dcode` – Plataforma web para conversão e decodificação.  
🔹 `hashcat` – Quebra de hashes (MD5, SHA-1, SHA-256).  
🔹 `John the Ripper` – Ataque de força bruta a senhas.  
🔹 `openssl` – Trabalha com cifragem AES, RSA, DES.  
🔹 `base64` – Codifica e decodifica textos.  
🔹 `stegsolve` – Extrai informações ocultas em imagens.

---

### 🌐 Exploração Web

Exploração web envolve encontrar e explorar **vulnerabilidades em sites e aplicações web**. Ataques comuns incluem **SQL Injection, Cross-Site Scripting (XSS), Directory Traversal e Server-Side Request Forgery (SSRF)**.

 **🛠️ Ferramentas úteis**

🔹 `Burp Suite` – Intercepta e manipula requisições HTTP.  
🔹 `sqlmap` – Testa vulnerabilidades SQL Injection.  
🔹 `XSSer` – Automatiza ataques de XSS.  
🔹 `wfuzz` – Faz fuzzing para encontrar diretórios escondidos.  
🔹 `dirb` – Descobre arquivos e pastas ocultas em servidores web.

---

### 🔍 Engenharia Reversa (Reverse Engineering)

Engenharia reversa analisa **executáveis, binários e programas compilados** para entender como funcionam sem ter acesso ao código-fonte. Em CTFs, os desafios envolvem decifrar programas, encontrar strings escondidas e explorar vulnerabilidades de software.

**🛠️ Ferramentas úteis**

🔹 `Ghidra` – Plataforma de engenharia reversa criada pela NSA.  
🔹 `IDA Pro` – Uma das ferramentas mais poderosas de engenharia reversa.  
🔹 `Radare2` – Analisador de binários avançado.  
🔹 `GDB` – Depurador para explorar programas em execução.  
🔹 `strings` – Extrai strings legíveis de arquivos binários.

---

### **🕵️ OSINT (Open Source Intelligence)**

OSINT é a arte de **coletar informações públicas** de fontes abertas, como redes sociais, bancos de dados públicos e vazamentos de dados.

 **🛠️ Ferramentas úteis**

🔹 `theHarvester` – Coleta e-mails e domínios.  
🔹 `Sherlock` – Busca perfis em redes sociais.  
🔹 `Google lens` – Busca informações de imagens no Google.  
🔹 `Maltego` – Mapeia conexões entre dados.  
🔹 `Google Dorks` – Usa o Google para encontrar dados sensíveis (`site:example.com filetype:pdf`).

## Materiais de estudo

Video super legalzinho do NetworkChuck introduzindo ciberseguranca: [https://youtu.be/uTAaFExLgwQ?si=MOLJnGE0rw0x_ICp](https://youtu.be/uTAaFExLgwQ?si=MOLJnGE0rw0x_ICp "https://youtu.be/uTAaFExLgwQ?si=MOLJnGE0rw0x_ICp") 

O que é um CTF: [https://medium.com/@ishwardeep.work/ctfs-what-are-they-and-diving-into-the-basics-a8e6fef8c312](https://medium.com/@ishwardeep.work/ctfs-what-are-they-and-diving-into-the-basics-a8e6fef8c312 "https://medium.com/@ishwardeep.work/ctfs-what-are-they-and-diving-into-the-basics-a8e6fef8c312")

https://ctf101.org/

Introducao ao Linux (com NetworkChuck): [https://youtube.com/playlist?list=PLIhvC56v63IJIujb5cyE13oLuyORZpdkL&si=tRUNnb6ZOz3YRWdn](https://youtube.com/playlist?list=PLIhvC56v63IJIujb5cyE13oLuyORZpdkL&si=tRUNnb6ZOz3YRWdn "https://youtube.com/playlist?list=PLIhvC56v63IJIujb5cyE13oLuyORZpdkL&si=tRUNnb6ZOz3YRWdn") (_sugiro fortemente o video 1, os outros ficam mais para curiosidade, porem todos sao bem informativos e **possivelmente** ajudarão bastante_) 

Site bom para aprender Linux na prática: [https://linuxjourney.com/](https://linuxjourney.com/ "https://linuxjourney.com/") 

Introdução a OSINT (**O**pen **S**ource **Int**elligence) (**BEM IMPORTANTE**): [https://medium.com/@Aardwarewolf/what-is-osint-part-1-91aaa3890643](https://medium.com/@Aardwarewolf/what-is-osint-part-1-91aaa3890643 "https://medium.com/@Aardwarewolf/what-is-osint-part-1-91aaa3890643") 

**Opcionais/curiosidades:** Por que muitos especialistas em cyber usam o famoso Kali Linux: [https://medium.com/@techlatest.net/understanding-the-benefits-of-using-kali-linux-for-penetration-testing-bfc89b8fab39](https://medium.com/@techlatest.net/understanding-the-benefits-of-using-kali-linux-for-penetration-testing-bfc89b8fab39 "https://medium.com/@techlatest.net/understanding-the-benefits-of-using-kali-linux-for-penetration-testing-bfc89b8fab39") 

**O que é CVE, CWE e NVD:** [https://medium.com/@sakeetkopparapu/what-is-cve-cwe-and-nvd-1f5c578cbdf7](https://medium.com/@sakeetkopparapu/what-is-cve-cwe-and-nvd-1f5c578cbdf7 "https://medium.com/@sakeetkopparapu/what-is-cve-cwe-and-nvd-1f5c578cbdf7") 

**Ferramentas**: Reverse Engineering: [https://ghidra-sre.org/](https://ghidra-sre.org/ "https://ghidra-sre.org/"), [https://mh-nexus.de/en/hxd](https://mh-nexus.de/en/hxd "https://mh-nexus.de/en/hxd") 

(Windows) ou GHex para Linux e [https://github.com/ReFirmLabs/binwalk](https://github.com/ReFirmLabs/binwalk "https://github.com/ReFirmLabs/binwalk")

**OSINT:** [https://lens.google/](https://lens.google/ "https://lens.google/") ou [https://images.google.com/](https://images.google.com/ "https://images.google.com/") Crypto: [https://cyberchef.org/](https://cyberchef.org/ "https://cyberchef.org/"), [https://www.dcode.fr/](https://www.dcode.fr/ "https://www.dcode.fr/") e [https://github.com/RsaCtfTool/RsaCtfTool](https://github.com/RsaCtfTool/RsaCtfTool "https://github.com/RsaCtfTool/RsaCtfTool") 

**Forensics:** [https://github.com/ReFirmLabs/binwalk](https://github.com/ReFirmLabs/binwalk "https://github.com/ReFirmLabs/binwalk")

**Misc:** [https://exiftool.org/](https://exiftool.org/ "https://exiftool.org/") ou versao online [https://exif.tools/](https://exif.tools/ "https://exif.tools/") 

**Geral:** [https://chat.openai.com/](https://chat.openai.com/ "https://chat.openai.com/") e [https://google.com/](https://google.com/ "https://google.com/") (ninguém é de ferro né)

### Material de estudo prático
https://picoctf.org/

