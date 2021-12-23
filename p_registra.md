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

### Ahora ya puedes registrar a uno o a varios de tus ejemplares (WD - WolfDog)(deberás proporcionar el Id del Kennel o el de Dueño Responsable generados en los pasos anteriores)
<form action="http://152.70.122.144/amexpl/ins_ejemplar.php" method="post" target="_blank">
Nombre de tu WD:<br><input type="text" name="ejemplar"><br>
Sexo detu WD:<br>
<input type="radio" id="Hembra" name="sexo" value="Hembra">
<label for="Hembra">Hembra</label><br>
<input type="radio" id="Macho" name="sexo" value="Macho">
<label for="Macho">Macho</label><br>
Fecha de Nacimiento:<br><input type="date" name="fnacim"><br>

Porcentaje (Contenido de sangre de Lobo):<br>
<input type="radio" id="LC" name="porcentaje" value="LC">
<label for="LC">Bajo Contenido (LowContent) 1% - 50% </label><br>
<input type="radio" id="MC" name="porcentaje" value="MC">
<label for="MC">Medio Contenido (MidContent) 51% - 75% </label><br>
<input type="radio" id="HC" name="porcentaje" value="HC">
<label for="HC">Alto Contenido (HighContent) 76% - 99% </label><br>
  
Prueba de ADN:<br>
<input type="radio" id="Embark" name="prueba" value="Embark">
<label for="Embark">Embark</label><br>
<input type="radio" id="EasyDNA" name="prueba" value="EasyDNA">
<label for="EasyDNA">EasyDNA</label><br>
<input type="radio" id="MyHeritage" name="prueba" value="MyHeritage">
<label for="MyHeritage">MyHeritage</label><br>
<input type="radio" id="WisdomPanel" name="prueba" value="WisdomPanel">
<label for="WisdomPanel">WisdomPanel</label><br>
<input type="radio" id="Otra" name="prueba" value="Otra">
<label for="Otra">Otra</label><br>

Número de Registro (en caso de contar con Prueba de ADN):<br><input type="text" name="regprueba" value="0"><br>
Padre (Escribe el ID en caso de contar con él):<br><input type="number" name="fatherid" value="-1"><br>
Madre (Escribe el ID en caso de contar con él):<br><input type="number" name="motherid" value="-1"><br>
Kennel ID:<br><input type="number" name="kennelid" value="-1"><br>
Responsable ID:<br><input type="number" name="responsable" value="-1"><br>
Foto del Ejemplar:<br> <input type="file" name="foto"><br>
Video del Ejemplar:<br><input type="url" name="video"><br>
<input type="submit">
</form>
[inicio](./)

***
