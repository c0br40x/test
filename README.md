<div id="image" align="center">
  <img src="https://linuxiac.b-cdn.net/wp-content/uploads/2022/01/polkit-bug.png" alt="PolKit" height="300">
</div>

---

<div id="badges" align="center">
  <img src="https://img.shields.io/badge/CVE-%20%20CVE--2021--4034%20-critical"></img>
  <img src="https://img.shields.io/badge/%40author-luijait.es-informational"></img>
  <img src="https://img.shields.io/github/downloads/c0br40x/b4cks0ck/total?label=Downloads"></img>
  <img src="https://img.shields.io/github/repo-size/c0br40x/b4cks0ck?label=Size"></img>
  <img src="https://img.shields.io/github/languages/top/luijait/PwnKit-Exploit?label=C"></img>
</div>

<div id="poc" align="center">
  <h3>POC:</h3>
  <img src="https://j.gifs.com/XQpL88.gif" height="600"></img>
</div>

---

<div id="install" align="center">
  <h3>Install:</h3>
  <img src="https://media.discordapp.net/attachments/870535335011024906/936767448831651890/unknown.png"></img>
</div>

---

<div id="explanation" align="center">
  <h3>
    Una vulnerabilidad fue encontrada en polkit y clasificada como crítica. Una función desconocida del archivo /usr/bin/pkexec es afectada por esta vulnerabilidad. Por la manipulación de un input desconocido se causa una vulnerabilidad de clase escalada de privilegios. Esto tiene repercusión sobre la confidencialidad, integridad y disponibilidad.
    
    
La vulnerabilidad fue publicada el 2022-01-26 (confirmado). El advisory puede ser descargado de qualys.com. La vulnerabilidad es identificada como CVE-2021-4034. La explotación se considera fácil. El ataque se puede efectuar a través de la red. Para explotarla se requiere una autentificación. Los detalles técnicos asi como un exploit público son conocidos.

    
Un exploit ha sido desarrollado por BLASTY en C y publicado incluso antes y no después del anuncio. Fue declarado como proof-of-concept. El exploit puede ser descargado de haxx.in. Por lo menos durante 1 días, esta vulnerabilidad fue clasificada como exploit día cero.

    
Es posible mitigar el efecto del problema mediante el uso de chmod 0755 /usr/bin/pkexec.
  </h3>
</div>
