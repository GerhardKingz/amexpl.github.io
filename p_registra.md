---
layout: default
---
# Registo de ejemplares.
***

### Primero regístrate como Dueño Responsable (Anota tu ID que se te generará!)
<form action="http://152.70.122.144/amexpl/ins_pers.php" method="post" target="_blank">
Nombres:<br><input type="text" name="name"><br>
Apellidos:<br><input type="text" name="lastname"><br>
Contacto:<br><input type="text" name="contact"><br>
Dirección:<br><input type="text" name="address"><br>
<input type="submit"><br><br>
</form>

### Una vez que te has registrado como Dueño Responsable, puedes registrar tu Kennel (deberás proporcionar tu Id obtenido en el paso anterior.)
<form action="http://152.70.122.144/amexpl/ins_kennel.php" method="post" target="_blank">
Nombre del Kennel:<br><input type="text" name="criadero"><br>
Responsable ID:<br><input type="text" name="responsable"><br>
<input type="submit"><br><br>
</form>

### Ahora ya puedes registrar a uno o a varios de tus ejemplares (deberás proporcionar el Id del Kennel o el de Dueño Responsable generados en los pasos anteriores)
<form action="http://152.70.122.144/amexpl/ins_ejemplar.php" method="post" target="_blank">
Nombre del Ejemplar:<br><input type="text" name="ejemplar"><br>
Sexo del Ejemplar:<br>
<input type="radio" id="Hembra" name="sexo" value="Hembra">
<label for="Hembra">Hembra</label><br>
<input type="radio" id="Macho" name="sexo" value="Macho">
<label for="Macho">Macho</label><br>
Fecha de Nacimiento del Ejemplar:<br><input type="date" name="fnacim"><br>
Kennel ID:<br><input type="number" name="kennelid" value="-1"><br>
Responsable ID:<br><input type="number" name="responsable" value="-1"><br>
Foto del Ejemplar:<br> <input type="file" name="foto"><br>
Video del Ejemplar:<br><input type="url" name="video"><br>
<input type="submit">
</form>
[inicio](./)

***
