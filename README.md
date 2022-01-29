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

---

<div id="poc" align="center">
  <h3>POC:</h3>
  <img src="https://j.gifs.com/XQpL88.gif" width=600 height="400"></img>
</div>

---

<div id="install" align="center">
  <h3>Install:</h3>
  <img src="https://media.discordapp.net/attachments/870535335011024906/936767448831651890/unknown.png"></img>
</div>

---

<div id="explanation" align="center">
  <h3>
    Explanation:
  </h3>
</div>

Una vulnerabilidad fue encontrada en `polkit` y clasificada como critica. Una funcion desconocida del archivo `/usr/bin/pkexec/` es afectada por esta vulnerabilidad. Por la manipulacion de un input desconocido se causa una vulnerabilidad de clase escalada de privilegios / escalation privilages. Esto tiene repercusion sobre la confidencialidad, integridad y disponibilidad.

La vulnerabilidad fue publicada el `2022-01-26`. El advisory puede ser descargada desde `qualys.com`. La vulnerabilidad es identificada como `CVE-2021-4034`. La explotacion se considera facil. El ataque se puede efectuar a traves de la red. Para explotarla se requiere una autentificacion. Los detalles tecnicos asi como un exploit publico son conocidos.

Es posible mitigar el efecto del problema mediante el uso de `chmod 0755 /usr/bin/pkexec`.

---

<div align=center>
  <h3>Memes in community:</h3>
  <img src="https://user-images.githubusercontent.com/60628803/151507343-b49df170-c853-47c9-aac1-740302e435f9.png" width=400px height=250px>
</div>

---

<div align="center">
  <h3><br>Readme made by: <a href="https://github.com/c0br40x">c0br40x</br></h3>
</div>

---

