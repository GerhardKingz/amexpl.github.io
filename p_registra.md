---
layout: default
---

# Registo de ejemplares.
***
<form action="ins_pers.php" method="post">
Nombres:<br><input type="text" name="name"><br>
Apellidos:<br><input type="text" name="lastname"><br>
Contacto:<br><input type="text" name="contact"><br>
Dirección:<br><input type="text" name="address"><br>
<input type="submit">
</form>

<form action="ins_kennel.php" method="post">
Nombre del Kennel:<br><input type="text" name="criadero"><br>
Responsable ID:<br><input type="text" name="responsable"><br>
<input type="submit">
</form>

<form action="ins_ejemplar.php" method="post">
Nombre del Ejemplar:<br><input type="text" name="ejemplar"><br>
Sexo del Ejemplar:<br>
<input type="radio" id="Hembra" name="sexo" value="Hembra">
<label for="Hembra">Hembra</label><br>
<input type="radio" id="Macho" name="sexo" value="Macho">
<label for="Macho">Macho</label><br>
Fecha de Nacimiento del Ejemplar:<br><input type="date" name="fnacim"><br>
Kennel ID:<br><input type="number" name="kennelid"><br>
Responsable ID:<br><input type="number" name="responsable"><br>
Foto del Ejemplar:<br> <input type="file" name="foto"><br>
Video del Ejemplar:<br><input type="url" name="video"><br>
<input type="submit">
</form>
[inicio](./)

***
